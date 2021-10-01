# hello-ansible

https://docs.ansible.com/ansible/2.8/modules/list_of_all_modules.html

ping all servers:
```bash
ansible all -m ping -i hosts
```

run a command on all servers:
```bash
ansible all -i hosts -a "cat /etc/os-release"
```

install packages on all servers:
```bash
ansible-playbook apt.yaml -i hosts
```
