##  Así luce un playbook

```yml
---
  - hosts: app

  tasks:
    - name: Instalar apache si no esta instalado.
      apt: name=apache2 state=latest
      sudo: yes

    - name: Activar el servicio si no esta activo.
      service: name=apache2 state=started
      sudo: yes
```
