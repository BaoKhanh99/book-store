# frozen_string_literal: true

source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.1.1"

gem "bootsnap", require: false
gem "bootstrap"
gem "config"
gem "devise"
gem "dotenv-rails"
gem "importmap-rails"
gem "jbuilder"
gem "jquery-rails"
gem "mysql2", "~> 0.5"
gem "puma", "~> 5.0"
gem "rails", "~> 7.0.4", ">= 7.0.4.1"
gem "sprockets-rails"
gem "stimulus-rails"
gem "turbo-rails"
gem "tzinfo-data", platforms: %i(mingw mswin x64_mingw jruby)
group :development, :test do
  gem "debug", platforms: %i(mri mingw x64_mingw)
  gem "pry-nav"
  gem "pry-rails"
  gem "rubocop-checkstyle_formatter"
  gem "rubocop-performance"
  gem "rubocop-rails"
end

group :development do
  gem "web-console"
end

group :test do
  gem "capybara"
  gem "selenium-webdriver"
  gem "webdrivers"
end
