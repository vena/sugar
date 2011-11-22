source 'http://rubygems.org'
source 'http://gems.github.com'

gem 'rails', '3.1.0'

# gem 'sqlite3-ruby', :require => 'sqlite3'
gem 'mysql2'

# Asset template engines
gem 'json'
gem 'sass-rails'
gem 'coffee-script'
gem 'uglifier'
gem 'dynamic_form'

gem 'jquery-rails'

# Use unicorn as the web server
# gem 'unicorn'

# Deploy with Capistrano
gem 'capistrano'

# To use debugger
# gem 'ruby-debug'

# OpenID gem. The stock gem is incompatible with Ruby 1.9, this fixes that.
gem 'ruby-openid', :git => 'git://github.com/xxx/ruby-openid.git', :require => 'openid'

gem 'hpricot', '0.8.4'
gem 'daemon-spawn', '0.2.0'
gem 'newrelic_rpm'

gem 'delayed_job', '2.1.4'
gem 'thinking-sphinx', '2.0.7'
gem 'ts-delayed-delta', '1.1.2', :require => 'thinking_sphinx/deltas/delayed_delta'

group :development do
  gem 'yui-compressor', :require => 'yui/compressor'
	gem 'guard'
	gem 'guard-test'
	gem 'guard-rspec'
	gem 'rb-fsevent'
	gem 'growl_notify', '~> 0.0.3'
	gem 'ruby-prof'
end

group :test, :development do
	gem 'rspec-rails'
	gem 'shoulda-matchers'
	gem 'shoulda-context' # TODO: remove
	gem 'factory_girl_rails'
	gem 'capybara'
end