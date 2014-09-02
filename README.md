Ansible Role - Elasticsearch Server
===================================

An Elasticsearch server role to install Elasticsearch Server on elao symfony standard vagrant box


Requirements
------------

This role only run on elao symfony standard vagrant box. See https://vagrantcloud.com/elao/symfony-standard-debian


Role Handlers
-------------

    elasticsearch server restart  # Restart Elasticsearch server


Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: elao.elasticsearch-server }


License
-------

MIT


Author Information
------------------

http://www.elao.com/
