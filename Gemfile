source 'https://rubygems.org'
ruby '2.0.0'

gem 'rails', '4.1.4'
gem 'pg'
gem 'heroku'

group :development, :test do 
	gem 'rspec-rails'
	gem 'guard-rspec'
	gem 'spring-commands-rspec'
	gem 'rb-fsevent' if 'uname' =~ /Darwin/
end

group :test do 
	gem 'selenium-webdriver'
	gem 'capybara'
end

gem 'sass-rails', '~> 4.0.3'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.0.0'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 2.0'

group :doc do 
	gem 'sdoc', '~> 0.4.0', require: false
end

group :production do
	gem 'rails_12factor'
end

gem 'spring', group: :development


