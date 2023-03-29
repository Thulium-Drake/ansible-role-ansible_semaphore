## Ansible Semaphore, powered by Ansible
This role provides a means to install Ansile Semaphore on your system.

It requires:

- A reverse proxy setup for SSL
- A database server (PostgreSQL or MySQL), unless using the built-in Bolt DB
- Access to the internet to retrieve packages or a repository that provides the 'semaphore' packages

Check [the defaults file](defaults/main.yml) for all configurable options
