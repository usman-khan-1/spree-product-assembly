source "https://rubygems.org"

gemspec

gem 'spree', github: 'spree/spree', :branch => '2-2-stable'

gem 'pry-rails'
gem 'pg'

group :assets do
  gem 'coffee-rails', '~> 4.0.0'
  gem 'sass-rails', '~> 4.0.0'
end

group :test do
  gem 'capybara', '~> 2.1.0'
  gem "codeclimate-test-reporter", require: nil
  gem 'selenium-webdriver', '~> 2.34'
  gem 'spree_wombat', github: 'spree/spree_wombat', branch: '2-2-stable'
end
