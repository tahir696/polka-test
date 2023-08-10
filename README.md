# openstack

OpenStack examples using terraform. 

# Usage
Source your openstack rc file
```sh
source admin.rc
```
then edit `variables.tf` with your favorite editor and follow these steps

```sh
terraform init
terraform plan
terraform apply 
```
to check the output:
```sh
terraform output
```

# deploy polkadot binary

update the hosts.ini file with the name of the hosts 
update the group_vars/all.yaml file with the require binary URL and checksum

run the main playbook to execute the deployment and config process

all the roles are tested for Ubuntu 20.04

