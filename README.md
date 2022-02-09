# docker-nginx-keycloak-mysql

Pre-run

1. Prepare your domain and your SSL certificate
2. Make "certs" directory and push your ssl certificate file ( *.crt, *.key ).
3. Go to "conf/nginx.conf" and insert your domain and your ssl.
4. Go to "docker-compose.yml" and insert your domain into "KEYCLOAK_FRONTEND_URL"

Run

```
docker-compose up --build -d
```
