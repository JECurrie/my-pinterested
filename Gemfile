source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem 'rails', '~> 5.1.7'
gem 'puma', '~> 4.3'
gem 'sassc-rails', '>= 2.1.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'

gem 'bootstrap-sass', '~> 3.3.1.0' #'~> 3.4', '>= 3.4.1'
gem 'jquery-rails'

group :development, :test do
  gem 'sqlite3',     '1.3.13' #9'
end
group :production do
  gem 'pg',             '~>0.21.0' #'0.17.1'
  gem 'rails_12factor', '0.0.2'
end
group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver'
end
group :development do
  gem 'web-console', '>= 3.3.0'
end
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
