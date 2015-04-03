##  Una línea!


Decir "hola mundo"

```console
ansible app -i inventory -a "echo 'Hola mundo'"
```

Activar un servicio
```console
ansible 127.0.0.1 -i 127.0.0.1, -m service -a "name=docker.io state=started"
```
