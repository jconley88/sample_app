source 'http://rubygems.org'

gem 'rails', '2.1.0'
gem 'rake', '0.8.7'

gem 'hoptoad_notifier', '2.3.12'
gem 'mysql', '2.8.1'
gem 'crypt', :require => 'crypt/blowfish'
gem 'aws-s3', :require => 'aws/s3'
gem 'zip', :require => 'zip/zip'
gem 'activemerchant', '1.4.1', :require => 'active_merchant'
gem 'rubyzip', '0.9.4', :require=> 'zip/zip'
gem 'RedCloth', '4.2.3'
gem 'chronic', '0.3.0'
gem 'fastercsv', '1.5.4'
gem 'tidy_table', '0.0.5'
gem 'will_paginate', '2.3.11'
gem 'haml', '3.0.24'
gem 'validates_timeliness', '~> 2.3'

# This is a dependency of something else, but the newest version requires a newer version of RubyGems, so specify this version.
gem 'hoe', '2.6.2'

group :development do
  # not needed for the app; just makes rails/console better
  # this does nothing unless you edit your .irbrc file to enable it
  # see https://github.com/janlelis/irbtools for instructions
  gem 'irbtools', :git => 'git://github.com/janlelis/irbtools.git', :branch => 'legacy', :require => false
  gem 'capistrano'
end

group :test do
  gem 'cucumber', '0.10.0'
  gem 'cucumber-rails'
  gem 'database_cleaner', '>=0.5.0'
  gem 'webrat', '>=0.7.0'
  gem 'timecop'
  gem 'factory_girl', '1.3.3'
  gem 'faker', '0.9.4'
  gem 'launchy'
  gem 'mocha', '0.9.12'
end

group :staging, :production do
  gem 'mongrel'
  gem 'mongrel_cluster'
end