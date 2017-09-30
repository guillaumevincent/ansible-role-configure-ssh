Configure ssh
=============

 * set ssh port
 * disallow password authentication
 * disallow root SSH access
 * disallow root SSH access

Role Variables
--------------

 * ssh_port (default: 22)

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: guillaumevincent.configure-ssh, ssh_port: 22 }

License
-------

MIT
