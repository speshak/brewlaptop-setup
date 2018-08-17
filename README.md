Brew Laptop Setup
=================

A collection of Ansible playbooks used to get my brewing laptop setup.

I use [brewtarget](https://github.com/Brewtarget/brewtarget) and BeerSmith
while making homebrew, and run it on an old laptop that I feel safe having next
to fire & water when I've been drinking.  This project defines how that laptop
was set up.  This assumes we're starting with a base install of Ubuntu 18.04.
`openssh-server` will have to be installed manually if this is to be run
remotely.


Running
=======

    ansible-playbook -i hosts setup.yml
