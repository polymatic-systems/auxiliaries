
### pgweb.env

Deploys [Pgweb](https://github.com/sosedoff/pgweb), a simple non-technical SQL database GUI.

Supported versions:
- 0

| Variable              | Required | Default        | Purpose  |
| --------------------- | -------- | -------------- | -------- |
| ENDPOINT_URL          | no       |                | The URL address where you want mailhog to be accessible |
| ENDPOINT_DISABLE      | no       | false          | For disabling the ingress |
| ENDPOINT_ISSUER       | no       |                | Set a different certificate issuer name |
| ENDPOINT_CERT         | no       | wildcard-cert  | Set a different certificate secret name |
| ENDPOINT_STATUS       | no       | enabled        | sets value of external-dns.io/status annotation |
| POD_COUNT             | no       | 2              | number of pods to deploy |
| PGWEB_POSTGRESQL_URL  | no       | localhost:5432 | Set the database URL to connect to |
