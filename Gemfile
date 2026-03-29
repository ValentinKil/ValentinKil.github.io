source "https://rubygems.org"

ruby '3.3.4'

# We use Jekyll 4 for better performance and compatibility with Scholar 7
gem "jekyll", "~> 4.3"

group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.17"
  gem "jekyll-sitemap", "~> 1.4"
  gem "jekyll-seo-tag", "~> 2.8"
  gem "jekyll-scholar", "~> 7.1"
  gem "jekyll-remote-theme", "~> 0.4" # Needed if you use a remote theme
end

# Keep this for Windows compatibility
gem "wdm", "~> 0.1.0" if Gem.win_platform?