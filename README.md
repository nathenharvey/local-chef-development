# Local Chef Development

Not all Chef workshops happen in places with Internet connectivity.  This reposiotry points to a Vagrant box that can be added to the local workstation and used for some meaningful learning.

## Connected to the Internet

1.  Clone this repository
1.  Use the included Vagrantfile
1.  `vagrant up`

You only need to do this one time while connected to the Internet.  This will:

* download the .box file
* start a virtual machine

## Disconnected from the Internet

1.  vagrant ssh
1.  verify chef-apply can install the following packages:
  * vim (`sudo chef-apply -e "package 'vim'"`)
  * emacs
  * nano
  * cowsay
  * fortune-mod
  * sl
1. move to the apache cookbook included in this repo (`cd chef-repo/cookbooks/apache`)
1. `kitchen test`
