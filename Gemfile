source 'https://rubygems.org'
ruby '1.9.2'

gem 'rails', '3.2.13'

group :development, :test do
   gem 'sqlite3', '1.3.5'
   gem 'rspec-rails', '2.9.0'
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '3.2.4'
  gem 'coffee-rails', '3.2.2'
  gem 'uglifier', '1.2.3'
end

# Book called for 2.0.0 but using that gave error as deprecated and to use
# 2.0.1 or later
gem 'jquery-rails', '2.0.1'

# Gem which allows us to sumulate a user's interactions with the sample app
# using a narual English-like sntax
group :test do
	gem 'capybara', '1.1.2'
end

# PostgreSQL gem in production for deployment to Heroku
group :production do
	gem 'pg', '0.12.2'
end
