source "https://rubygems.org"
ruby "2.0.0"

gem "rack-canonical-host"
gem "sinatra"
gem "slim"
gem "rdiscount"
gem "nokogiri"
gem "builder"
gem "dalli"
gem "rack-cache"

# Rewrites Heroku ENV names so Dalli just works.
gem "memcachier"

group :production do
  gem "unicorn"
  gem "newrelic_rpm"
end
