source "https://rubygems.org"

ruby "3.1.2"
gem "rails", "~> 7.1.3", ">= 7.1.3.4"
gem "sprockets-rails"
gem "sqlite3", "~> 1.4"
gem "puma", ">= 5.0"
gem "importmap-rails"
gem "turbo-rails"
gem "stimulus-rails"
gem "jbuilder"
gem "tzinfo-data", platforms: %i[ mswin mswin64 mingw x64_mingw jruby ]
gem "bootsnap", require: false

group :development, :test do
  # See https://guides.rubyonrails.org/debugging_rails_applications.html#debugging-with-the-debug-gem
  gem "debug", platforms: %i[ mri mswin mswin64 mingw x64_mingw ]
  gem 'byebug', '~> 11.1', '>= 11.1.3'
end

group :development do
  # Use console on exceptions pages [https://github.com/rails/web-console]
  gem "web-console"
  gem 'listen', '~> 3.9'
  # Add speed badges [https://github.com/MiniProfiler/rack-mini-profiler]
  # gem "rack-mini-profiler"

  # Speed up commands on slow machines / big apps [https://github.com/rails/spring]
  gem "spring"
  gem 'spring-watcher-listen', '~> 2.1'
  gem "error_highlight", ">= 0.4.0", platforms: [:ruby]
end

group :test do
  # Use system testing [https://guides.rubyonrails.org/testing.html#system-testing]
  gem "capybara"
  gem "selenium-webdriver"
  gem 'webdrivers', '~> 5.3', '>= 5.3.1'
  gem 'rails-controller-testing', '~> 1.0', '>= 1.0.5'
  gem 'minitest', '~> 5.24', '>= 5.24.1'
  gem 'minitest-reporters', '~> 1.7', '>= 1.7.1'
  gem 'guard', '~> 2.18', '>= 2.18.1'
  gem 'guard-minitest', '~> 2.4', '>= 2.4.6'
end

group :production do
  gem 'pg', '~> 1.5', '>= 1.5.6'
end
