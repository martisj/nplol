source 'https://rubygems.org'

ruby '2.0.0'

gem 'airbrake'
gem 'bourbon'
gem 'neat'
gem 'jquery-rails'
gem 'coffee-rails'
gem 'delayed_job_active_record', '>= 4.0.0'
gem 'email_validator'
gem 'flutie'
gem 'high_voltage'
gem 'jquery-rails'
gem 'neat'
gem 'pg'
gem 'rack-timeout'
gem 'rails', '>= 4.0.0'
gem 'recipient_interceptor'
gem 'sass-rails'
gem 'simple_form'
gem 'uglifier'
gem 'unicorn'

# redcarpet for markdown
gem 'redcarpet'

# haml view engine
gem 'haml'

# use rspec for testing
gem 'rspec-rails', :group => [:development, :test]

group :development do
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'foreman'
end

group :test do
  gem 'factory_girl_rails'
  gem 'capybara-webkit', '>= 1.0.0'
  gem 'database_cleaner'
  gem 'launchy'
  gem 'shoulda-matchers'
  gem 'simplecov', require: false
  gem 'timecop'
  gem 'webmock'
end

group :staging, :production do
  gem 'newrelic_rpm', '>= 3.6.7'
  gem 'rails_12factor'
end
