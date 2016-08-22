# Example-Vagrant-1

The Vagrant version used in this example is v1.8.4.

## Installation

* Install [VirtualBox](https://www.virtualbox.org/)

* Install vagrant using the installation instructions in the [Getting Started document](https://www.vagrantup.com/docs/getting-started/)

* Clone this repository and cd into it

* Run ```vagrant up``` in order to set up the box using the ansible provisioner

* You should now have your working 
  * http://192.168.33.11
  
 
## Installed Components

* [Apache2](http://nginx.org)
* [MySQL](http://dev.mysql.com/downloads/mysql/)
* [PHP 5.5](http://www.php.net/)
* [PhpMyAdmin](https://www.phpmyadmin.net/)
* [NodeJS 6](https://nodejs.org)
* [Bower](https://bower.io/)
* [Gulp](http://gulpjs.com/)
* [Git](http://git-scm.com/)
* [Composer](https://getcomposer.org/)
  
  
## How use?

##### Connect with PhpMyAdmin:
  
    * Available on http://192.168.33.11/phpmyadmin
    * User: root Password: root
  
##### Connect with the database:
    
    * MySQL Host: 127.0.0.1
    * Username: root
    * Password: root
    * SSH Host: 192.168.33.11
    * SSH User: vagrant
    * SSH Password: vagrant