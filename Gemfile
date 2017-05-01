source 'https://rubygems.org'
ruby '~> 2.3.0'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails'
gem 'bcrypt'
gem 'bootstrap-sass'
gem 'sass-rails'
gem 'uglifier'
gem 'coffee-rails'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder'

#for Heroku deployments
gem 'rack-timeout', '0.3.2'
gem 'fog'

#originally in dev/test only
gem 'web-console'

gem 'sdoc', group: :doc

group :development, :test do
  gem 'sqlite3'
  gem 'byebug'
  gem 'spring'
end

group :test do
  gem 'minitest-reporters'
  gem 'mini_backtrace'
  gem 'guard-minitest'
  gem 'guard'
end

group :production do
  gem 'pg'
  gem 'rails_12factor'
  gem 'puma', '2.11.1'
end

