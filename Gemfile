source "https://rubygems.org"

ruby '3.3.4'

# Core Jekyll 4
gem "jekyll", "~> 4.3"

group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.17"
  gem "jekyll-sitemap", "~> 1.4"
  gem "jekyll-seo-tag", "~> 2.8"
  gem "jekyll-scholar", "~> 7.1"
  gem "jekyll-paginate", "~> 1.1"      # Added this to fix the error
  gem "jekyll-remote-theme", "~> 0.4"
  gem "jekyll-include-cache", "~> 0.2" # Highly recommended for performance
end

# Keep this for Windows compatibility
gem "wdm", "~> 0.1.0" if Gem.win_platform?