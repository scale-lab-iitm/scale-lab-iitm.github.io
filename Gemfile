source "https://rubygems.org"

# jekyll
gem "jekyll", "~> 4.4"
gem "webrick", "~> 1.9"

gem "html-proofer", "~> 5.2"

# standard libraries that newer Rubies (3.4+/4.x) no longer bundle by default
gem "logger"
gem "bigdecimal"
gem "ostruct"

# plugins
group :jekyll_plugins do
  gem "jekyll-spaceship"
  gem "jekyll-sitemap"
  gem "jekyll-redirect-from"
  gem "jekyll-feed"
  # 1.3.2+ no longer depends on posix-spawn, which no longer compiles with GCC 14+
  gem "jekyll-last-modified-at", ">= 1.3.2"
end
