WP - VAGRANT - LAMP with KNIFE-SOLO
====================================
This is a default vagrant LAMP stack optimized for WordPress usage setup with
knife solo

Installation:
-------------

Download and install [VirtualBox](http://www.virtualbox.org/)

Download and install [vagrant](http://vagrantup.com/)

Download and install [knife-solo](http://matschaffer.github.io/knife-solo/)

Download a vagrant box (name of the box is supposed to be precise32)

    $ vagrant box add precise32 http://files.vagrantup.com/precise32.box

Clone this repository

Go to the repository folder and launch the box

    $ cd [repo]
    $ vagrant up

What's inside:
--------------

Installed software:

* Apache
* MySQL
* php
* phpMyAdmin
* mc, vim, curl, apt
* Wordpress utils:
    * [WP-Cli](http://wp-cli.org/)


