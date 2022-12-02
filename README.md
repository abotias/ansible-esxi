# Ansible ESXi
Playbooks for the administration of ESXi.

## deploy_portgroup.yml
In this playbook I have defined the tasks to deploy a portgroup with vlan id on the servers of the inventory servers.

```sh
ansible-playbook -i servers playbook.yml
```
