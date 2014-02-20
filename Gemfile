source 'https://rubygems.org'
gem "bower-rails", "~> 0.7"

ruby "2.1.0"
gem 'rails', '~> 4.0'
gem 'pg'

gem 'jbuilder', '~> 1.2'

gem 'bcrypt-ruby', '~> 3.1'
gem "rolify", "~> 3.4"
gem "authority", "~> 2.9"
gem "devise", "~> 3.1"
gem "devise-i18n"
gem "omniauth-openid"

gem 'ranked-model'

gem "paperclip", "~> 3.5"
gem "paperclip-dropbox", "~> 1.1"
gem "rmagick", "~> 2.13"

gem 'uglifier', '>= 1.3'
gem 'sass-rails', '~> 4.0'
gem "haml", "~> 4.0"
gem "haml-rails", "~> 0.5"
gem 'coffee-rails', '~> 4.0'
gem 'turbolinks', "~> 2.2"
gem 'jquery-rails'
gem 'jquery-turbolinks'
gem 'therubyracer', platforms: :ruby, :require => 'v8'
gem "bootstrap-sass", "~> 3.1"
gem "bootstrap_forms", :github=>"gagalago/bootstrap_forms", :branch => "bootstrap3"
# https://github.com/schnawel007/bootstrap3-wysihtml5
# https://github.com/nickl-/bootstrap-wysihtml5

gem 'dotenv-rails'

group :development do
  # gem 'capistrano'
  gem 'travis-lint'
  # Lot of metrics "metric_fu --format html"
  gem "metric_fu"
end

group :development, :test do
  gem 'debugger'
  gem 'coveralls', require: false
  gem "codeclimate-test-reporter", require: false
end

group :test do
  gem 'rspec-rails'

  gem "factory_girl_rails", "~> 4.3"
  gem 'faker'

  gem 'cucumber-rails', '~> 1.4', :require => false
  gem 'launchy'
  gem 'database_cleaner', "~> 1.2"
  gem "capybara"
  gem 'selenium-webdriver'
  gem "capybara-webkit"
end

group :production do
  gem 'rails_12factor'
  gem 'unicorn'
end

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end
gem 'annotate', ">=2.6.0"
