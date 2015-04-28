== Installer for ansible-pull hosts ==

Install ansible pull on hosts pointed by the group named: pull_mode_hosts.
To add these hosts simply edit /etc/ansible/hosts and add the following section:

```
[pull_mode_hosts]
192.168.1.12
```

Then to run the installation on these hosts, run ansible-playbook on your ansible master:
```
ansible-playbook ansible_pull.yml 
```

