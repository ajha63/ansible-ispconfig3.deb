ansible-ispconfig3.deb
========================
Ansible share role to install a ispconfig3 Debian environment, based on The Perfect Server - Debian Wheezy (nginx, BIND, Dovecot, ISPConfig 3) tutorial  [ISPconfig3](https://www.howtoforge.com/perfect-server-debian-wheezy-nginx-bind-dovecot-ispconfig-3 "The Perfect Server - Debian Wheezy (nginx, BIND, Dovecot, ISPConfig 3)")

Requirements
------------

Debian 7 Wheezy installed

Role Variables
--------------

	# vars file for ispconfig3.deb
	ispconfig3_ip: 
 	 - 192.168.1.1

	ispconfig3_fqdn: 
	  - mydom.example.com

	# packages name
	sshd_packages:
	  - openssh-server

	vim-nox_packages:
	  - vim-nox

	sshd_service: 
	  - ssh

	# config files
	sshd_file_config: 
	  - /etc/ssh/sshd_config

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

[GPLv3](http://www.gnu.org/licenses/gpl-3.0.en.html "GNU General Public License version 3")

Author Information
------------------

About me. Alvaro Jesus Hernandez <hernandez.alvaro@gmail.com> Twitter: @ajha63 
Blog [Cacho y Capote](http://www.alvaro.web.ve "Cacho y Capote")
