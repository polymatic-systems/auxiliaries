
### cockroach.env

*Not for production use!* Deploys a single node CockroachDB cluster.

The service is available on review at: 

```
${AUX_SERVICE_RELEASE}:26257
```

Supported versions:
- 3

| Variable     | Required | Default  | Purpose  |
| ------------ | -------- | -------- | -------- |
| SIZE         | no       | 40Gi     | The size of the volume to provision |
