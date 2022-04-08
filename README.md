ic_it.deploy_secondary_dns
=========

This role takes care of deploying the secondary DNS server for ic-cluster.

Requirements
------------

Docker needs to be installed on the host.

Role Variables
--------------

| variable | description | default |
| -------- | ----------- | ------- |
| bind_path | the path where the docker compose definition should be deployed | /srv/bind |

Example Playbook
----------------

```yml
    - hosts: servers
      roles:
         - ic_it.deploy_secondary_dns
```

License
-------

BSD

Author Information
------------------

Emmanuel Jaep [EPFL Profile](https://people.epfl.ch/emmanuel.jaep)
