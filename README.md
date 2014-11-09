default-d8
=======

Drupal 8 box. 

requirements
------------
* [vagrant](http://downloads.vagrantup.com/) >= 1.2.0 (1.4.x recommended)

Legacy Note: you no longer need any particular vagrant plugins. The box is
already provisioned, so there's no need for a chef run.

Building
---

* Run `vagrant up` to build the environment.
* ssh in with `vagrant ssh`
* Navigate to `/var/www/sites/PROJECT`.

Use
---
1) Set up your hosts file to include default-d8.dev with an ip address of 10.33.36.58
2) Run vagrant up (Vagrant is pointing to a box that is located on an Amazon S3 account.)
3) In you browser go to http://default-d8.dev
4) Follow instructions for setting up the Drupal 8 database
