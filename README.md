# ansible-cluster-network-setup

The purpose of this Ansible role is to configure BDN and LLN interfaces
on Fedora Atomic 27 cluster nodes already provisioned by Magnum as it currently
only provisions a cluster attached to a single network interface by default.

Usage:

```
ansible-playbook cluster-network-setup.yml 
```
