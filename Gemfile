source 'https://rubygems.org'
# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.0.0.rc1'
# Use jquery as the JavaScript library
gem 'jquery-rails'

# Use devise for user authentication
gem 'devise'
# As devise uses attr_accessible
gem 'protected_attributes'
# Use this to customize devise form
# This is a requirement for simple_form:install --bootstrap to work with rails 4
gem 'simple_form', '~> 3.0.0.beta1'

group :production do
  # For Heroku
  # ruby "2.0.0"
  gem 'pg'
end

group :development, :test do
  gem 'sqlite3'
end

group :assets do
  # Use SCSS for stylesheets
  gem 'sass-rails', '~> 4.0.0.rc1'
  # Use Uglifier as compressor for JavaScript assets
  gem 'uglifier', '>= 1.3.0'
  # Use CoffeeScript for .js.coffee assets and views
  gem 'coffee-rails', '~> 4.0.0'
 end
# for good and flat design
gem 'flatstrap-sass', '~> 2.3.1.0'
# gem 'bootstrap-sass','~>2.3.1.3'


# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 1.0.1'

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end

# Use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]
