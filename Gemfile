source 'https://rubygems.org'
 

 
 # Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
 gem 'rails', '~> 5.1.2'
 
 # #1
 group :production do
   # Use pg as the production database for Active Record
   gem 'pg'
   gem 'rails_12factor'
 end
 
 # #2
 group :development do
   # Use sqlite3 as the development database for Active Record
   gem 'sqlite3'
   gem 'pry-rails'
 end
 
 # Use Puma as the app server
 gem 'puma', '~> 3.0'
 # Use SCSS for stylesheets
 gem 'sass-rails', '~> 5.0'
 # Use Uglifier as compressor for JavaScript assets
 gem 'uglifier', '>= 1.3.0'
 
 # Use jquery as the JavaScript library
 gem 'jquery-rails'
 # Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
 gem 'turbolinks', '~> 5'
 # Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
 gem 'jbuilder', '~> 2.5'
 
 gem 'thor', '0.19.1'

 gem 'tzinfo-data'
 
 group :development do
   gem 'listen', '~> 3.0.5'
 end

 group :development, :test do 
 	gem 'rspec-rails', '~> 3.0'
 	gem 'rails-controller-testing'
  gem 'shoulda'
  gem 'factory_girl_rails'
 end

gem 'bootstrap-sass'

# sending emails
gem 'figaro', '1.0'

# rubocop 
gem 'rubocop', '~> 0.52.1', require: false
# Used for encrypting passwords
gem 'bcrypt'
