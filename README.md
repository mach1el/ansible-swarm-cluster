Role Name
=========

ansible-swarm-cluster. Provision Docker Swarm cluster using Ansible role

Role Variables
--------------

- master_node: [ip of master node]

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    ---
    - name: Initialize Swarm cluster
      become: true
      hosts: "{{ hosts }}"
      roles:
      - 'mach1el.ansible-swarm-cluster'

License
-------

![License](https://img.shields.io/github/license/mach1el/ansible-swarm-cluster?color=purple&style=plastic)