##  El módulo `Template`

Obtienes todo el potencial de jinja y sus filtros incluso dentro de los playbooks.

```
---
mysql_root_password: "{{ lookup('env','MYSQL_ROOT_PASSWORD') }}" 
rails_user_password: "{{ lookup('env','RAILS_USER_PASSWORD') }}"
```
