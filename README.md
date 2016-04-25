# centos6.7-apache-php55-git
A Vagrant Box that can be used to quickly create an environment to develop on it. 

By default I install
* apache 2.2+
* Mysql Percona 5.6+
* php 5.5+
* Gnome 2 GUI

How to start:
1. start the box with vagrant up: all the provisions should take a while to load.
2. After all the provision is done reload the box to apply the latest changes: $vagrant reload
3. After reload login in the console and start the gui: $ startx
4. In the interface open the browser Firefox and go to this url: http://magento.dev.loc
5. A success message should be displayed and tells you how where to clone your magenot repo.

