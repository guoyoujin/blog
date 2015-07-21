source 'https://ruby.taobao.org'
ruby '2.2.2'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.1.5'
# Use mysql as the database for Active Record
gem 'mysql2'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 4.0.3'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '~> 4.0.0'
# See https://github.com/sstephenson/execjs#readme for more supported runtimes
#gem 'therubyracer',  platforms: :ruby
#Use kaminari page
gem 'kaminari'
#Use settingslogic
gem 'settingslogic'
# Use jquery as the JavaScript library
gem 'jquery-rails'
# Use haml template
gem 'haml-rails'
# Use bootstrap css
gem 'bootstrap-sass'
gem 'font-awesome-sass-rails', '~> 3.0.2.2'
gem 'twitter-bootstrap-rails-confirm', github: 'guoyoujin/twitter-bootstrap-rails-confirm', branch: 'bootstrap3'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0',          group: :doc

# Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
gem 'spring',        group: :development

# Use ActiveModel has_secure_password
gem 'bcrypt', '~> 3.1.7'

# Use unicorn as the app server
#gem 'unicorn'
# 定时任务
gem 'whenever', '0.9.0', :require => false
# group :development do
#   gem 'thin'
# end

#Avatar
gem 'gravatar_image_tag'

#markdown
gem 'markdown-toolbar', git: 'git@github.com:guoyoujin/markdown-toolbar.git'
gem 'redcarpet'

#file upload
gem 'simple_fileupload'
gem 'remotipart'

#share article
gem 'social-share-button'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]
gem 'grape'

gem "puma"
group :development, :test do
  gem 'thin', '1.6.3'
  gem 'rspec-rails'
  gem 'factory_girl_rails'
  gem 'capistrano', '~> 3.2.1'
  gem 'capistrano-rails'
  gem 'capistrano-rvm'
  gem 'capistrano-bundler'
  gem 'capistrano-sidekiq'
  gem 'grape-rails-routes'
  gem 'capistrano3-puma'
end