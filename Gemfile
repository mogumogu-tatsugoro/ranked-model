source "https://rubygems.org"

# Specify your gem's dependencies in ranked-model.gemspec
gemspec

group :sqlite do
  gem 'sqlite3', '~> 1.4'
end

gem 'debug', group: [:development, :test]

group :postgresql do
  gem "pg", platform: :ruby
end

group :mysql do
  gem "mysql2", platform: :ruby
end
