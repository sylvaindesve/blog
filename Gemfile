source "https://rubygems.org"

gem "jekyll", "~> 4.2.0"

group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem 'jekyll-seo-tag'
end

# Spécifique à Windows et JRuby
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Performances
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Serveur pour la prévisualisation
gem "webrick", "~> 1.7"
