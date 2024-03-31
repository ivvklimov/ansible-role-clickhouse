Clickhouse
=========

This role install Clickhouse on EL

Role Variables
--------------

|vars|description|
|----|-----------|
| clickhouse_version | Version of Clickhouse to install |
|clickhouse_server_listen_host| Clickhouse server listen host |

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: clickhouse }

License
-------

MIT

Author Information
------------------

Netology DevOps student
