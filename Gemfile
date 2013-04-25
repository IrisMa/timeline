# source 'https://rubygems.org'
source 'http://ruby.taobao.org'

gem 'rails', '3.2.13'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

gem 'mongoid'
gem 'devise'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', :platforms => :ruby
  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails'

group :development do
  gem 'puma'
  gem 'rb-readline'
  gem 'rails-backbone'
  gem 'twitter-bootstrap-rails'
end

group :development, :test do
  gem "rspec-rails", "~> 2.0"
  gem 'factory_girl_rails'
  gem 'mongoid-rspec'
  gem 'guard-rspec'
  gem 'guard-spork'
end

group :test do
  gem 'capybara', "~> 2.0"
  gem 'database_cleaner'

  case RUBY_PLATFORM
  when /darwin/i
  	gem 'rb-fsevent', :require => false
    gem 'growl'
  when /linux/i
  	gem 'rb-inotify', :require => false
    gem 'libnotify'
  end
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
# gem 'debugger'
