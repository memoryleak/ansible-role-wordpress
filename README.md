memoryleak.wordpress
====================

A basic role to download and extract Wordpress.

Requirements
------------

None

Role Variables
--------------

```
wordpress_webroot_path: /var/www
wordpress_directory: wordpress
wordpress_install_group: apache
wordpress_install_user: apache
```

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - name: memoryleak.wordpress

License
-------

BSD

Author Information
------------------

Haydar Ciftci <haydar.ciftci@gmail.com>