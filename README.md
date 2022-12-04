# Ansible ESXi
Playbooks for the administration of ESXi.

File ansible.cfg:

Contains the configuration where the inventory servers are set.

File servers:

Pool with ESXi servers.

## deploy_portgroup.yml

In this playbook I have defined the tasks to deploy a portgroup with vlan id on the servers of the inventory servers.
Distribuited switch can be parameterized.

Run:

```sh
ansible-playbook deploy_portgroup.yml
```
