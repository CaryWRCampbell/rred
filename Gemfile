source 'https://rubygems.org'
ruby '2.0.0'
#ruby-gemset=railstutorial_rails_4_0

gem 'rails', '4.0.0'
gem 'bootstrap-sass', '2.3.2.0'
gem 'bcrypt-ruby', '3.0.1'
gem 'faker', '1.1.2'
gem 'will_paginate', '3.0.4'
gem 'bootstrap-will_paginate', '0.0.9'

group :development, :test do
  gem 'sqlite3', '1.3.8'
  gem 'rspec-rails', '2.13.1'
  # The following optional lines are part of the advanced setup.
  gem 'guard-rspec', '2.5.0'
  gem 'spork-rails', '4.0.0'
  gem 'guard-spork', '1.5.0'
  gem 'childprocess', '0.3.6'
end

group :test do
  gem 'selenium-webdriver', '2.35.1'
  gem 'capybara', '2.1.0'
  gem 'factory_girl_rails', '4.2.1'
  gem 'cucumber-rails', '1.4.0', :require => false
  gem 'database_cleaner', github: 'bmabey/database_cleaner'

  # Uncomment this line on OS X.
  gem 'growl', '1.0.3'

  # Uncomment these lines on Linux.
  # gem 'libnotify', '0.8.0'

  # Uncomment these lines on Windows.
  # gem 'rb-notifu', '0.0.4'
  # gem 'win32console', '1.3.2'
  # gem 'wdm', '0.1.0'
end

# Fix for sass-rails dependency on railties 4.0.1.rc3 discovered at:
# http://qiita.com/Wmrfreew/items/80b4355868461a5b3e34
# (N.B. It's in Japanese!)
# and for a problem with 'git push heroku master':
# http://stackoverflow.com/questions/11444998/rake-assetsprecompile-aborting-cant-push-to-heroku
gem 'therubyracer' 
gem 'sprockets-rails', :git => 'https://github.com/rails/sprockets-rails.git'
gem 'sass-rails',   '~> 4.0.0', :git => 'https://github.com/rails/sass-rails.git'
gem 'coffee-rails', '~> 4.0.0', :git => 'https://github.com/rails/coffee-rails.git'
gem 'uglifier', '2.1.1'
#gem 'sass-rails', '4.0.0'
#gem 'coffee-rails', '4.0.0'
gem 'jquery-rails', '3.0.4'
gem 'turbolinks', '1.1.1'
gem 'jbuilder', '1.0.2'

group :doc do
  gem 'sdoc', '0.3.20', require: false
end

group :production do
  gem 'pg', '0.15.1'
  gem 'rails_12factor', '0.0.2'
end
