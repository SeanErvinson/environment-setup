# Environment setup

## Usage

- Once successfully transferred, execute `playbook` playbook

```shell
ansible-playbook -i inventories/local/hosts.yml -K playbook-dev-machine.yml

# -K ask for sudo password to run as sudo
```

Inventory - is the target machine/s
Playbook - is the orchestrator of the different roles
Role/s - is the repeatable group of tasks
