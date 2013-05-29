source 'https://rubygems.org'

gem 'rails', '3.2.13'

# Server
gem "unicorn"

# POW helpers
gem 'powder'

# Envs loaded into development
gem 'dotenv'

# Database
gem 'pg'

# File Upload
gem 'paperclip'

# Hosting
gem "heroku"
# Gzip files served from Heroku
gem 'heroku_rails_deflate', :group => :production

# Storage
# Official Amazon S3 Gem
gem 'aws-sdk'

# Auth
gem 'devise'
gem 'rolify'
gem 'cancan'

# JSON
require 'json'

# API
# Serialise Models to JSON
gem "active_model_serializers"

# UI
gem 'bootstrap-sass'
gem 'simple_form'
gem "susy"

# JavaScript
gem 'jquery-rails'
gem 'jquery-fileupload-rails'

# Angular
gem 'angularjs-rails'
# Attach CRSF token to API requests
gem 'ng-rails-csrf', :git => "git://github.com/xrd/ng-rails-csrf.git"

# Markdown
gem "redcarpet"

# Slugs
gem "friendly_id"

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  # CSS Precompiler
  gem 'sass-rails',   '~> 3.2.3'
  # Sass mixin library
  gem 'compass', '>= 0.12.2'
  gem 'compass-rails', '>= 1.0.3'
  # Minifier
  gem 'uglifier', '>= 1.0.3'
  # Automatically store and retrieve assets from S3 bucket
  gem "asset_sync"
end

# Debugging and Logging
# Supress asset pipeline logging
gem "quiet_assets", ">= 1.0.1", :group => :development
# Better Errors
gem 'better_errors', :group => :development
gem 'binding_of_caller', :group => :development
# Rails Panel (Chrome Extension)
gem 'meta_request', :group => :development
