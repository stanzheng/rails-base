source 'https://rubygems.org'

gem 'rails',       '~> 4.2.1'
gem 'app'
gem 'pg'
gem 'nokogiri',    '>= 1.6.8' # security update
gem 'rest-client', '>= 1.8.0' # security update
gem "simple_form"

# Front End
gem 'haml'
gem 'jquery-rails'
gem 'less-rails'
gem 'lodash-rails'
gem 'sass-rails'
gem 'twitter-bootstrap-rails'

# activeadmin
gem 'activeadmin', '~> 1.0.0.pre2'
gem 'devise',      '~> 3.2'

# Services
gem 'dailycred'
gem "intercom-rails"
gem 'newrelic_rpm'
gem 'rollbar'
gem "skylight"

group :development do
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'bullet'
  gem 'foreman'
  gem 'git-up'
  gem 'meta_request'
  gem 'powder'
  gem 'spring-commands-rspec'
  gem 'wirble'
  # gem 'heroku' # deprecated and replaced with the Heroku Toolbelt
  # gem 'mailcatcher' # Please install outside of bundle
end

group :development, :test do
  gem "awesome_print", :require => "ap"
  gem 'dotenv-rails'
  gem 'factory_girl_rails'
  gem 'pry-rails'
  gem 'tapp'
end

group :test do
  gem 'capybara'
  gem 'codeclimate-test-reporter', group: :test, require: nil
  gem 'database_cleaner'
  gem 'fuubar'
  gem 'rspec-its'
  gem 'rspec_junit_formatter'
  gem 'rspec-rails'
  # rspec guard
  # gem 'rspec-nc'
  # gem 'guard-rspec'
end

group :assets do
  gem 'coffee-rails'
  gem 'uglifier'
end

group :production do
  gem 'rails_12factor'
  gem 'therubyracer'
  gem 'unicorn'
end