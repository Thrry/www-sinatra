source "https://rubygems.org"
ruby '2.1.2'

gem 'sinatra'
gem 'sinatra-asset-pipeline'
gem 'sinatra-contrib'

gem 'bootstrap-sass', '~> 3.2.0'

gem 'redcarpet'

# Serve fonts to other domains (Wufoo)
gem 'rack-cors', :require => 'rack/cors'

group :development do
  gem 'sinatra-reloader', require: true
  gem 'better_errors'
  gem 'binding_of_caller'
end

group :production do
  gem 'puma'
  gem 'rails_12factor'
end
