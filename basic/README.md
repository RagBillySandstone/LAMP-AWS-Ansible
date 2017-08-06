Basic, no VPN setup. Just launch some instances.
------------------------------------------------
Simply edit the `groupvars\all` file as necessary. As the file is now, it will bring up two t2.micro instances running RHEL 7.3 in the us-east-1a availability zone.
Please be aware that the groupvar `ec2_security_group` refers to the SG's **name** not its Group_ID.

Call with `ansible-playbook launch-ec2.yml`

I learned a lot from the code at [dfederlein/ansible-aws] (https://github.com/dfederlein/ansible-aws/tree/master/non-vpc)

