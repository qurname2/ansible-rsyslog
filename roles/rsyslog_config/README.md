Simple Role for configuration rsyslog
=========
Configure rsyslog service

Role Variables
--------------
If you want to send log to remote server, please set remote_server: True and define remote_server_ip, remote_port.
For custom configuration look at the rsyslog_defaults variable.

Example Playbook
----------------

    - hosts: all
      become: yes
      gather_facts: true

      roles:
         - rsyslog_config

License
-------

BSD

Author Information
------------------

bakyrskiy@gmail.com
