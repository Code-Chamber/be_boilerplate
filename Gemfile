source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.0.0'

gem 'bootsnap', '>= 1.4.2', require: false
gem 'pg', '>= 0.18', '< 2.0'
gem 'puma', '~> 4.1'
gem 'rack-cors', require: 'rack/cors'
gem 'rails', '~> 6.0.3', '>= 6.0.3.2'
gem 'active_model_serializers'
gem 'devise_token_auth'

group :development, :test do
  gem 'coveralls', require: false
  gem 'factory_bot_rails'
  gem 'pry-byebug'
  gem 'pry-rails'
  gem 'shoulda-matchers'
  gem 'rspec-rails'
end

group :development do
  gem 'listen', '~> 3.2'
  gem 'solargraph'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end
