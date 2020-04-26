# Environment setup

## Usage
- Execute `transfer_ssh_key` playbook
```
ansible-playbook -K playbooks/transfer_ssh_key -i inventories/staging/hosts.yml --ask-vault-pass
```

- Once successfully transferred, execute `playbook` playbook
```
ansible-playbook -i inventories/staging/hosts.yml -K site.yml --ask-vault-pass
```