source 'http://rubygems.org'

gem "rails", "~> 3.1.0"
gem 'sqlite3', '1.3.4'
gem 'jquery-rails'

group :development do
gem 'rspec-rails', '2.6.1'
gem 'annotate', 
    :git => 'git://github.com/jeremyolliver/annotate_models.git', 
    :branch => 'rake_compatibility'
end

group :test do
gem 'rspec-rails', '2.6.1'
gem 'webrat', '0.7.1'
gem 'factory_girl_rails'
end

group :production do
  # gems specifically for Heroku go here
  gem 'pg'
end
