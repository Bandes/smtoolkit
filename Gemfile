# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.0.2'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails', branch: 'main'
gem 'rails', '~> 6.1.4'
# Use postgresql as the database for Active Record
gem 'pg', '~> 1.1'
# Use Puma as the app server
gem 'puma', '~> 5.0'
# Use SCSS for stylesheets
gem 'sass-rails', '>= 6'
# Transpile app-like JavaScript. Read more: https://github.com/rails/webpacker
gem 'webpacker', '~> 5.0'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.7'
# Use Redis adapter to run Action Cable in production
gem 'redis', '~> 4.0'
# Use Active Model has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Active Storage variant
# gem 'image_processing', '~> 1.2'

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.4.4', require: false

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: %i[mri mingw x64_mingw]
  gem 'factory_bot_rails'
  gem 'rspec_junit_formatter'
  gem 'rspec-rails'
end

group :development do
  gem 'annotate'
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '>= 4.1.0'
  # Display performance information such as SQL time and flame graphs for each request in your browser.
  # Can be configured to work on production as well see: https://github.com/MiniProfiler/rack-mini-profiler/blob/master/README.md
  gem 'listen', '~> 3.3'
  gem 'rack-mini-profiler', '~> 2.0'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
end

group :test do
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '>= 3.26'
  gem 'rails-controller-testing'
  gem 'simplecov', require: false
  # Easy installation and use of web drivers to run system tests with browsers
  gem 'webdrivers'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'caxlsx'
gem 'caxlsx_rails'
gem 'devise', github: 'ghiculescu/devise', branch: 'error-code-422' # https://github.com/heartcombo/devise/pull/5340 not yet merged
gem 'font-awesome-rails'
gem 'friendly_id', '~> 5.4', '>= 5.4.1'
gem 'haml'
gem 'hotwire-rails'
gem 'inline_svg'
gem 'kaminari'
gem 'letter_opener', group: :development
gem 'mail_form'
gem 'name_of_person', '~> 1.1', '>= 1.1.1'
gem 'premailer-rails'
gem 'pundit'
gem 'ransack'
gem 'responders'
gem 'rexml'
gem 'rubocop', require: false
gem 'simple_form'
gem 'simple_form-tailwind'
gem 'trestle'
gem 'trestle-auth'
gem 'trestle-search'
gem 'view_component'
gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]
