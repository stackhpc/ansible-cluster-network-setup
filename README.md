# ansible-cluster-network-setup

The purpose of this Ansible role is to configure BDN and IB interfaces
to a Kubernetes or Docker swarm cluster already provisioned by Magnum.

Usage:

```
ansible-playbook cluster-network-setup.yml -e cluster_name=vis-swarm
```
