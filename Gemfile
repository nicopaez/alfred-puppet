source 'https://rubygems.org'

ruby '2.1.5'

puppetversion = ENV.key?('PUPPET_VERSION') ? "= #{ENV['PUPPET_VERSION']}" : ['>= 3.3']
gem 'puppet', puppetversion, :require => false
gem 'puppetlabs_spec_helper', '>= 0.1.0'
gem 'puppet-lint', '>= 0.3.2'
gem 'facter', '>= 1.7.0'

group :development, :test do
  gem 'beaker-rspec', :require => false
  gem 'pry'
end
