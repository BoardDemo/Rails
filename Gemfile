source 'https://rubygems.org'

gem 'rails'
gem 'httparty'
gem 'uri_signer', :git => 'https://github.com/kissmetrics/uri_signer.git', :branch => 'nk/ruby-2.0'
gem 'unicorn'
gem 'virtus', '~> 0.5'
gem 'omniauth'
gem "omniauth-google-oauth2"
gem 'kmts', '~> 2.0.1'
gem 'maxminddb', '~> 0.1'
gem 'dotenv-rails'

gem 'jquery-rails'

gem 'bourbon'
gem 'kissable', :git => 'https://github.com/kissmetrics/kissable', :ref => '5dfa50e'

# No Persistence

# Monitoring
gem 'newrelic_rpm'
gem 'rdiscount'
gem 'yui-compressor'
gem 'sentry-raven'

# Logging
gem 'lograge', '~> 0.3'

# Gems used only for assets and not required
# in production environments by default.

# Use SCSS for stylesheets
gem 'sass-rails'

# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'

gem 'therubyracer', :platforms => :ruby
gem 'sitemap_generator'

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end

group :development, :test do
  gem 'yard'
  gem 'rspec'
  gem 'rspec-rails'
  gem 'factory_girl'
  gem 'factory_girl_rails'
  gem 'database_cleaner'
  gem "codeclimate-test-reporter", require: nil
end
