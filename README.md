##vagrant-gocd
Installs Go Continuous Integration Server & Agent in Vagrant

###Prerequisites

* Vagrant
  * Download: [http://www.vagrantup.com/downloads.html](http://www.vagrantup.com/downloads.html)
  * Setup: [http://docs.vagrantup.com/v2/installation/index.html](http://docs.vagrantup.com/v2/installation/index.html)
* Virtualization, such as virtualbox. See [http://docs.vagrantup.com/v2/providers/index.html](http://docs.vagrantup.com/v2/providers/index.html)
* Install puppet-librarian-puppet:
    ```  vagrant plugin install puppet-librarian-puppet ```


###Install

    git clone git@github.com:natewarr/vagrant-gocd.git
    cd vagrant-gocd
    vagrant up

Point your browser to [http://localhost:8153](http://localhost:8153) or [https://localhost:8154](https://localhost:8154)
