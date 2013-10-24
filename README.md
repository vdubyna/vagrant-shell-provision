Image, based on "VirtualBox" for web projects
==============================================

Installation
------------

1. Install [Ruby](http://www.ruby-lang.org)
2. Install [Vagrant](http://vagrantup.com)
3. Install [VirtualBox](http://virtualbox.org)

Usage
-----

    vagrant up

Package Box
-----------

1. Get the name of the virtual machine in the VirtualBox
2. Package Virtual machine as VBox

    vagrant package --base web-box_default_1382634695 --output centos-6.4-web.box
    vagrant box add centos-6.4-web-box centos-6.4-web.box








