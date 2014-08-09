source 'https://rubygems.org'
#ruby '2.0.0'
ruby '2.1.1'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.0.1'
#gem 'bootstrap-sass','2.3.2.0'
gem 'bootstrap-sass' #,'3.1.1.1'
gem 'bcrypt-ruby', '3.1.2'

# Use sqlite3 as the database for Active Record
group :development, :test do
    gem 'sqlite3', '1.3.8'
    gem 'rspec-rails','2.13.1'
    gem 'annotate', '~> 2.4.1.beta'
    # gem 'guard-rspec', '0.5.5'
    gem 'guard-rspec', '2.5.0'
    gem 'spork-rails', '4.0.0'
    gem 'guard-spork', '1.5.0'
    gem 'childprocess', '0.3.9'
    gem 'listen'
    gem 'libnotify' if /linux/ =~ RUBY_PLATFORM
    gem 'growl' if /darwin/ =~ RUBY_PLATFORM
end

group :test do
    gem 'selenium-webdriver', '2.35.1'
    gem 'capybara','2.1.0'
    #gem 'rb-inotify', '0.9.2'
    gem 'factory_girl_rails', '1.4.0'
end

gem 'bootstrap_form', '2.1.1'
gem 'sass-rails', '4.0.1'
gem 'uglifier', '2.1.1'
gem 'coffee-rails', '4.0.1'
gem 'jquery-rails', '3.0.4'
# gem 'jquery-ui-rails', '4.2.1'
gem 'jquery-ui-rails', '~> 5.0'
gem 'turbolinks', '1.1.1'
gem 'jbuilder', '1.0.2'
gem 'appointments', '1.3.3'
gem 'activeadmin', git: 'https://github.com/gregbell/active_admin.git'
#gem 'activeadmin', git: 'https://github.com/bamorim/active_admin.git', branch: '3274-adding-nested-belongs-to'
gem 'devise'
#gem 'jquery-turbolinks'

group :doc do
  gem 'sdoc', '0.3.20', require: false
end

group :production do
    gem 'pg', '0.15.1'
    gem 'rails_12factor', '0.0.2'
end
