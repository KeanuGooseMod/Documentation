# Run locally with: bundle exec jekyll serve
source "https://rubygems.org"

# gem "jekyll-rtd-theme"

gem "github-pages", '~> 212', group: :jekyll_plugins
group :jekyll_plugins do
  gem "jekyll-default-layout"
  gem "jekyll-readme-index"
  gem "jekyll-github-metadata"
  gem "jekyll-titles-from-headings"
  gem "jemoji"
  gem "jekyll-avatar"
  gem "jekyll-mentions"
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

