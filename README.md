# Ansible Elasticsearch Role

A simple role install Elasticsearch

## Role Variables

```yaml
elasticsearch_version: # Defaults to 1.3.1
elasticsearch_cluster_name: # provide a cluster name, defaults to elasticsearch
elasticsearch_node_name: # provide a node name, defaults to elasticsearch
elasticsearch_network_host: # provide a default host, defaults to 127.0.0.1
elasticsearch_heap_size: 4g
elasticsearch_min_mem: 256m
elasticsearch_max_mem: 8g
elasticsearch_java_opts: "-Xmx4096m -Xms512m"
```

## License

MIT

