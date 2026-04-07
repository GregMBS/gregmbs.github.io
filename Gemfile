source "https://rubygems.org"

# If you want to use GitHub Pages, keep github-pages and remove the jekyll line.
# To upgrade, run `bundle update github-pages`.
# Run locally with: bundle exec jekyll serve
gem "github-pages", group: :jekyll_plugins
gem "rack"
gem "webrick"

group :jekyll_plugins do
  gem "jekyll-feed"
  gem "jekyll-sitemap"
  gem "jekyll-gist"
  gem "jekyll-include-cache"
  gem "jekyll-admin", "0.9.0"
end

# Windows and JRuby do not include zoneinfo files
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", install_if: Gem.win_platform?