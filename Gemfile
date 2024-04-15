source "https://rubygems.org"

ruby "3.0.2"

gem "rails", "~> 7.1.3"

gem "sprockets-rails"

gem "pg", "~> 1.1"

gem "puma", ">= 5.0"

gem 'importmap-rails', '~> 2.0.1'

gem 'turbo-rails', '>= 0.7.14'

gem "stimulus-rails"

gem "jbuilder"

gem "tzinfo-data", platforms: %i[ mswin mswin64 mingw x64_mingw jruby ]

gem "bootsnap", require: false

gem 'bootstrap', '~> 5.3.0'
gem 'jquery-rails'

gem "sassc-rails" #コメントアウトをなくす
gem 'uglifier'
gem 'coffee-rails'

gem 'bcrypt'


group :development, :test do
  # See https://guides.rubyonrails.org/debugging_rails_applications.html#debugging-with-the-debug-gem
  gem "debug", platforms: %i[ mri mswin mswin64 mingw x64_mingw ]
end

group :development, :test do
  # Use console on exceptions pages [https://github.com/rails/web-console]
  gem "web-console"

  # Add speed badges [https://github.com/MiniProfiler/rack-mini-profiler]
  # gem "rack-mini-profiler"

  # Speed up commands on slow machines / big apps [https://github.com/rails/spring]
  # gem "spring"
  gem 'pry-rails'
  gem 'better_errors'
  gem 'binding_of_caller'
end

group :test do
  # Use system testing [https://guides.rubyonrails.org/testing.html#system-testing]
  gem "capybara"
  gem "selenium-webdriver"
end
