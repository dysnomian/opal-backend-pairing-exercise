source 'https://rubygems.org'

gem 'rails', '4.2.6'
gem "rails-api"
gem 'pg', '~> 0.15'
gem "rack"

# SERVERS
gem "thin"
gem "puma"
gem "unicorn"

# API
gem "grape"
gem "grape-swagger"

# HTTP CLIENT
gem "rest-client"

# SERIALIZERS
gem "jbuilder"
gem "active_model_serializers"
gem "rabl-rails"

group :development, :test do
  gem "minitest"
  gem "test-unit"
  gem "byebug"
  gem "rspec-rails",          require: false
  gem "factory_girl_rails"
  gem "awesome_print",        require: "ap"
  gem "cucumber-rails",       require: false
  gem "database_cleaner"
  gem "pry-rails"
  gem "pry-nav"
  gem "zeus"
end

group :development do
  gem "meta_request"
  gem "better_errors",        require: false
  gem "binding_of_caller",    require: false
  gem "web-console"
  gem "rubocop"
  gem "rails_best_practices"
  gem "brakeman"
end

