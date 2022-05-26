Role Name: Gnome
=========

An Ansible role that installs and configures Gnome desktop to my personal tastes.

Requirements
------------

None.

Role Variables
--------------

Available variables are listed below, along with default values (see defaults/main.yml):

```yml
---
# Which GTK theme to use:
gtk_theme: 'Adwaita-dark'

# Which wallpaper to download from a URL and use:
wallpaper_url: https://w.wallhaven.cc/full/z8/wallhaven-z8qvew.png
```

Dependencies
------------

None.

Example Playbook
----------------

```yaml
---
- hosts: localhost
  roles:
  - mictram.gnome
```

License
-------

MIT

Author Information
------------------

This role was created in 2022 by Michael Ramos.
