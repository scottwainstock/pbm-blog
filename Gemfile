source 'https://rubygems.org'
ruby '1.9.3'

gem 'rails', '~> 4.0.0'

gem 'puma'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

# Gems used only for assets and not required
# in production environments by default.
gem 'sass-rails'

platforms :ruby do
  gem 'pg'
end

platforms :jruby do
  # The stable version has not yet supported Rails 4
  gem 'activerecord-jdbcsqlite3-adapter', '1.3.0.beta2'
  gem 'trinidad'
  gem 'jruby-openssl'
end

gem 'jquery-rails'
gem 'thin'

gem 'rails_12factor'

# Bundle the extra gems:
gem 'RedCloth', '~> 4.2.9', :require => 'redcloth'
gem 'ruby-openid', :require => 'openid'
gem 'rack-openid', :require => 'rack/openid'
gem 'aaronh-chronic', :require => 'chronic' # Fixes for 1.9.2
gem 'coderay', '~> 1.0.5'
gem 'lesstile', '~> 1.1.0'
gem 'formtastic'
gem 'will_paginate', '~> 3.0.2'
gem 'exception_notification', '~> 2.5.2'
gem 'omniauth'
gem 'omniauth-google-oauth2'
gem 'omniauth-openid'

# Bundle gems for the local environment. Make sure to
# put test-only gems in this group so their generators
# and rake tasks are available in development mode:
group :test do
  gem 'database_cleaner'
  gem 'cucumber-rails',    :require => false
  gem 'cucumber-websteps', :require => false
  gem 'factory_girl'
  gem 'rspec'
  gem 'nokogiri', '~> 1.5.0'
  gem 'webrat'
end

# Uncomment if you want easy profiling in development.
#group :development do
#  gem 'rack-mini-profiler'
#end

group :development, :test do
  gem 'rspec-rails'
end
