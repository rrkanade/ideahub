source 'https://rubygems.org'

gem 'rails',     :git => 'git://github.com/rails/rails.git', :branch => '3-2-stable'
gem 'journey',   :git => 'git://github.com/rails/journey.git'
gem 'arel',      '3.0.2'

gem 'mysql2'
gem 'bootstrap-sass'
gem 'simple_form'

gem 'feather_cms'
gem 'tweet-button'

group :production do
  gem 'pg'
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   :git => 'git://github.com/rails/sass-rails.git', :branch => '3-2-stable'
  gem 'coffee-rails', :git => 'git://github.com/rails/coffee-rails.git', :branch => '3-2-stable'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', :platform => :ruby

  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails'
gem 'omniauth'
gem 'omniauth-twitter'
gem 'twitter'
gem 'haml'
gem 'haml-rails'
gem 'RedCloth'
group :test do
  gem 'rspec-rails', '>=2.8.0rc1'
  gem 'faker'
  gem 'database_cleaner'
  gem 'shoulda-matchers'
  gem 'factory_girl_rails', '1.4.0'
  gem "cucumber-rails"
  gem 'simplecov', :require => false
  gem "capybara"
  gem "selenium"
  gem "selenium-client"
  gem "selenium-webdriver"
  gem "watir-webdriver", "~> 0.6.1"
end

# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the app server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'ruby-debug19', :require => 'ruby-debug'
gem 'newrelic_rpm'

group :development do
  gem 'heroku'
  gem 'passenger'
  gem 'webrat', '0.7.3'
end
