Security Policy Configuration
=========

Configure Security Policy for Junos.

Requirements
------------


Role Variables
--------------
security_policy: List of Dictionaries containing Security Policy

security_policy_settings: Dictionary containing settings for Security Policy


Dependencies
------------

N/A

Example Playbook
----------------

    - hosts: all
      roles:
         - { role: junos_security_policy_config }

License
-------

BSD

Author Information
------------------

Marc Colburn Juniper
