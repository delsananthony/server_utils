
# Commands

### Create a iniventory.ini
```ansible

touch inventory.ini
```

### Put the script below inside the inventory.ini
```ansible

inventory.ini

[webservers]
ip_address
```

```ansible

ansible-playbook check_service.yml --limit replica
```

```ansible

ansible-playbook module_up.yml --limit replica -K
```