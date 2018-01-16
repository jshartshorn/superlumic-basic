# superlumic-config

NOTE: jsh -> run this -> curl -s https://raw.githubusercontent.com/superlumic/superlumic/master/superlumic | bash -s https://github.com/jshartshorn/superlumic-basic.git

* jsh: requires your username on your mac 
* jsh: last param is git repo for clone

This is a basic configuration repository for the Superlumic workstation configuration management toolset based off of Ansible.

This repository is organized into the following roles and sets of configurations to ensure ease of use amongst the varying sets of tools that I use:

* **profile-all** - this is a general set of installs that are generally ubiquitous, regardless of the situation (i.e. I'm always going to install slack, firefox, chrome, etc.)
* **profile-dev** - this is a general set of tools that I use whenever I'm developing software or something similar.
* **profile-dev-aws** - AWS-specific tooling and installs for (generally) infrastructure-specific development on the Amazon Web Services platform.
* **profile-dev-golang** - Golang specific installs for local Golang dev.
* **profile-dev-java** - Java-specific installs for local Java dev.
* **profile-dev-node** - Node(.js)-specific installs for local Node dev.
* **profile-dev-python** - Python-specific installs for local Python dev.
* **profile-dev-ruby** - Ruby-specific installs for local Ruby dev.
