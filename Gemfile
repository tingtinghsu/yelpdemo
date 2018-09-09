source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

ruby '2.4.2'
# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
# Rails defaults
gem 'rails', '~> 5.1.6'
gem 'sqlite3',             group: :development 
#database for Active Record
gem 'puma', '~> 3.7'       #app server
gem 'sass-rails', '~> 5.0' #stylesheets
gem 'uglifier', '>= 1.3.0' #compressor for JavaScript assets
gem 'coffee-rails', '~> 4.2' #.coffee assets and views
gem 'turbolinks', '~> 5' #navigate your web application faster
gem 'jbuilder', '~> 2.5' #Build JSON APIs

# learning rails
gem 'carrierwave'
gem 'figaro'
gem "fog-aws" 
gem "mini_magick"
gem 'pg',                  group: :production



#group :production do
#  gem 'pg'
#end

#group :development, :test do
#  gem 'sqlite3'  
#end  
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '~> 2.13'
  gem 'selenium-webdriver'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
