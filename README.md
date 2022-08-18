# Elasticsearch

Simple download binaries from official website and install elasticsearch.

# Role Variables

```bash
  elastic_version: "7.10.1" # download only this version of elastic
  elastic_home: "/opt/elastic/{{ elastic_version }}" # Use for unpackage distro and create ES_HOME variable
```

# Example Playbook

        - hosts: all
          roles:
            - elastic


# License

BSD

# Author Information

Sergey Davydov
