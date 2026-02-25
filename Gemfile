source "https://rubygems.org"

gem "jekyll"
gem "jekyll-remote-theme"

# Markdown
gem "kramdown-parser-gfm"

# Required by Just the Docs
gem "jekyll-seo-tag"
gem "jekyll-include-cache"

# Required dependency
gem "rake"

# Windows and JRuby does not include zoneinfo fileSs, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end