"# development-template" 

## Play

```
sudo apt update
sudo apt install ansible
ansible-playbook --limit="ubuntu" --inventory-file=localhost -v provision/ubuntu.yml --ask-become-pass
```
