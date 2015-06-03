correcthorse.ssl
=========

An ansible role for installing SSL certificates. Make sure you use ansible-vault to encrypt any variable files with private keys!

Role Variables
--------------

    ssl_certificates:
      localhost.localdomain
        private_key:
        certificate:
        chain:

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: correcthorse.ssl }

License
-------

MIT

Author Information
------------------


* [Joshua Rusch](https://correct.horse/)
