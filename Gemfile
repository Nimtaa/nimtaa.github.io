source "https://rubygems.org"

# Local development / preview only. GitHub Pages builds the live site
# server-side with its own pinned toolchain, so it ignores this file.
gem "jekyll", "~> 4.3"
gem "webrick", "~> 1.8" # required by `jekyll serve` on Ruby 3+

group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.17"
  gem "jekyll-seo-tag", "~> 2.8"
end

# Windows and JRuby only (skipped on Linux/macOS).
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end
