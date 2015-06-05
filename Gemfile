source 'https://rubygems.org'

gem 'rails', '4.1.8'

gem 'pg'
gem 'spring',        group: :development

gem 'sass-rails', '~> 4.0.3'
gem 'haml-rails'
gem 'foundation-rails'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.0.0'

gem 'jquery-rails'
gem 'jquery-easing-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 2.0'
gem 'sdoc', '~> 0.4.0',    group: :doc


# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'


gem 'unicorn'
gem 'font-awesome-rails'
gem 'dotenv'
# gem 'newrelic_rpm'


group :production  do
  # Heroku dependency
  gem 'rails_12factor'
end

group :development, :test do

  gem 'better_errors'
  gem 'binding_of_caller'

  gem 'pry'
  gem 'pry-byebug'
  gem 'pry-doc'
  # gem 'debugger'

  gem 'capistrano-rails'
  gem 'rspec-rails', '=2.14'
  gem 'factory_girl_rails'
  gem 'faker'
  gem 'launchy'

  gem 'guard-rspec'
  gem 'guard-livereload'
  gem 'guard-spork'
  gem 'spork', :github => 'sporkrb/spork'
  gem 'spork-rails', :github => 'sporkrb/spork-rails'
  gem 'ruby_gntp'

end

group :test do
  gem 'capybara'
  gem 'selenium-webdriver'
  gem 'database_cleaner'
  gem 'shoulda-matchers'
end
