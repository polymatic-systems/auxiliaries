
### mysql.env

*Not for production use!* Deploys a single MySQL instance.

The service is available on review at:

```
${AUX_SERVICE_RELEASE}:3306
```

Supported versions:
- 5
- 8

| Variable     | Required | Default  | Purpose  |
| ------------ | -------- | -------- | -------- |
| PASSWORD     | no       | password | Default password |
| SIZE         | no       | 40Gi     | The size of the volume to provision |
