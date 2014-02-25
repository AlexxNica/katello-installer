forge 'http://forge.puppetlabs.com'

#################################################################
# The Foreman part of Puppetfile (taken from foreman-installer #
#################################################################

# Temporary for Apache 2.4 support (post-0.11.0)
mod 'puppetlabs/apache', :git => 'https://github.com/puppetlabs/puppetlabs-apache'

# Temporary for Amazon Linux support (https://github.com/puppetlabs/puppetlabs-xinetd/issues/32)
mod 'puppetlabs/xinetd', :git => 'https://github.com/puppetlabs/puppetlabs-xinetd'

# Dependencies
mod 'puppetlabs/mysql'
mod 'theforeman/concat_native', :git => 'https://github.com/theforeman/puppet-concat'
mod 'theforeman/dhcp', :git => 'https://github.com/theforeman/puppet-dhcp'
mod 'theforeman/dns', :git => 'https://github.com/theforeman/puppet-dns'
mod 'theforeman/git', :git => 'https://github.com/theforeman/puppet-git'
mod 'theforeman/tftp', :git => 'https://github.com/theforeman/puppet-tftp'

# Top-level modules
mod 'theforeman/foreman', :git => 'https://github.com/theforeman/puppet-foreman'
mod 'theforeman/foreman_proxy', :git => 'https://github.com/theforeman/puppet-foreman_proxy'
mod 'theforeman/puppet', :git => 'https://github.com/theforeman/puppet-puppet'

###########################################################
# Katello part of Puppefile (taken from foreman-installer #
###########################################################

# Katello specific modules
mod 'katello/common', :git => 'https://github.com/Katello/puppet-common'
mod 'katello/candlepin', :git => 'https://github.com/Katello/puppet-candlepin'
mod 'katello/capsule', :git => 'https://github.com/Katello/puppet-capsule'
mod 'katello/certs', :git => 'https://github.com/Katello/puppet-certs'
mod 'katello/elasticsearch', :git => 'https://github.com/Katello/puppet-elasticsearch'
mod 'katello/katello', :git => 'https://github.com/Katello/puppet-katello'
mod 'katello/pulp', :git => 'https://github.com/Katello/puppet-pulp'
mod 'katello/qpid', :git => 'https://github.com/Katello/puppet-qpid'
mod 'katello/service_wait', :git => 'https://github.com/Katello/puppet-service_wait'
mod 'puppetlabs/mongodb', :git => 'https://github.com/puppetlabs/puppetlabs-mongodb'
