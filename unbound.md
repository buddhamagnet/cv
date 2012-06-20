### TECHNOLOGIES USED 

```ruby

source 'http://rubygems.org'

gem 'rails', '3.0.10'
gem 'sqlite3-ruby', :require => 'sqlite3'
gem 'xml-simple', '1.0.11'
gem 'builder', '2.1.2'
gem 'mime-types', ' 1.16'
gem 'paperclip', '2.3.8'
gem 'will_paginate', '3.0.pre2'
gem 'panda', "1.3.0"
gem 'aws-s3', '0.5.1', :require => 'aws/s3'
gem "aws-ses", "~> 0.4.1", :require => 'aws/ses'
gem 'jquery-rails'
gem 'gritter'
gem 'activemerchant', :git => 'git://github.com/Shopify/active_merchant.git'
gem 'date_validator'
gem 'pony'
gem 'kaminari'
gem 'rake', '0.8.7'
gem 'newrelic_rpm'
gem 'friendly_id', '~> 4.0.0.beta8'
gem 'jbuilder'
gem 'activeadmin'
gem 'fastercsv'
gem 'gibbon'
gem 'daemons', '1.0.10'
gem 'delayed_job_active_record'
gem 'delayed_job_web'

group :production do
# cmd line: bundle --without=production
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

### WORKFLOW

I worked primarily in vim usimg tmux for terminal management. All new features and bug fixes were worked on in git branches which were then tagged and pushed to the staging environment before being merged into the development branch and then master for final deployment. Deployment
was done using capistrano. 

### WORKLOG

The original codebase was almost completely refactored, extra work included:

* Added CSS3 media queries for mobile, ipad and retina display devices
* Added maintenance page system to put site offline during large deployments
* Performed security audit, focus on mass assignment holes
* Implemented initial caching strategy using cache sweepers
* Create JSON feed for [River Cottage team](http://www.peoplefund.it/) 
* Integrated [Activemerchant](https://github.com/Shopify/active_merchant) for card processing
* Upgraded Rails from 3 to 3.0.10 and prepped for 3.1
* Built new admin back end
* Built reporting system
* Optimised queries (counter cache, N+1 queries etc.)
* Added proper Actionmailer implementation replacing custom classes
* Added automatic email notifier using above implementation
* Added code to add failed projects to robots.txt disallow directives
* Added substantial test coverage, bolstering existing Test Unit suite and adding Rspec
* [Audioboo](http://audioboo.fm) integration
* Implemented friendly URLs for books and users
* Added extensive documentation
* Refactored front end using shared partials and presenters
* Integrated [New Relic](https://github.com/newrelic/rpm)
* Implemented HTTPS across the site
* Implemented automated email system triggered by user events (Amazon SES)
* Advised on git branching and merging strategy
* Advised on agile methodologies
* Separated staging and production environments
* Amended deployment process to run migrations and perform necessary rake tasks
* Added sales and transaction reporting interface with CSV download