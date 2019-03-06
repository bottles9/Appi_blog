source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

ruby '2.3.3'

gem 'rails', '~> 5.1.3'

gem 'puma', '~> 3.7'
 gem 'execjs' 
gem 'sass-rails', '~> 5.0'
gem 'bootstrap-sass'
gem 'jquery-rails'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'
gem 'redcarpet', '~> 3.4'
gem 'pygments.rb', '~> 1.2', '>= 1.2.1'
gem 'coderay', '~> 1.1', '>= 1.1.2'
gem 'friendly_id', '~> 5.2', '>= 5.2.5'
gem 'will_paginate', '~> 3.1', '>= 3.1.6'
gem 'mail_form', '~> 1.7', '>= 1.7.1'
gem 'sendgrid-ruby'

group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'capybara', '~> 2.13'
  gem 'selenium-webdriver'
end

group :development do
  gem 'web-console', '>= 3.3.0'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

group :development do
	gem 'sqlite3', '~> 1.3.6'
end

group :production do
	gem 'pg'
	gem 'rails_12factor'
end