=====================
ansible-role-semodule
=====================

Ansible role to manage SELinux policy modules.

* License: Apache License, Version 2.0
* Documentation: https://ansible-role-semodule.readthedocs.org
* Source: https://git.openstack.org/cgit/openstack/ansible-role-semodule
* Bugs: https://bugs.launchpad.net/ansible-role-semodule

Description
-----------

semodule is the tool used to manage SELinux policy modules, including
installing, upgrading, listing and removing modules.

Requirements
------------

Packages
~~~~~~~~

Package repository index files should be up to date before using this role, we
do not manage them.

Role Variables
--------------

Dependencies
------------

Example Playbook
----------------

.. code-block:: yaml

    - name: Install semodule
      hosts: web
      roles:
        - ansible-role-semodule
