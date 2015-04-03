##  Archivos de configuración


```ini
[defaults]
inventory = ./inventory
log_path = ./ansible.log
remote_user = root
ask_pass = True

# private_key_file =
```

Reduce a:

```console
ansible  db -m apt -a "name=redis state=latest"
```
