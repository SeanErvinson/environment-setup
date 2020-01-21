# Environment setup

## Usage
- Execute `transfer_ssh_key` playbook
```
ansible-playbook -K playbooks/transfer_ssh_key -i hosts.yml
```

- Once successfully transferred, execute `playbook` playbook
```
ansible-playbook -K playbook.yml -i hosts.yml
```