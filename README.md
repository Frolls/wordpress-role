Wordpress-role
=================

Устанавливает wordpress и настраивает его для работы с кластером MySQL

Requirements
------------

Наличие кластера MySQL )

Role Variables
--------------

Смотри `defaults/main.yml`

Dependencies
------------

None

Example Playbook
----------------

```yml
- name: Create wordpress app
  hosts: wordpress
  become: true
  roles:
    - role: wordpress-role
```

License
-------

BSD

Author Information
------------------

Frolls
