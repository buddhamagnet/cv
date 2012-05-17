### TECHNOLOGIES USED 

```ruby

gem 'rails', '3.0.10'
gem 'sqlite3-ruby', :require => 'sqlite3'
gem 'xml-simple', '1.0.11'
gem 'builder', '2.1.2'
gem 'mime-types', ' 1.16'
gem 'paperclip', '2.3.8'
gem 'panda', "1.3.0"
gem 'aws-s3', '0.5.1', :require => 'aws/s3'
gem 'typus'
gem 'jquery-rails'
gem 'gritter'
gem 'activemerchant', :git => 'git://github.com/Shopify/active_merchant.git'
gem 'date_validator'
gem 'pony'
gem 'kaminari'
gem 'rake', '0.8.7'
gem 'newrelic_rpm'
gem 'friendly_id'
gem 'jbuilder'

group :production do
  gem 'mysql2', '0.2.7'
  gem 'backup'
end

group :development, :test do
  gem 'capybara'
  gem 'database_cleaner'
  gem 'annotate', :git => 'git://github.com/ctran/annotate_models.git'
  gem 'rspec-rails'
  gem 'factory_girl_rails'
  gem 'guard-rspec'
  gem 'guard-livereload'
  gem 'guard-bundler'
  gem 'mocha'
  gem 'spork', '~> 0.9.0.rc'
  gem 'growl'
  gem 'growl_notify'
  gem 'rb-fsevent', :require => false if RUBY_PLATFORM =~ /darwin/i
  gem 'rails-erd'
  gem 'timecop'
end

````



