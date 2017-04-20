# A sample Gemfile
source "https://rubygems.org"

gem 'rake'
gem 'activesupport'

gem 'sinatra'
gem 'sinatra-contrib'
gem 'sinatra-activerecord'

gem 'puma'
gem 'tux'

group :development, :test do
  gem 'pry' #stops code from executing. Delete if pushing to Heroku and environment.rb
  gem 'shotgun'#always push changes to Heroku 
  gem 'sqlite3'
end

group :production do
  gem 'pg'
  gem 'rails_12factor'
end