source 'https://rubygems.org'

gem 'rails', '3.2.12'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', :platforms => :ruby

  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails'
gem 'haml-rails'
gem "mechanize", "~> 2.6.0"
gem 'devise'
gem 'omniauth-twitter'
gem 'faraday'

group :production do
  gem 'pg'
  gem 'therubyracer-heroku'
end

group :development, :test do
  gem 'sqlite3'
  gem 'debugger'
end
