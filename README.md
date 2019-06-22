# letsencrypt

issue certificate:
```
docker-compose run issue
```

create two TXT record in your domain provider
```
Type: TXT
Host: _acme-challenge
TXT Value: <check-console-output>
```

Check the updated TXT values:

https://mxtoolbox.com/SuperTool.aspx?action=txt%3a_acme-challenge.shubhamtatvamasi.com

renew certificate:
```
docker-compose run renew
```

Copy `fullcahin.cer` and `*.shubhamtatvamasi.com.key` to your sever.

for deleting all containers run:
```
docker-compose down
```
