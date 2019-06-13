# letsencrypt

issue certificate:
```
docker-compose run issue
```

create a new TXT record in your domain provider
```
Type: TXT
Host: _acme-challenge
TXT Value: <check-console-output>
```

renew certificate:
```
docker-compose run renew
```

Copy `fullcahin.cer` and `*.shubhamtatvamasi.com.key` in your sever.

for deleting all container run:
```
docker-compose down
```
