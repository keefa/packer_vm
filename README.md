Packer configuration for creating Ubuntu 12.04 Vmware machine

A packer template (ubuntu_64.json) with a debconf preconfiguration file to automate the Ubuntu installer (preseed.cfg). Outputs a Vmware VM image in output-vmware-iso with a fully configured Ubuntu 12.04 LTS, ready for you to SSH into and further customize. Useful info from here: http://blog.endpoint.com/2014/03/provisioning-development-environment.html and here http://kappataumu.com/articles/creating-an-Ubuntu-VM-with-packer.html
