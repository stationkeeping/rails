source 'https://rubygems.org'

gem 'rails', '3.2.13'

# Servers

# Unicorn
gem 'unicorn'

# POW management
gem 'powder'

# Routing

# Slugs
gem 'friendly_id'
# Organise single pages
gem "high_voltage"

# Envs loaded into development
gem 'dotenv'

# Database
gem 'pg'
# Check for missing indexes in Database
gem 'lol_dba'

# Models

# Ordering for model
gem 'acts_as_list'

# File Upload
gem 'paperclip'

# Hosting
gem 'heroku'
# Process Management
gem 'foreman'
# Heroku Commands
gem 'heroku_san'
# Gzip files served from Heroku
gem 'heroku_rails_deflate', :group => :production

# Storage
# Official Amazon S3 Gem
gem 'aws-sdk'

# Auth
gem 'devise'
gem 'rolify'
gem 'cancan'
gem 'omniauth'

# API

# JSON
require 'json'
# Serialise Models to JSON
gem "active_model_serializers"

# UI

# Responsive Grids
gem 'susy'
# Bootstrap 
gem 'bootstrap-sass'
# Better forms
gem 'simple_form'
# Loading Spinner
gem 'spinjs-rails'
# Pagination
gem 'will_paginate'

# JavaScript
gem 'jquery-rails'
gem 'jquery-fileupload-rails'

# Angular
gem 'angularjs-rails'
# Attach CRSF token to API requests
gem 'ng-rails-csrf', :git => "git://github.com/xrd/ng-rails-csrf.git"

# Markdown
gem "redcarpet"

# Media
gem 'vimeo'

# Gems used only for assets and not required
# in production environments by default.

group :assets do
  # CSS Precompiler
  gem 'sass-rails'
  # Sass mixin library
  gem 'compass'
  gem 'compass-rails'
  # Minifier
  gem 'uglifier'
  # Automatically store and retrieve assets from S3 bucket
  gem 'asset_sync'
end

# Debugging and Logging

gem 'log4r', :group => [:development, :test, :staging]
# Supress asset pipeline logging
gem 'quiet_assets', :group => :development
# Better Errors
gem 'better_errors', :group => :development
gem 'binding_of_caller', :group => :development
# Rails Panel (Chrome Extension)
gem 'meta_request', :group => [:development, :test, :staging]

# Testing

gem 'rspec-rails', :group => :test
gem 'cucumber-rails', :group => :test
gem 'factory_girl', :group => :test
gem 'capybara', :group => :test
