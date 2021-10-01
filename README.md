# hello-ansible

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
