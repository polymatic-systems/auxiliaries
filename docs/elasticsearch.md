
### elasticsearch.env

*Not for production use!* Deploys a single node Elasticsearch cluster.

The service is available on review at: 

```
${AUX_SERVICE_RELEASE}-master:9200
```

Supported versions:
- 6
- 7

| Variable     | Required | Default  | Purpose  |
| ------------ | -------- | -------- | -------- |
| USER         | no       | elastic  | Default user name |
| PASSWORD     | no       | password | Default password |
| SIZE         | no       | 40Gi     | The size of the volume to provision |
