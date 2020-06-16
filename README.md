Example Playbook

```yaml
- hosts: logstash
  roles:
    - clay_wangzhi.logstash
  vars:
    logstash_elasticsearch_hosts: '["http://172.16.91.27:9200", "http://172.16.91.1:9200", "http://172.16.91.151:9200"]'
    es_user: "elastic"
    es_pass: "****"
```