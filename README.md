Elasticsearch Exporter
=========

[Elasticsearch exporter source](https://github.com/justwatchcom/elasticsearch_exporter)

Install Role
----------------

Add to requirements.yml

```
- name: elasticsearch-exporter
  src: https://github.com/oleksandr-mazur/ansible-role-elasticsearch-exporter
  version: master
```

```bash
$ ansible-galaxy install -r requirements.yml
```

Example Playbook
----------------

```yaml
- name: Setup exporter
  hosts: my_hosts
  gather_facts: no
  roles:
    - role: elasticsearch-exporter
      version: "1.3.0"
```

License
-------

BSD


