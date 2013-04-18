source 'https://rubygems.org'
gem 'rails', '3.2.13'

group :development, :test do
  gem 'sqlite3'
  gem "rspec-rails", ">= 2.12.2"
  gem "factory_girl_rails", ">= 4.2.0"
end

group :production do
  gem 'pg'
end

group :development do
  gem "html2haml", ">= 1.0.1"
  
  gem "guard-bundler", ">= 1.0.0"
  gem "guard-cucumber", ">= 1.4.0"
  gem "guard-rails", ">= 0.4.0"
  gem "guard-rspec", ">= 2.5.2"
  
  gem "rb-inotify", ">= 0.9.0", :require => false
  gem "rb-fsevent", ">= 0.9.3", :require => false
  gem "rb-fchange", ">= 0.0.6", :require => false
  
  gem "quiet_assets", ">= 1.0.2"
  gem "better_errors", ">= 0.7.2"
  
  gem "binding_of_caller", ">= 0.7.1", :platforms => [:mri_19, :rbx]
  gem "hub", ">= 1.10.2", :require => nil
end

group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'uglifier', '>= 1.0.3'
  gem "therubyracer", ">= 0.11.3", :platform => :ruby, :require => "v8"
end

gem 'jquery-rails'
gem "unicorn", ">= 4.3.1"
gem "haml-rails", ">= 0.4"

group :test do
  gem "database_cleaner", ">= 1.0.0.RC1"
  gem "email_spec", ">= 1.4.0"
  gem "cucumber-rails", ">= 1.3.1", :group => :test, :require => false
  gem "launchy", ">= 2.2.0"
  gem "capybara", ">= 2.0.3"
end

gem "bootstrap-sass", ">= 2.3.0.0"
gem "hominid", ">= 3.0.5"
gem "devise", ">= 2.2.3"
gem "devise_invitable", ">= 1.1.5"
gem "cancan", ">= 1.6.9"
gem "rolify", ">= 3.2.0"
gem "simple_form", ">= 2.1.0"

gem "figaro", ">= 0.6.3"

gem "libv8", ">= 3.11.8"

