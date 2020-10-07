source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/CraftAcademy/api_el_gaucho_nyheter.git" }

ruby "2.5.1"

gem "rails", "~> 6.0.3", ">= 6.0.3.3"
gem "pg", ">= 0.18", "< 2.0"
gem "puma", "~> 4.1"
gem "rack-cors", require: "rack/cors"

gem "bootsnap", ">= 1.4.2", require: false

group :development, :test do
  gem "pry-rails"
  gem "pry-byebug"
  gem "rspec-rails"
  gem "shoulda-matchers"
  gem "factory_bot_rails"
  gem "coveralls", require: false
end

group :development do
  gem "listen", "~> 3.2"
  gem "spring"
  gem "spring-watcher-listen", "~> 2.0.0"
end
