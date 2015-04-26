source 'https://rubygems.org'
ruby "2.1.6"

# Backend
gem 'rails', '4.2.0'
gem 'pg'

# Tools
gem 'brandify'
gem 'heroku_secrets', github: 'alexpeattie/heroku_secrets'

# Server
gem 'thin', group: :development
gem 'unicorn'

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
