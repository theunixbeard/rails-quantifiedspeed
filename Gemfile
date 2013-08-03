source 'https://rubygems.org'
ruby '2.0.0'

# Default Gems
gem 'rails', '4.0.0'
gem 'sass-rails', '~> 4.0.0' # SASS for Asset Pipeline
gem 'uglifier', '>= 1.3.0' # Javascript compressor
gem 'coffee-rails', '~> 4.0.0' # Use coffeescript
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 1.2'
gem 'bcrypt-ruby', '~> 3.0.0' # Can use ActiveModel has_secure_password

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end

# Non-Default Gems

# Foundation Gems
gem 'compass-rails' # you need this or you get an err
gem 'zurb-foundation', '~> 4.0.0'

gem 'faker'
gem 'will_paginate'
# Trying out foundation... (At least until Bootstrap 3 v.final)
# gem 'bootstrap-sass' # Not using until Bootstrap 3 supported 
# gem 'bootstrap-will_paginate'

group :development, :test do
  gem 'sqlite3'
  gem 'rspec-rails' # Test framework, instead of Test::Unit
  gem 'guard-rspec' # Automatically runs tests, needs gem 'growl' below in test
  # Spork is not quite Rails 4.0 ready yet, wait a bit to incorporate!
  #gem 'spork-rails' # Spork is testing server for fast startup
  #gem 'guard-spork' # Dunno
  #gem 'childprocess' # Dunno
  gem 'debugger'
end

group :test do
  gem 'selenium-webdriver' # Capybara needs it?
  gem 'capybara' # Interact w/ HTML programatically
  gem 'growl' # Notify when files change
  gem 'factory_girl_rails' # Factories for mock objects in testing
end

group :production do
  gem 'pg'
  gem 'rails_12factor' # Needed for Heroku integration
  gem 'unicorn' # Use unicorn instead of Webrick in production
end