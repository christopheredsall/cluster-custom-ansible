# brismedphys-ansible
Ansible playbook to customise Cluster in the Cloud 

## Operation

After you have run the ``./finish`` script once the cluster is up in 
https://cluster-in-the-cloud.readthedocs.io/en/latest/ansible.html#final-configuration-step

```
ansible-playbook \
    --become \
    --inventory=/home/opc/hosts \
    cluster-custom-ansible/site.yml
```
