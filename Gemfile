source 'https://rubygems.org'

ruby '2.6.1'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


gem 'rails', '~> 5.2.0'
gem 'slim-rails'
gem 'pg', '~> 0.18'
gem 'puma', '~> 3.7'
gem 'dalli'

gem 'uglifier', '>= 1.3.0'

gem 'sass-rails', '~> 5.0'
gem "webpacker", "~> 3.5"
gem 'good_ui', github: 'goodlogik/good-ui', branch: 'master'
gem 'rack-cors', require: 'rack/cors'

gem 'coffee-rails', '~> 4.2'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'

gem 'heroku-deflater', :group => :production

group :development, :test do
  gem 'rb-readline'
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'dotenv-rails'
end

group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end
