#
# This Gemfile is used to bundle jekyll locally when targeting Github Pages.
#
# To run jekyll locally:
#
#     bundle exec jekyll serve

source "https://rubygems.org"
gem "webrick"

gem "jekyll", "~> 3.9.4"
gem "minima"
gem "jekyll-remote-theme"

gem "github-pages", group: :jekyll_plugins

# If you have any plugins, put them here!
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.6"
  gem "jekyll-sitemap"
  gem "jekyll-mentions"
  gem "jekyll-paginate"
  gem "jekyll-redirect-from"
  gem "jekyll-commonmark"
  gem "jekyll-include-cache"
  gem "jemoji"
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.0", :install_if => Gem.win_platform?

# kramdown v2 ships without the gfm parser by default. If you're using
# kramdown v1, comment out this line.
gem "kramdown-parser-gfm"

# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds since newer versions of the gem
# do not have a Java counterpart.
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
