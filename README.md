jnakatsui.cloudwatch
====================

Installs and configures CloudWatch for EC2

cloudwatch_cronjobs are run every 5 minutes by default.

Requirements
------------

None

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: jnakatsui.cloudwatch }

License
-------
The source code is licensed under GPL v3.

Author Information
------------------
Jonathan Nakatsui
