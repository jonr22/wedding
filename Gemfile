source "https://rubygems.org"

ruby "2.1.2"

gem "airbrake"
gem 'bootstrap-sass'
gem "coffee-rails"
gem "delayed_job_active_record"
gem "email_validator"
gem "high_voltage"
gem "jquery-rails"
gem 'paperclip', '~> 3.0'
gem "pg"
gem "rack-timeout"
gem "rails", "4.1.4"
gem "recipient_interceptor"
gem "sass-rails", "~> 4.0.3"
gem "simple_form"
gem "title"
gem "uglifier"
gem "unicorn"

# gem 'devise'
# gem 'omniauth-facebook'
# gem 'omniauth-twitter'
# gem 'twitter'
# gem 'fb_graph'
# gem 'cancan'

group :development do
  gem "spring"
  gem "spring-commands-rspec"

  gem 'guard'
  gem 'guard-rspec', require: false
  gem 'guard-livereload', require: false
  gem 'rack-livereload'
  gem 'terminal-notifier-guard'
end

group :development, :test do
  gem "awesome_print"
  gem "byebug"
  gem "dotenv-rails"
  gem "factory_girl_rails"
  gem "pry-rails"
  gem "rspec-rails", "~> 3.0.0"
end

group :test do
  gem "capybara-webkit", ">= 1.2.0"
  gem "database_cleaner"
  gem "formulaic"
  gem "launchy"
  gem "shoulda-matchers", require: false
  gem "timecop"
  gem "webmock"
end

group :staging, :production do
  gem "newrelic_rpm", ">= 3.7.3"
  # gem 'aws-sdk', '~> 1.5.7'
end
