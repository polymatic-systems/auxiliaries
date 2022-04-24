
### sidekiq-ui.env

Deploys the [Sidekiq UI](https://github.com/mperham/sidekiq/wiki/Monitoring) for monitoring sidekiq jobs.

Supported versions:
- 5

| Variable                   | Required | Default        | Purpose  |
| -------------------------- | -------- | -------------- | -------- |
| ENDPOINT_URL               | no       |                | The URL address where you want mailhog to be accessible |
| ENDPOINT_DISABLE           | no       | false          | For disabling the ingress |
| ENDPOINT_ISSUER            | no       |                | Set a different certificate issuer name |
| ENDPOINT_CERT              | no       | wildcard-cert  | Set a different certificate secret name |
| ENDPOINT_STATUS            | no       | enabled        | sets value of external-dns.io/status annotation |
| POD_COUNT                  | no       | 2              | number of pods to deploy |
| SIDEKIQ_REDIS_URL          | no       | localhost:6379 | Set the redis URL to connect to |
| SIDEKIQ_LICENSE_PRO        | no       |                | Sidekiq-Pro license if available |
| SIDEKIQ_LICENSE_ENTERPRISE | no       |                | Sidekiq-Enterprise license if available |
