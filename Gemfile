source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.0.0"

gem "rails", "~> 7.0.4" # Bundle edge Rails instead: gem "rails", github: "rails/rails", branch: "main"
gem "sqlite3", "~> 1.4" # Use sqlite3 as the database for Active Record
gem "puma", "~> 5.0" # Use the Puma web server [https://github.com/puma/puma]
gem 'rack-cors' # Setup CORS
gem 'devise'
gem 'devise-jwt'
gem 'dotenv-rails'
# gem "jbuilder" # Build JSON APIs with ease [https://github.com/rails/jbuilder]
# gem "redis", "~> 4.0" # Use Redis adapter to run Action Cable in production
# gem "kredis" # Use Kredis to get higher-level data types in Redis [https://github.com/rails/kredis]
# gem "bcrypt", "~> 3.1.7" # Use Active Model has_secure_password [https://guides.rubyonrails.org/active_model_basics.html#securepassword]
gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ] # Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "bootsnap", require: false # Reduces boot times through caching; required in config/boot.rb
# gem "image_processing", "~> 1.2" # Use Active Storage variants [https://guides.rubyonrails.org/active_storage_overview.html#transforming-images]
# gem "rack-cors" # Use Rack CORS for handling Cross-Origin Resource Sharing (CORS), making cross-origin AJAX possible

group :development, :test do
  gem "debug", platforms: %i[ mri mingw x64_mingw ] # See https://guides.rubyonrails.org/debugging_rails_applications.html#debugging-with-the-debug-gem
end

group :development do
  # gem "spring" # Speed up commands on slow machines / big apps [https://github.com/rails/spring]
end

