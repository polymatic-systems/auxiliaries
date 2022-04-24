
### mailhog.env

Deploy [Mailhog](https://github.com/mailhog/MailHog) , a developement tool for capturing and viewing outgoing emails.

The service is available on review at: 

```
${AUX_SERVICE_RELEASE}:5432
```

Supported versions:
- 1

| Variable         | Required | Default       | Purpose  |
| ---------------- | -------- | ------------- | -------- |
| ENDPOINT_URL     | no       |               | The URL address where you want mailhog to be accessible |
| ENDPOINT_DISABLE | no       | false         | For disabling the ingress |
| ENDPOINT_ISSUER  | no       |               | Set a different certificate issuer name |
| ENDPOINT_CERT    | no       | wildcard-cert | Set a different certificate secret name |
| ENDPOINT_STATUS  | no       | enabled       | sets value of external-dns.io/status annotation |
