source 'https://rubygems.org'
ruby '2.0.0'

# Default Rails gems
gem 'rails', '4.0.0'
gem 'sass-rails', '~> 4.0.0' # Use SCSS for stylesheets
gem 'uglifier', '>= 1.3.0' # Use Uglifier as compressor for JavaScript assets
gem 'coffee-rails', '~> 4.0.0' # Use CoffeeScript for .js.coffee assets and views
gem 'jquery-rails' # Use jquery as the JavaScript library
gem 'turbolinks' # Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'jbuilder', '~> 1.2' # Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder

# Non-default gems
gem 'bootstrap-sass', '~> 3.0.2.0' # Twitter Bootstrap front-end framework
gem 'bcrypt-ruby', '~> 3.0.0' # Encryption for user passwords
gem 'local_time' # Manage time
gem 'faye' # Chat framework
gem 'private_pub' # Extends chat framework
gem 'thin' # Web server (Faye dependent) (Hosts chat framework)
gem 'jquery-datatables-rails' # Quickly sort table data
gem 'rails_autolink' #Automatically hyperlink http:// text

group :production do
  gem 'pg' # Heroku database
  gem 'rails_12factor' # Heroku support
end

group :development do
  gem 'quiet_assets' # Turns off the Rails asset pipeline log
  gem "bullet", "~> 4.7.1" # Helps increase performance by alerting dev to reduce the number of queries app makes
end

group :development, :test do
  gem 'sqlite3' # Development database
  gem 'rspec-rails' # Run rake tests in development
  gem 'therubyracer' # Javascript runtime for development
end

group :test do
  gem 'selenium-webdriver', '2.0.0'
  gem 'capybara', '2.1.0'
  gem 'libnotify', '0.8.1'
  gem 'factory_girl_rails', '4.2.1'
end

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end
