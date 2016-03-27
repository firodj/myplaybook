My Ansible Playbook
---

To install ansible and then upgrade ansible using ansible:

```
sudo apt-get install ansible
ansible-playbook -K -i local ansible.yml
```

To install common settings:

```
ansible-playbook -K -i local local.yml
```
