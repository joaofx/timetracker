source 'https://rubygems.org'


gem 'rails', '4.1.7'
gem 'pg'
gem 'sass-rails', '~> 4.0.3'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.0.0'
gem 'jquery-rails'

gem 'bootstrap-sass', '~> 3.3.1'
gem 'devise'

gem 'tzinfo-data', platforms: [:mingw, :mswin]

group :development, :test do
	gem 'guard'
	gem 'guard-livereload'
	gem 'guard-rspec'
	gem 'rspec-rails'
	gem 'capybara'
	gem 'factory_girl_rails'
	gem 'database_cleaner'
	gem 'shoulda-matchers'
end

require 'rbconfig'
if RbConfig::CONFIG['target_os'] =~ /mswin|mingw|cygwin/i
  gem 'wdm', '>= 0.1.0'
end