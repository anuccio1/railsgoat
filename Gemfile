# frozen_string_literal: true
source "https://rubygems.org"

#don't upgrade
gem "rails", "5.2.4.2"

ruby "2.5.3"

gem "aruba"
gem "bcrypt"
gem "coffee-rails", ">= 4.2.2"
gem "execjs"
gem "foreman"
gem "jquery-fileupload-rails", ">= 0.4.7"
gem "jquery-rails", ">= 4.3.3"
gem "minitest"
gem "powder" # Pow related gem
gem "pry-rails" # not in dev group in case running via prod/staging @ a training
gem "puma"
gem "rails-perftest"
gem "rake"
gem "responders" , ">= 2.4.0" #For Rails 4.2 # LOCKED DOWN
gem "ruby-prof"
gem "sass-rails", ">= 5.0.7"
gem "simplecov", require: false, group: :test
gem "sqlite3"
gem "therubyracer"
gem "turbolinks"
gem "uglifier"
gem "unicorn"

# Add SMTP server support using MailCatcher
# NOTE: https://github.com/sj26/mailcatcher#bundler
# gem 'mailcatcher'

group :development, :mysql do
  gem "better_errors"
  gem "binding_of_caller"
  gem "brakeman"
  gem "bundler-audit"
  gem "guard-brakeman"
  gem "guard-livereload"
  gem "guard-rspec"
  gem "guard-shell"
  gem "pry"
  gem "rack-livereload"
  gem "rb-fsevent"
  gem "rubocop-github"
  gem "travis-lint"
end

group :development, :test, :mysql do
  gem "capybara"
  gem "database_cleaner"
  gem "launchy"
  gem "poltergeist"
  gem "rspec-rails", ">= 3.8.1"
  gem "test-unit"
end

group :mysql do
  gem "mysql2"
end
