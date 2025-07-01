source "https://rubygems.org"

gem "jekyll", "~> 4.3.2"

group :development do
  gem "webrick", "~> 1.7"  # Required for Jekyll to run on Ruby 3+
end
