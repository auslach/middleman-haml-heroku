# If you have OpenSSL installed, we recommend updating
# the following line to use "https"
source 'http://rubygems.org'

ruby '2.1.2'

gem "middleman", "~>3.3.6"

gem 'haml'
gem 'sass'
gem 'coffee-script'

gem 'compass'

# Live-reloading plugin
gem "middleman-livereload", "~> 3.1.0"


# For faster file watcher updates on Windows:
#gem "wdm", "~> 0.1.0", :platforms => [:mswin, :mingw]

# Windows does not come with time zone data
#gem "tzinfo-data", platforms: [:mswin, :mingw]

group :production do
  # Heroku server
  gem 'puma'
  gem 'rack'
  gem 'rack-contrib'
end
