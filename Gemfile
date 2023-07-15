# frozen_string_literal: true

source 'https://rubygems.org'

git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.2.2'

gem 'rails', '~> 7.0.4.2'

gem 'mysql2', '~> 0.5'
gem 'puma', '~> 5.0'
gem 'sprockets-rails'
gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]

group :development, :test do
  gem 'debug', platforms: %i[mri mingw x64_mingw]
  gem 'pry-byebug'
  gem 'factory_bot_rails', '6.2.0'
  gem 'factory_bot', '6.2.1'
end

gem 'rspec-rails', '6.0.2'
gem 'rspec-core', '3.12.2'
gem 'rspec-expectations', '3.12.3'
gem 'rspec-mocks', '3.12.5'
gem 'rspec-support', '3.12.0'
gem 'devise'

group :development do
  gem 'rubocop', require: false
  gem 'rubocop-performance'
  gem 'rubocop-rails'
  gem 'rubocop-rspec'
  gem 'solargraph'
end
