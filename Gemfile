source 'http://rubygems.org'

gem 'rails', '5.0.0'
gem 'rake'
gem 'mysql2'
gem 'addressable'
gem 'devise', '>= 1.5.3'
gem 'whenever'
gem 'capistrano'
gem 'active_scaffold', '>= 3.1.18'
gem 'haml'
gem 'jquery-rails', '>= 4.4.0'
gem 'sass-rails', '>= 5.0.5'
gem 'coffee-rails', '>= 4.1.1'

gem 'recaptcha',
  :require => 'recaptcha/rails'

gem 'exception_notification',
  :git => "git@github.com:rails/exception_notification.git",
  :require => 'exception_notifier'

gem 'transitions',
  :require => ["transitions", "active_record/transitions"]

gem 'will_paginate', '~> 3.0.pre2'

# OTP toolbox
gem 'rotp', '~> 1.3.0'

# QR Code generation
gem 'qrencoder'

# IBAN format validations
gem 'iban-tools'

gem 'delayed_job'

# CSS toolbox
gem 'blueprint-rails', '>= 0.2.0'
gem 'bourbon'

# File attachment with database storage support
gem 'paperclip', 
  :git => 'https://github.com/patshaughnessy/paperclip.git'

# Apple push notifications
gem 'apn_on_rails',
  :git => 'https://github.com/natescherer/apn_on_rails.git',
  :branch => 'rails3'

group :test do
  gem 'mocha', :require => false
  gem 'factory_girl_rails', '>= 1.4.0'
end

group :assets do
  gem 'uglifier'
  gem 'execjs'
  gem 'therubyracer'
end
