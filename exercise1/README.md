#Links

* [https://docs.vagrantup.com/v2/getting-started/index.html]()
* [http://www.vagrantbox.es/]()

#Instructions

* Adding a box and saving it with specific name 
  ``vagrant box add hashicorp/precise64``

  (Note: You can see more boxes @ [Vagrant Cloud](https://vagrantcloud.com/discover/featured))
  (Note: You can download box from a url too, ``vagrant box add <box-name> <url>``)

* List of boxes
  ``vagrant box list``

* Initializing vagrant locally
  ``vagrant init hashicorp/precise64``

* Settings
  * argument1 folder from host box is mounted on argument2 folder

      ``config.vm.synced_folder "../project", "/var/www"``

* Boot Up!  ``vagrant up``
* In the vagrant -> ``vagrant ssh``
