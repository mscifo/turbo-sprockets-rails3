source "http://rubygems.org"

# Specify your gem's dependencies in sprockets-rails.gemspec
gemspec

gem 'rails', '3.2.8'
gem "jquery-rails"

gem "uglifier", :require => false
gem "mocha", :require => false
gem "minitest", '~> 3.5.0', :platform => :mri_18

unless ENV['CI']
  gem "debugger", :platform => :mri_19
end
