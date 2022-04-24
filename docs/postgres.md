
### postgres.env

*Not for production use!* Deploys a single Postgresql instance.

The service is available on review at: 

```
${AUX_SERVICE_RELEASE}:5432
```

Supported versions:
- 11

| Variable     | Required | Default  | Purpose  |
| ------------ | -------- | -------- | -------- |
| USER         | no       | postgres | Default user name |
| PASSWORD     | no       | password | Default password |
| DATABASE     | no       | database | Default database |
| SIZE         | no       | 40Gi     | The size of the volume to provision |
