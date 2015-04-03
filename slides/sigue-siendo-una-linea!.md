## Sigue siendo una línea


Instalar en todas las máquinas del grupo db.

```console
ansible  db -i inventario -m apt -a "name=redis state=latest" -k -s
```
