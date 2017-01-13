andrewrothstein.dcos-deploy
===========================

Deploys dcos-master, dcos-private-agent and dcos-public-agent to nodes assigned in group vars

Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)

Example Playbook
----------------

    - hosts: servers
      roles:
         - andrewrothstein.dcos-deploy

License
-------

MIT

Author Information
------------------

Andrew Rothstein andrew.rothstein@gmail.com
