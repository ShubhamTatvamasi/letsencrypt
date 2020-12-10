# letsencrypt

Add API key of your domain provider.

Create a file `godaddy.keys` and add following keys:
```bash
GD_Key="sdfsdfsdfljlbjkljlkjsdfoiwje"
GD_Secret="asdfsdafdsfdsfdsfdsfdsafd"
```

https://github.com/acmesh-official/acme.sh/wiki/dnsapi#4-use-godaddycom-domain-api-to-automatically-issue-cert

issue certificate:
```bash
docker-compose run issue
```

get help:
```bash
docker-compose run help
```

Copy `fullcahin.cer` and `shubhamtatvamasi.com.key` to your sever.

for deleting all containers run:
```bash
docker-compose down
```
---

Check Certificate transparency

https://transparencyreport.google.com/https/certificates
