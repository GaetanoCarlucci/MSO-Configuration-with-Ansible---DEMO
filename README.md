# MSO ANSIBLE DEMO

## RUN THE PLAYBOOK

First deploy tenant 2:
```
ansible-playbook -i inventory_paris_tenant_2.yml.yml site.yml 
```
Then deploy tenant 1:
```
ansible-playbook -i inventory_paris_tenant_1.yml.yml site.yml 
```
