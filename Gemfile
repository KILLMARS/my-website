source "https://rubygems.org"

ruby "3.2.2"

group :development, :test do
  gem "sqlite3", "~> 1.4"
end

# Use pg in production
group :production do
  gem "pg", "~> 1.2"
end

gem "rails", "~> 7.1.3", ">= 7.1.3.4"
gem "sprockets-rails"
gem "puma", ">= 5.0"
gem "jbuilder"
gem "tzinfo-data", platforms: %i[ windows jruby ]
gem "bootsnap", require: false

group :development, :test do
  gem "debug", platforms: %i[ mri windows ]
end

group :development do
  gem "web-console"
end