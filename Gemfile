source 'https://rubygems.org'
ruby '2.1.2'
gem 'rails', '4.1.1'

# Use SCSS for stylesheets
gem 'sass-rails', '~> 4.0.0'

# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'

# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '~> 4.0.0'

# Prefer Node as a JavaScript runtime.
#
# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails', '~> 3.1.1'

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks', '~> 2.3.0'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 1.2'

# Use Puma as the webserver
gem 'puma', '~> 2.8.1'

group :development, :test do
  gem 'sqlite3', '~> 1.3.9'

  gem 'rspec-rails', '~> 2.14.2'
  gem 'factory_girl_rails', '~> 4.4.1'
  gem 'faker', '~> 1.3.0'
  gem 'database_cleaner', '~> 1.2.0'
  gem 'annotate', '~> 2.6.3'
  gem 'spring', '~> 1.1.3'
end

group :production do
  gem 'pg', '~> 0.17.1'

  # Required for Heroku asset serving & logging
  gem 'rails_12factor', '~> 0.0.2'

  # Heroku-level performance monitoring
  gem 'librato-rails', '~> 0.11.0'
end
