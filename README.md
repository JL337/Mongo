# MongoDB Cookbook

## Purpose
The purpose of this cookbook is to set up a MongoDB instance using Chef.

## Requirements

Install these programs:

[Chef DK - 2.4.17](https://downloads.chef.io/chefdk)(2.4.17)

[Virtual Box](https://www.virtualbox.org/wiki/Downloads)(5.2.6)

[Vagrant](https://www.vagrantup.com/downloads.html)

## Useage

Clone down this repository to a directory of your choice, eg. `mongo-cookbook`

Create a VM with chef in the same repository:

		kitchen create
		
Remove the VM

		kitchen destroy
		
Run Tests to check correct `recipes` have been downloaded

		kitchen verify
		
Also:

		kitchen test
		
This does create, converge and verify 



