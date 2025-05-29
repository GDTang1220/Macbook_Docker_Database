# Docker
## Elasticsearch
```sh
bin/elasticsearch-reset-password --batch --user kibana_system
```

Then copy the password to .env KIBANA_SYSTEM_PASSWORD

```sh
bin/elasticsearch-plugin install https://get.infini.cloud/elasticsearch/analysis-ik/9.0.1
```
