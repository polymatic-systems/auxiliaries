
### mongo.env

*Not for production use!* Deploys a single MongoDB instance.

The service is available on review at:

```
${AUX_SERVICE_RELEASE}:27017
```

Supported versions:
- 4

| Variable     | Required | Default  | Purpose  |
| ------------ | -------- | -------- | -------- |
| USER         | no       | admin    | Default user name |
| PASSWORD     | no       | password | Default password |
| SIZE         | no       | 40Gi     | The size of the volume to provision |
