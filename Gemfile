# -*- coding: utf-8 -*-
source 'https://rubygems.org'
# ruby '2.1.0'

gem 'rails', '4.0.2'

gem 'pg'
gem 'sass-rails', '~> 4.0.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.0.0'
gem 'jquery-rails'
gem 'turbolinks'
# gem 'jbuilder', '~> 1.2'

group :doc do
  gem 'sdoc', require: false
end

group :production do
  gem 'rails_12factor'
end


gem 'rails-i18n', '~> 4.0.0'


group :development, :test do
  gem 'rspec-rails'
  gem 'factory_girl_rails'
  gem 'database_cleaner'
  gem 'shoulda-matchers'
  gem 'rb-fsevent', :require => false if RUBY_PLATFORM =~ /darwin/i
  gem 'guard-rspec'
#  gem 'guard-coffeescript'
  gem 'capybara', git: 'git://github.com/jnicklas/capybara.git'
#  gem 'pry-rails'
#  gem 'pry-debugger'

  gem 'dotenv-rails'
  gem 'quiet_assets'
end

gem 'omniauth-twitter'
gem 'rails_config'
gem 'minimum-omniauth-scaffold'

gem 'simple_form', github: 'wtfiwtz/simple_form_bootstrap3'
gem 'font-awesome-rails'

gem 'bootstrap-sass', '~> 3.0.3.0'
group :development do
  gem 'rails_layout'
end
