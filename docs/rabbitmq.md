
### rabbitmq.env

*Not for production use!* Deploys a single node Rabbitmq cluster.

The service is available on review at: 

```
${AUX_SERVICE_RELEASE}:5672
```

Supported versions:
- 3

| Variable     | Required | Default  | Purpose  |
| ------------ | -------- | -------- | -------- |
| SIZE         | no       | 40Gi     | The size of the volume to provision |
