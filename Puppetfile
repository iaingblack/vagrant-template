#!/usr/bin/ruby env

require "socket"
$hostname = Socket.gethostname

forge 'http://forge.puppetlabs.com'


mod 'puppetlabs/stdlib'
mod 'puppetlabs/apt'
mod 'stahnma/epel'
#mod 'garethr/docker'
mod 'garethr/docker', :git => "https://github.com/garethr/garethr-docker.git"
#mod 'stankevich/python'