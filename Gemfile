source 'http://ruby.taobao.org'

ruby '1.9.3'
gem 'rails', '3.1.0'

group :development do 
  gem 'sqlite3'
end 

group :assets do
  gem 'sass-rails', "  ~> 3.1.0"
  gem 'coffee-rails', "~> 3.1.0"
  gem 'uglifier'
end

gem 'jquery-rails'
gem "therubyracer"
#gem "less-rails"  i don't wanna to use less so ...
gem "twitter-bootstrap-rails"

# Use unicorn as the web server
# gem 'unicorn'

group :test do
  gem 'turn', :require => false
end

group :production do 
	gem 'pg', '0.15.1'
end 

gem 'devise'


gem 'annotate'
gem 'magic_encoding'

# webserver
gem 'thin'