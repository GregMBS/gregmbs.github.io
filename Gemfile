source "https://rubygems.org"

# Pin to the Jekyll version GitHub Pages uses (matches the jekyll/builder
# Docker image used by .github/workflows/jekyll.yml)
gem "github-pages", "230", group: :jekyll_plugins

# Explicitly require these so Netlify doesn't choke
gem "kramdown-parser-gfm"
gem "webrick" # Required for Ruby 3+, missing from older Jekyll

group :jekyll_plugins do
  gem "jekyll-feed"
  gem "jekyll-seo-tag"
  # Only use GitHub Pages-whitelisted plugins here
end
