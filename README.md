configure_and_start_salt-minion
=========

Configure and start/enable the salt-minion.service

Requirements
------------

None. OK, salt-minion should be installed....

Role Variables
--------------

`salt_master_ip_or_hostname`: Hostname or IP address of the salt master that this minion should contact

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: johanneskastl.configure_and_start_salt-minion, salt_master_ip_or_hostname: "1.2.3.4" }

License
-------

BSD-3-Clause

Author Information
------------------

I am Johannes Kastl, reachable via kastl@b1-systems.de.
