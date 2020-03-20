# rubocop:disable Metrics/LineLength, Layout/LeadingCommentSpace

source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem 'rails', '5.2.4.2'

# select the appropriate gem below for your database:
gem 'mysql2'
#gem 'pg'

gem 'activemodel-serializers-xml'
gem 'activerecord-session_store', '>= 1.1.1'
gem 'acts_as_list'
gem 'acts_as_taggable_on_steroids', github: 'seven1m/acts_as_taggable_on_steroids'
gem 'authority'
gem 'bcrypt'
gem 'bootstrap-sass'
gem 'bugsnag'
gem 'builder'
gem 'coffee-rails', '>= 4.2.2'
gem 'country_select'
gem 'date_validator'
gem 'draper', '>= 3.0.0'
gem 'erubis'
gem 'feedjira'
gem 'flag_shih_tzu'
gem 'font-awesome-rails', '>= 4.7.0.4'
gem 'geocoder'
gem 'github_api'
gem 'haml'
gem 'highline'
gem 'html_truncator'
gem 'httparty'
gem 'jquery-rails', '>= 4.3.1'
gem 'load_and_authorize_resource', '>= 0.4.1'
gem 'loofah'
gem 'mini_magick'
gem 'mustache'
gem 'nokogiri'
gem 'omniauth-facebook'
gem 'paperclip'
gem 'prawn'
gem 'pusher'
gem 'rails_autolink', '>= 1.1.6'
gem 'react-rails', '>= 2.2.1'
gem 'responders', '>= 2.4.0'
gem 'sanitize'
gem 'sass-rails', '>= 5.0.6'
gem 'strong_password'
gem 'sucker_punch'
gem 'thin'
gem 'tzinfo-data'
gem 'uglifier'
gem 'webpacker', '>= 3.0.2'
gem 'whenever'
gem 'will_paginate'
gem 'will_paginate-bootstrap'
gem 'with_advisory_lock'

group :test do
  gem 'factory_girl_rails', '>= 4.8.0'
  gem 'rails-controller-testing', '>= 1.0.2'
  gem 'shoulda-matchers', github: 'thoughtbot/shoulda-matchers'
  gem 'webmock'
end

group :development do
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'capistrano'
  gem 'capistrano-bundler'
  gem 'capistrano-newrelic'
  gem 'capistrano-rails'
  gem 'capistrano-yarn'
  gem 'observr'
  gem 'terminal-notifier'
end

group :development, :test do
  gem 'guard-rspec', require: false
  gem 'pry'
  gem 'pry-rails'
  gem 'pry-remote'
  gem 'rspec-rails', '>= 3.6.1'
  gem 'spring'
  gem 'spring-commands-rspec'
  gem 'timecop'
end

group :production do
  gem 'newrelic_rpm'
end
