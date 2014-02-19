graylog2-vagrant
================

Graylog2 0.20 RC3 Vagrant Box for easy testing

 * git clone --recursive https://github.com/hggh/graylog2-vagrant.git
 * cd graylog2-vagrant
 * vagrant up
 * vagrant provision # because puppet need to run twice, to create GELF Inputs
 * http://localhost:9000/
   * Username: admin
   * Password: yourpassword
 * cronjob runs every minute to push sample data into Graylog2


Graylog2 Stream Dashboard
------------------------------

Access the new Graylog2 Stream Dashboard:

http://127.0.0.1:8080/graylog2-stream-dashboard

Graylog2 Server address: http://127.0.0.1:12900

For more information and limitations of the Dashboard: https://github.com/Graylog2/graylog2-stream-dashboard


Debian Packages
=========================

Please see https://gist.github.com/hggh/7492598 for the Debian packages, if you want to use it without the Vagrant Box.

Contact?
--------------

Jonas Genannt @hggh / jonas@brachium-system.net

IRC:
freenode/#graylog2
