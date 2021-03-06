source 'https://rubygems.org'

ruby '2.5.1'

gem 'pg'
gem 'rake'
gem 'awesome_print'
gem 'coinbase-exchange', '0.1.1' # later version returns hashes instead of JSON
gem 'sinatra'#, '~> 2.0.2'
gem 'dotenv-rails'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '5.2.0'
# Use Puma as the app server
gem 'puma', '~> 3.0'
gem 'clockwork', require: false
gem 'active_attr'

# needed in prod git pushing Heroku
gem 'brakeman', require: false
gem 'bundler-audit', require: false
gem 'rubocop', require: false

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
# gem 'jbuilder', '~> 2.5'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 3.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Use Rack CORS for handling Cross-Origin Resource Sharing (CORS), making cross-origin AJAX possible
# gem 'rack-cors'

gem 'bootsnap', require: false

group :development, :test do
  gem 'rspec-rails'
  gem 'factory_bot_rails'
  gem 'rails_best_practices', require: false
  gem 'reek', require: false
  gem 'byebug', platform: :mri
end

group :development do
  gem 'web-console'
  gem 'listen', '~> 3.0.5'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :test do
  gem 'json_spec'
  gem 'database_cleaner'
  # IMPORTANT! - Use caution when upgrading webmock
  # As of 12/1/2108 any version past 3.1.1 is making live requests to the exchange API on spec runs. Yikes!!
  gem 'webmock', '3.1.1', require: false
  gem 'shoulda-matchers', require: false
  gem 'fantaskspec'
  gem 'simplecov'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
