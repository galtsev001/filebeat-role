filebeat role
=========

Роль для установки filebeat

Requirements
------------

Поддреживаются ОС Linux семейств Centos.

Role Variables
--------------

| Variable name         | Default  | Description  
|-----------------------|----------|-------------------------  
| filebeat_version      | "7.14.0" | Параметр, определяющий устанавливаемую версию filebeat  
| filebeat_install_type | "remote" | Параметр, определяющий способ получения дистрибутива - удаленно или из локального файла. Возможные значения: "remote", "local"  


Example Playbook
----------------

Example Playbook
----------------

	- hosts: all
	  roles:
		 - { role: filebeat-role }

License
-------

MIT
