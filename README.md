graylog2-vagrant
================

Graylog2 0.20 RC1-1 Vagrant Box for easy testing

 * git clone --recursive https://github.com/hggh/graylog2-vagrant.git
 * cd graylog2-vagrant
 * vagrant up
 * vagrant provision # because puppet need to run twice, to create GELF Inputs
 * http://localhost:9000/
   * Username: admin
   * Password: yourpassword
 * cronjob runs every minute to push sample data into Graylog2


Debian Packages
=========================

Please see https://gist.github.com/hggh/7492598 for the Debian packages, if you want to use it without the Vagrant Box.

Contact?
--------------

Jonas Genannt @hggh / jonas@brachium-system.net

IRC:
freenode/#graylog2
