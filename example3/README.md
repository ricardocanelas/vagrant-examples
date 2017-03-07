# Example-Vagrant-3 (xdebug with phpstorm)



## Installation

* Install [VirtualBox](https://www.virtualbox.org/)

* Install vagrant using the installation instructions in the [Getting Started document](https://www.vagrantup.com/docs/getting-started/)

* Clone this repository and cd into it

* Run ```vagrant up``` in order to set up the box using the ansible provisioner

* You should now have your working 
  * http://192.168.100.100
  
 
## Installed Components

* [Apache2](http://nginx.org)
* [MySQL5.6](http://dev.mysql.com/downloads/mysql/)
* [MariaDB](https://mariadb.org/)
* [PHP 7.1](http://www.php.net/)
* [NodeJS 6](https://nodejs.org)
* [Gulp](http://gulpjs.com/)
* [Git](http://git-scm.com/)
* [Composer](https://getcomposer.org/)
* [XDebug](https://xdebug.org/)
  
  
## How use?
  
##### Connect with the database:
    
    * MySQL Host: 127.0.0.1
    * Username: root
    * Password: password
    * SSH Host: 192.168.100.100
    * SSH User: vagrant
    * SSH Password: vagrant
    
      
##### PHPStorm

 
* Preference / Languages & Frameworks / PHP
  * interpreter
    * Add a new interpreter
       * Remote: vagrant 
       * Vagrant instance Folder: [your-path]
    * General 
       * PHP executable: /usr/bin/php
       
* Preference / Languages & Frameworks / PHP / Debug 
  * Debug port: 9000
  
* Preference / Languages & Frameworks / PHP / Debug 
  * Use debugger bookmarklets to initiate debugging from your favorite browser
     * IDE Key: MY_AWESOME_KEY123 
     * add favourites the links: start debug, stop debug..  