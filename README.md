Ansible Role Node Exporter for Prometheus
=========

Deployable Prometheus node exporter role for CentOS using the Copr Repo.

Port specified in defaults/main.yml  
```node_exporter_port: 9100```

Systemd managed service  
```systemctl [start|stop|restart] node_exporter```

Example Playbook
----------------
```yaml
    - hosts: all
      gather_facts: true
      roles:
        - node_exporter
```
