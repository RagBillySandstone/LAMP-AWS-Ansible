Provisioning AWS with Ansible
-----------------------------
##Examples on how to use Ansible to be the boss of your AWS environment
###Work in progress, so don't use it for real.

Each project needs a `./PROJECT_NAME/group_vars/creds` file of the format:
```yaml
---
ec2_access_key: PUT_YOUR_ACCESS_KEY_HERE
ec2_secret_key: PUT_YOUR_SECRET_KEY_HERE
```
