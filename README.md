# ansible-personal-config

Ansible configurations for my personal systems.  
I use these in combination with backups and very minimal manual work to create fully configured and uniform systems.

## These will pretty much always get updated and worked on

**However for now the basic setup and laptop roles are considered "pretty much complete"**

### How to use this ansible playbook

1. Edit the hosts file and add your hosts to the corresponding roles. For running on localhost, check the comment in the hosts file. 
2. Set any relevant variables by creating a file for your host in the host_vars folder. If running on localhost simply edit the present localhost file.
3. Run
> sudo ansible-playbook local.yml