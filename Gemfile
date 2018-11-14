source 'https://rubygems.org'

gem 'rails', '~> 5.0.1'
gem 'app'
gem 'pg'
gem 'nokogiri',    '>= 1.6.8' # security update
gem 'rack-attack'
gem "simple_form", ">= 3.3.1"

# Front End
gem 'haml'
gem 'jquery-rails', '>= 4.2.1'
gem 'lodash-rails', '>= 4.17.2'
gem 'sass-rails', '>= 5.0.6'
gem 'twitter-bootstrap-rails', '>= 3.2.2'
gem 'jquery-ui-rails', '>= 5.0.5', '< 6' # fixes active admin dep issue

# activeadmin
gem 'activeadmin'        , git: 'https://github.com/activeadmin/activeadmin'
gem 'inherited_resources', git: 'https://github.com/activeadmin/inherited_resources'
gem 'devise', '>= 4.2.0'

# Services
gem 'analytics-ruby', require: 'segment'
gem "intercom-rails", ">= 0.3.4"
gem 'newrelic_rpm'
gem 'rollbar'
gem 'sendwithus_ruby_action_mailer'
gem "skylight", ">= 1.0.1"

group :development do
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'bullet', '>= 5.4.3'
  gem 'foreman'
  gem 'git-up'
  gem 'meta_request', '>= 0.4.0'
  gem 'powder'
  gem 'spring-commands-rspec', '>= 1.0.4'
  gem 'wirble'
  # gem 'heroku' # deprecated and replaced with the Heroku Toolbelt
  # gem 'mailcatcher' # Please install outside of bundle
end

group :development, :test do
  gem "awesome_print", :require => "ap"
  gem 'dotenv-rails', '>= 2.1.1'
  gem 'factory_girl_rails', '>= 4.8.0'
  gem 'pry-rails'
  gem 'tapp'
end

group :test do
  gem 'capybara'
  gem 'codeclimate-test-reporter', require: nil
  gem 'database_cleaner'
  gem 'fuubar'
  gem 'poltergeist'
  gem 'phantomjs', :require => 'phantomjs/poltergeist'
  gem 'rspec-its'
  gem 'rspec_junit_formatter'
  gem 'rspec-rails', '>= 3.5.2'
  gem 'rspec-retry'
  gem 'simplecov'
  gem 'webmock'
  # rspec guard
  # gem 'rspec-nc'
  # gem 'guard-rspec'
end
group :assets do
  gem 'coffee-rails', '>= 4.2.1'
  gem 'uglifier'
end

group :production do
  gem 'rails_12factor'
  gem 'therubyracer'
  gem 'unicorn'
end
