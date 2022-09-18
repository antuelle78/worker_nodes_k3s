Role Name
=========

**worker_nodes_k3s**

Add any number of worker nodes an existing k3s cluster

Requirements
------------

Ubuntu 18.04 - 22.04

Role Variables
--------------

**k3s_version**:
**k3s_master_url**:
**k3s_master_token**:

Examples
----------------

1. Using ansible-playbook

```
ansible-playbook -i YourInventoryFile add_worker_nodes_k3s.yml

```

2. Using ansible navigator with my custom built EE

```
ansible-navigator run add_worker_nodes_k3s.yml -i YourInventoryFile

```

License
-------

GPLv3

Author Information
------------------

Name: Michael Nelson

LET'S GET IT AUTOMATED AND BE LAZY :<)
