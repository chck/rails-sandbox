source 'https://rubygems.org'
ruby '2.0.0'

gem 'rails', '4.0.5'

group :development, :test do
  gem 'sqlite3'
  gem 'rspec-rails', '2.13.1'
  gem 'pry-rails'
  gem 'pry-doc'
  gem 'pry-stack_explorer'

  if RUBY_VERSION >= '2.0.0'
    gem 'pry-byebug'
  else
    gem 'pry-debugger'
    gem 'pry-remote'
  end

  gem 'better_errors'
  gem 'binding_of_caller'

  gem 'hirb'
  gem 'hirb-unicode'

  gem 'tapp'
  gem 'awesome_print'
  gem 'quiet_assets'
  gem 'annotate', git: 'git://github.com/ctran/annotate_models.git'
  gem 'timecop'
  gem 'guard-rspec'
  gem 'factory_girl_rails'
  gem 'database_rewinder'
end

group :test do
  gem 'selenium-webdriver', '2.35.1'
  gem 'capybara', '2.1.0'
end

gem 'sass-rails', '4.0.5'
gem 'uglifier', '2.1.1'
gem 'coffee-rails', '4.0.1'
gem 'jquery-rails', '3.0.4'
gem 'turbolinks', '1.1.1'
gem 'jbuilder', '1.0.2'

group :doc do
  gem 'sdoc', '0.3.20', require: false
end

group :production do
  gem 'pg', '0.15.1'
  gem 'rails_12factor', '0.0.2'
end
