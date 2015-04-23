# Ansible Role: Pimp My Log

[![Build Status](https://travis-ci.org/geerlingguy/ansible-role-pimpmylog.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-pimpmylog)

Installs [Pimp my Log](http://pimpmylog.com/).

## Requirements

Requires PHP to be installed on the server, and a web server like Apache, Nginx, IIS. You can get Pimp my Log set up pretty quickly with this role in tandem with `geerlingguy.apache` and `geerlingguy.php` available on Ansible Galaxy.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

    TODO.

## Dependencies

None.

## Example Playbook

    - hosts: webservers
      roles:
        - { role: geerlingguy.apache }
        - { role: geerlingguy.php }
        - { role: geerlingguy.phpmyadmin }

## License

MIT / BSD

## Author Information

This role was created in 2015 by [Jeff Geerling](http://jeffgeerling.com/), author of [Ansible for DevOps](http://ansiblefordevops.com/).
