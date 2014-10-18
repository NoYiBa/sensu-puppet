source 'https://rubygems.org'

source ENV['GEM_SOURCE'] || "https://rubygems.org"

group :development, :test do
  gem 'rake',                    :require => false
  gem 'rspec-puppet',            :require => false
  gem 'puppetlabs_spec_helper',  :require => false
  gem 'serverspec',              :require => false
  gem 'puppet-lint',             :require => false
  gem 'puppet-blacksmith',       :require => false
  gem 'beaker',                  :require => false
  gem 'beaker-rspec', "~> 2.2.4",:require => false
  gem 'pry',                     :require => false
  gem 'simplecov',               :require => false
  gem 'vagrant-wrapper',         :require => false
  gem 'rest-client', "1.6.8",    :require => false
end

if facterversion = ENV['FACTER_GEM_VERSION']
  gem 'facter', facterversion, :require => false
else
  gem 'facter', :require => false
end

if puppetversion = ENV['PUPPET_GEM_VERSION']
  gem 'puppet', puppetversion, :require => false
else
  gem 'puppet', :require => false
end

# vim:ft=ruby
