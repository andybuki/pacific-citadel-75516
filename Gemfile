source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

ruby '2.5.1'

gem 'rails', '~> 5.2.0'

group :development do
   gem 'sqlite3', '~> 1.3.13'
end

group :test, :production do
    gem 'pg'
end

gem 'puma', '~> 3.11.4'
gem 'sass-rails', '~> 5.0.7'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2.2'
gem 'bundler', '~> 1.16.2'
gem 'jquery-rails'
gem 'turbolinks', '~> 5.1.1'
gem 'jbuilder', '~> 2.7.0'

group :development, :test do
  gem 'byebug', platform: :mri
end

group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.1'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

gem 'bootstrap-sass', '~> 3.3.7'
gem 'devise', '~> 4.4.3'

gem 'toastr-rails', '~> 1.0.3'

gem 'omniauth', '~> 1.8.1'
gem 'omniauth-facebook', '~> 5.0.0'

gem 'paperclip', '~> 6.0.0'
gem 'aws-sdk', '~> 3.0.1'

gem 'geocoder', '~> 1.4.9'
gem 'jquery-ui-rails', '~> 6.0.1'

gem 'ransack', '~> 1.8.8'
