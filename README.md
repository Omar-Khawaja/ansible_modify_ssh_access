This playbook assumes your users are securely logging into servers via SSH keys
and uses a central SSH public key location (in this case, the ansible host) to
push out and remove keys to the nodes you specify.

You can modify the users and location of their public keys on the ansible
host in the vars directory of each role. Doing this will allow you to safely 
and cleanly modify SSH access on the nodes specified in the playbook.
