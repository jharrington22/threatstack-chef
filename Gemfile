source 'https://rubygems.org'

gem 'chefspec', '= 5.2.0'
gem 'berkshelf', '= 4.1.1'
gem 'rubocop', '= 0.43.0'
gem 'foodcritic', '= 8.0.0'
gem 'serverspec', '= 2.37.1'
gem 'stove', '= 4.1.1'
gem 'test-kitchen'

if chefversion = ENV['CHEF_VERSION']
  gem 'chef', chefversion
else
  gem 'chef'
end
