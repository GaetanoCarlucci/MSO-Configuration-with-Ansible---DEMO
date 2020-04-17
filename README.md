# MSO ANSIBLE DEMO

## RUN THE PLAYBOOK
Edit the credentials in the invertory file:
```
fabric01:
  hosts:
    mso:
      mso_host: X.X.X.X
      mso_user: admin
      mso_port: 443
      mso_password: PASSWORD
```
More than one host can be used.


First deploy tenant 2:
```
ansible-playbook -i inventory_tenant_2.yml.yml site.yml 
```
Then deploy tenant 1:
```
ansible-playbook -i inventory_tenant_1.yml.yml site.yml 
```
