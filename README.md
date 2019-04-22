consul-exporter
=========

Creates a systemd service to run the Prometheus consul-exporter as a Docker container.

Requirements
------------

Docker, docker-py, and  systemd

Role Variables
--------------

See defaults/main.yml

Dependencies
------------

TODO: Add Docker deps

Example Playbook
----------------

    - name: Prometheus consul-exporter
      hosts: monitor
      become: yes
      roles:
        - { role: lmickh.consul-exporter }
      tags:
        - consul-exporter

License
-------

MIT
