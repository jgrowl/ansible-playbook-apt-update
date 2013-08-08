ansible-playbook-apt-update
===========================

Ansible playbook to keep apt updated!

This is meant to be a very simple play that can be included as a role in other plays. By default it will run update if it
is included but can be overridden globally so you do not have plays that end up updating numerous times. For instance if
you wanted to have one common playbook that gets run on all machines that performs this role but is turned off everywhere
else.
