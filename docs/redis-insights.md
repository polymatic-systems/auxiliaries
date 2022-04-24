
### redis-insights.env

Deploys [Redis Insights](https://docs.redislabs.com/latest/ri/) for inspecting Redis data. The Redis URI is set from the Redis Insights dashboard after it's installed.

Supported versions:
- 1

| Variable              | Required | Default         | Purpose  |
| --------------------- | -------- | --------------- | -------- |
| ENDPOINT_URL          | no       |                 | The URL address where you want mailhog to be accessible |
| ENDPOINT_DISABLE      | no       | false           | For disabling the ingress |
| ENDPOINT_ISSUER       | no       |                 | Set a different certificate issuer name |
| ENDPOINT_CERT         | no       | wildcard-cert   | Set a different certificate secret name |
| ENDPOINT_STATUS       | no       | enabled         | sets value of external-dns.io/status annotation |
| SIZE                  | no       | 10Gi            | The size of the volume to provision |
