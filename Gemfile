source "https://rubygems.org"

# Jekyll version
gem "jekyll", "~> 3.9.3"
gem "bundler"
gem "webrick"

# GitHub Pages support
gem "github-pages", group: :jekyll_plugins
gem "jekyll-include-cache", group: :jekyll_plugins

# Required plugins
group :jekyll_plugins do
  gem "jekyll-feed"    # Adds RSS feed support
  gem "jekyll-sitemap" # Generates a sitemap.xml
end

# Use Just the Docs theme
gem "just-the-docs"

# Windows and JRuby support
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance booster for watching directories on Windows
gem "wdm", "~> 0.1", platforms: [:mingw, :x64_mingw, :mswin]

# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds
gem "http_parser.rb", "~> 0.6.0", platforms: [:jruby]
