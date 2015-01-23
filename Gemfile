source 'https://rubygems.org'

# Backend
gem 'rails', '4.2.0'
gem 'pg'

# Server
gem 'unicorn'
gem 'thin', group: :development
gem 'capistrano-rails', group: :development

# Styling
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'foundation-rails'
gem 'foundation-icons-sass-rails'

# Javascript
gem 'turbolinks'
gem 'jquery-turbolinks'
gem 'jquery-rails'
gem 'coffee-rails', '~> 4.1.0'
gem 'jbuilder', '~> 2.0'
gem "jquery-slick-rails"

# Templating
gem 'slim'
gem 'slim-rails', group: :development
gem 'simple_form'

group :development do
  gem 'quiet_assets'
  gem 'better_errors'
  gem 'binding_of_caller'
end

group :development, :test do
  gem 'rspec-rails'
  gem 'faker'
  gem 'factory_girl_rails'
  gem 'pry-byebug'
  gem 'spring'
end

group :test do
  gem "codeclimate-test-reporter", require: false
  gem 'database_cleaner'
  gem 'vcr'
  gem 'webmock'
  gem 'mocha'
  gem 'capybara', '>= 2.2.0'
  gem 'capybara-screenshot'
  gem 'spinach-rails'
  gem 'poltergeist'
end

