source 'https://rubygems.org'

gemspec :development_group => :test

gem 'cqm-models', '~> 0.8.4'
gem 'mongoid', '~> 5.0.0'

group :development, :test do
  gem 'bundler-audit'
  gem 'rubocop', '~> 0.52.1', require: false
end

group :development do
  gem 'rake'
  gem 'byebug', '~> 6.0.2',  platforms: [:ruby_20, :ruby_21, :ruby_22, :ruby_23]
end

group :test do
  gem 'factory_girl', '~> 4.1.0'
  gem 'tailor', '~> 1.1.2'
  gem 'cane', '~> 2.3.0'
  gem 'codecov'
  gem 'simplecov', :require => false
  gem 'webmock'
  gem 'minitest', '~> 5.3'
  gem 'minitest-reporters'
  gem 'awesome_print', :require => 'ap'
  gem 'simplexml_parser', :git => 'https://github.com/projecttacoma/simplexml_parser.git', :branch => 'master'
  gem 'vcr'
end
