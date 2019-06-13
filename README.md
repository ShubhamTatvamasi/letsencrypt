# letsencrypt

issue certificate
```
docker-compose run issue
```

crate a new TXT record in your domain provider
```
Type: TXT
Host: _acme-challenge
TXT Value: <check-console-output>
```

renew certificate
```
docker-compose run renew
```
