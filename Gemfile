source 'https://rubygems.org'

gem 'rubyzip', '>= 1.0.0'
gem 'zip-zip' # Just to avoid 'cannot load such file -- zip/zip' error
gem 'simple_enum'
gem 'uuidtools', '~> 2.1.1'
gem 'dav4rack',  '~> 0.3.0'

group :production do
  gem 'nokogiri'
end

#Allows --without=xapian
group :xapian do
  gem 'xapian-full-alaveteli', :require => false
end
