source "https://rubygems.org"

ruby "3.2.2"

gem "rails", "~> 7.1.4"
gem "sprockets-rails"
gem "sqlite3", ">= 1.4"
gem "puma", ">= 5.0"

gem "importmap-rails"
gem "turbo-rails"
gem "stimulus-rails"

gem "jbuilder"

# Authentication
gem "devise"

# Authorization
# gem "pundit"

# gem "redis", ">= 4.0.1"
# gem "kredis"

# gem "bcrypt", "~> 3.1.7"

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: %i[ windows jruby ]

gem "bootsnap", require: false

# Use Active Storage variants [https://guides.rubyonrails.org/active_storage_overview.html#transforming-images]
# gem "image_processing", "~> 1.2"

group :development, :test do
  gem "debug", platforms: %i[ mri windows ]
  gem "rspec-rails"
  gem "factory_bot_rails"
  gem "faker"
  gem "pry-rails"

  # gem "rubocop"
  # gem "rubocop-rails"

  gem "minitest"
end

group :development do
  gem "web-console"
  gem "rack-mini-profiler"
  gem "spring"
end

group :test do
  gem "capybara"
  gem "selenium-webdriver"
end
