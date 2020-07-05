source "https://rubygems.org"

gem "jekyll"

group :jekyll_plugins do
  gem "jekyll-include-cache"
  gem "jekyll-assets", "~> 2"

  # TODO: Can you make this work in GitHub Actions without building the
  # V8 engine (or Rhino) on every pipeline operation? The rubyracer/rhino
  # doesn't seem right, since it's built on every install (or is it?).
  # Maybe chaining Node.js as a layer in front of the build works...

  # gem "jekyll-minifier"
end

group :development do
  gem "rake"
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem.
gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]

# Performance-booster for watching directories on Windows.
gem "wdm", "~> 0.1.0" if Gem.win_platform?

gem "dotenv"
