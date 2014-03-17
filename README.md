This is a Vagrant file and set of Chef recipes for building a basic DerbyJS development environment.
If you're not familiar with Vagrant, read more about it at http://www.vagrantup.com.

To get this to work, you must have VirtualBox (> 4.1.0) and Vagrant (> 1.0) installed. 
I've most recently been testing it with VirtualBox 4.2.10 and Vagrant 1.1.0. Please post an
issue if you're having problems with other versions, and I'll see if I can track it down.

Installers for VirtualBox are available at http://www.virtualbox.org, and installers for
Vagrant are available at http://www.vagrantup.com.

Once you have the pre-requisites installed, you should be able to clone this repository 

    git clone https://github.com/citymont/derbyjs-vagrant.git my_project

and change to your new project directory to start your VM:

    cd my_project
    vagrant up


More info about these Chef recipes :

https://github.com/semmypurewal/node-dev-bootstrap

