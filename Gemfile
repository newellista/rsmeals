source 'https://rubygems.org'

gem 'rails', '3.2.6'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

gem 'mysql2'


# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails', "  ~> 3.2.3"
  gem 'uglifier', '>= 1.0.3'
  gem 'yui-compressor'
  gem 'ejs'
  gem 'jade'
  gem 'bootstrap-sass', '~> 2.0.0'
  gem 'compass-rails'
  gem 'therubyracer', '0.11.0beta5'
end

group :test do
  gem 'cucumber-rails', "~> 1.3.0", require: false
  gem 'launchy'
  gem 'database_cleaner'
end

gem 'jquery-rails'

group :development, :test do
  gem 'rspec-rails'
  gem 'annotate', '~> 2.4.1.beta1'
  gem 'factory_girl_rails'
  gem 'jasmine'
  gem 'guard-rspec'
  gem 'guard-bundler'
  gem 'guard-cucumber'
  gem 'thin'
  gem 'quiet_assets'
  gem 'pry-rails'
  gem 'capybara'
  gem 'sextant' # Remove in rails 4 as this has been merged in
  gem 'debugger'
  gem 'awesome_print'
end

group :development do
  gem 'rb-fsevent'
end
