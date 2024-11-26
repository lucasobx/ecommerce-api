source "https://rubygems.org"

gem "rails", "~> 7.2.2"

# Basic
gem "bootsnap", require: false
gem "pg", "~> 1.1"
gem "puma", ">= 5.0"
gem "tzinfo-data", platforms: %i[ windows jruby ]

# Auth
gem 'devise_token_auth'

group :development, :test do
  gem "debug", platforms: %i[ mri windows ], require: "debug/prelude"

  gem "brakeman", require: false

  gem "rubocop-rails-omakase", require: false
end

