source 'https://rubygems.org'
ruby '2.1.1'
gem 'rails', '4.1.0'
gem 'sass-rails', '~> 4.0.3'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.0.0'
gem 'jquery-rails'
gem 'jbuilder', '~> 2.0'
gem 'sdoc', '~> 0.4.0',          group: :doc
gem 'spring',        group: :development
gem 'bootstrap-sass'
gem 'simple_form'
gem 'bower-rails'
gem "foreman"
group :development do
  gem 'better_errors'
  gem 'binding_of_caller', :platforms=>[:mri_21]
  gem 'guard-bundler'
  gem 'guard-rails'
  gem 'guard-rspec'
  gem 'quiet_assets'
  gem 'rails_layout'
  gem 'rb-fchange', :require=>false
  gem 'rb-fsevent', :require=>false
  gem 'rb-inotify', :require=>false
  gem 'spring-commands-rspec'
end
group :development, :test do
  gem 'mysql2'
  gem 'factory_girl_rails'
  gem 'faker'
  gem 'rspec-rails'
  gem 'thin'
  gem 'capybara'
  gem 'selenium-webdriver'
  # Put the two below in group :test do end if they cause an issue
  gem 'database_cleaner'
  gem 'launchy'
end
group :production, :staging do
  gem 'rails_stdout_logging'
  gem 'rails_serve_static_assets'
end
group :production do
  gem 'pg'
  gem 'rails_12factor'
  gem 'unicorn'
end