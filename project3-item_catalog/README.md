UDACITY-FULLSTACK-NANODEGREE
PROJECT 3: ITEM CATALOG
Author: Paul Tai

Description:
	This application that provides a list of items within a variety of categories
	as well as provide a user registration and authentication system. 
	Registered users will have the ability to post, edit and delete their own items.

Project files:
	catalog.py
	TODO

Usage steps:
	If not installed, install Vagrant and VirtualBox.
	
	Clone the git repo containing project files.
		git clone https://github.com/Tyrfang/udacity-fullstack.git
	
	Clone the git repo containing vagrant setup and files
		git clone https://github.com/udacity/fullstack-nanodegree-vm.git
	
	Copy the vagrant folder in this directory into the vagrant folder provided by the Udacity course files
		cp -rf ./udacity-fullstack/project3-item_catalog_results/vagrant/ fullstack-nanodegree-vm/
	
	Navigate to the fullstack-nanodegree-vm/vagrant/
		cd fullstack-nanodegree-vm/vagrant
		
	Start up the viritual machine using Vagrant
		vagrant up
	
	Connect to the virtual machine using Vagrant
		vagrant ssh
	
	Navigate to the sync directory, then the catalog directory
		cd /vagrant/catalog
		
	TODO
		