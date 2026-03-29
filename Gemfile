source "https://rubygems.org"

ruby '3.3.4'

# Core Jekyll 4
gem "jekyll", "~> 4.3"

group :jekyll_plugins do
  # Standard plugins previously provided by github-pages
  gem "jekyll-feed", "~> 0.17"
  gem "jekyll-sitemap", "~> 1.4"
  gem "jekyll-seo-tag", "~> 2.8"
  gem "jekyll-paginate", "~> 1.1"
  gem "jekyll-gist", "~> 1.5"             # Fixed the latest error
  gem "jekyll-remote-theme", "~> 0.4"
  gem "jekyll-include-cache", "~> 0.2"
  gem "jekyll-commonmark-ghpages", "~> 0.5"
  gem "jekyll-relative-links", "~> 0.6"
  gem "jekyll-optional-front-matter", "~> 0.3"
  gem "jekyll-titles-from-headings", "~> 0.5"
  gem "jekyll-default-layout", "~> 0.1"
  gem "jekyll-readme-index", "~> 0.3"
  gem "jekyll-redirect-from", "~> 0.16"

  # Your specific bibliography plugin (Ruby 3.3 compatible)
  gem "jekyll-scholar", "~> 7.1"
end

# Keep this for Windows compatibility
gem "wdm", "~> 0.1.0" if Gem.win_platform?
gem "webrick", "~> 1.8" # Required for Ruby 3.x