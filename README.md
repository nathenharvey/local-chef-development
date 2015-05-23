# Local Chef Development

Not all Chef workshops happen in places with Internet connectivity.  This reposiotry points to a Vagrant box that can be added to the local workstation and used for some meaningful learning.

1.  Use the included Vagrantfile
2.  vagrant up
3.  disconnect from the Internet
4.  vagrant ssh
5.  verify chef-apply can install the following packages:
  * vim
  * emacs
  * nano
  * cowsay
  * fortune-mod
  * sl
6. move to the apache cookbook included in this repo
7. kitchen test
