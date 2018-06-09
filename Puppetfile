#!/usr/bin/env ruby
#^syntax detection

forge "https://forgeapi.puppetlabs.com";

mod 'alexandresvieira-confsbase'
mod 'alexandresvieira-memcached'
mod 'alexandresvieira-mysqlserver'

mod 'puppet-webserver',
  :git => 'https://github.com/alexandresvieira/puppet-webserver.git',
  :branch => 'production'

mod 'puppet-balancer',
  :git => 'https://github.com/alexandresvieira/puppet-balancer.git',
  :branch => 'production'
