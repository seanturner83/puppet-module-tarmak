source ENV['GEM_SOURCE'] || 'https://rubygems.org'

puppetversion = ENV.key?('PUPPET_VERSION') ? ENV['PUPPET_VERSION'] : ['>= 4.2']
gem 'metadata-json-lint'
gem 'puppet', puppetversion
gem 'puppetlabs_spec_helper', '>= 2.2.0'
gem 'puppet-lint', '>= 1.0.0'
gem 'facter', '>= 1.7.0'
gem 'rspec-puppet'
gem 'aws-sdk', '~> 2'
gem 'net-ssh'
gem 'puppet-blacksmith'
gem 'puppet_readme_generator', '>= 0.2.0'
gem 'rspec-retry'
gem 'semantic_puppet'

# rubocop requires ruby >= 1.9
gem 'rubocop', '>= 0.49.1'

gem 'beaker', :git => 'https://github.com/jetstack-experimental/beaker.git', :branch => 'fix-test-rerun'
gem 'beaker-rspec'
gem 'beaker-puppet_install_helper'
