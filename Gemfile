source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


gem 'rails', '~> 5.0.3'
gem 'puma', '~> 3.0'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'

gem 'jquery-rails'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'
gem 'pygments.rb', '~> 1.1', '>= 1.1.2'
gem 'redcarpet', '~> 3.4'

group :development, :test do
  gem 'byebug', platform: :mri
end

group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '~> 3.0.5'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'sqlite3'
end

group :production do
  gem 'pg'
  gem 'rails_12factor'
end

gem 'devise', '~> 4.3'
gem 'mail_form', '~> 1.6'
gem 'will_paginate', '~> 3.1', '>= 3.1.6'
gem 'friendly_id', '~> 5.2', '>= 5.2.1'
gem 'nokogiri', '~> 1.7', '>= 1.7.2'
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
