=========================
ansible-role-openstacksdk
=========================

Ansible role to manage OpenStackSDK

* License: Apache License, Version 2.0
* Documentation: https://ansible-role-openstacksdk.readthedocs.org
* Source: https://git.openstack.org/cgit/openstack/ansible-role-openstacksdk
* Bugs: https://bugs.launchpad.net/ansible-role-openstacksdk

Description
-----------

OpenStackSDK is a simple client library for operating OpenStack clouds.

Requirements
------------

* pip3 to be installed if using openstacksdk_install_method: (git|pip)

See `bindep.txt` for role dependencies.

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

    - name: Install openstacksdk
      hosts: nodepool
      roles:
        - ansible-role-openstacksdk
