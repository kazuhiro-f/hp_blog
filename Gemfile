source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

gem 'rails',                   '~> 6.0.3'
gem 'image_processing',        '~> 1.9.3'
gem 'bcrypt',                  '~> 3.1.13'
gem 'will_paginate',           '~> 3.1.8'
gem 'will_paginate-bootstrap4'
gem 'bootstrap',               '~> 5.0.0.alpha1'
gem 'sprockets-rails', require: 'sprockets/railtie'
gem 'jquery-rails'
gem 'font-awesome-rails'
gem 'puma',                    '~> 4.3.4'
gem 'sass-rails',              '~> 5.1.0'
gem 'webpacker',               '~> 4.0.7'
gem 'turbolinks',              '~> 5.2.0'
gem 'jbuilder',                '~> 2.9.1'
gem 'bootsnap',                '~> 1.4.5', require: false
gem 'acts-as-taggable-on',     '~> 7.0'
gem 'rails-i18n'

group :development, :test do
  gem 'sqlite3', '1.4.1'
  gem 'byebug',  '11.0.1', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  gem 'web-console',           '~> 4.0.1'
  gem 'listen',                '~> 3.1.5'
  gem 'spring',                '~> 2.1.0'
  gem 'spring-watcher-listen', '~> 2.0.1'
end

group :test do
  gem 'capybara',                 '~> 3.28.0'
  gem 'selenium-webdriver',       '~> 3.142.4'
  gem 'webdrivers',               '~> 4.1.2'
  gem 'rails-controller-testing', '~> 1.0.4'
  gem 'minitest',                 '~> 5.11.3'
  gem 'minitest-reporters',       '~> 1.3.8'
  gem 'guard',                    '~> 2.16.2'
  gem 'guard-minitest',           '~> 2.4.6'
end

group :production do
  gem 'pg', '~> 1.1.4'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
