Zucchini Universe Docker Role
=========

Zucchini Universe - Docker

Role Variables
--------------

All variables are set in defaults/main.yml:

docker_users:

Dependencies
------------

None.

Example Playbook
----------------

This role should be used for all Zucchini Universe systems that cannot use podman:

    - hosts: all
      roles:
        ...
         - zucchini-docker
        ...

Author Information
------------------

(c) Zucchini Universe: [www.zucchiniuniverse.org](https://www.zucchiniuniverse.org)