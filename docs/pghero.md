
### pghero.env

Deploys [Pghero](https://github.com/ankane/pghero), a tool for analyzing PostgreSQL statistics.

Supported versions:
- 2

| Variable              | Required | Default        | Purpose  |
| --------------------- | -------- | -------------- | -------- |
| ENDPOINT_URL          | no       |                | The URL address where you want mailhog to be accessible |
| ENDPOINT_DISABLE      | no       | false          | For disabling the ingress |
| ENDPOINT_ISSUER       | no       |                | Set a different certificate issuer name |
| ENDPOINT_CERT         | no       | wildcard-cert  | Set a different certificate secret name |
| ENDPOINT_STATUS       | no       | enabled        | sets value of external-dns.io/status annotation |
| POD_COUNT             | no       | 2              | number of pods to deploy |
| PGHERO_POSTGRESQL_URL | no       | localhost:5432 | Set the database URL to connect to |
