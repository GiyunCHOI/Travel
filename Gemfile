source "https://rubygems.org"

# Default Jekyll theme
gem "minima", "~> 2.5"

# GitHub Pages support (includes Jekyll and plugins)
group :jekyll_plugins do
  gem "github-pages", "~> 232"
  gem "jekyll-include-cache"
  gem "jekyll-feed", "~> 0.12"
end

# Windows and JRuby do not include zoneinfo files; include tzinfo-data gem
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance booster for watching directories on Windows
gem "wdm", "~> 0.1", platforms: [:mingw, :x64_mingw, :mswin]

# Lock http_parser.rb gem to v0.6.x on JRuby builds
gem "http_parser.rb", "~> 0.6.0", platforms: [:jruby]
