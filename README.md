# Using Nginx as reverse proxy for Keycloak

Simply run

```
docker-compose up
```

This command starts	 Nginx, Keycloak and the proper database.
The Nginx configuration can be found in `nginx.conf`.

Accessing [http://localhost:8080/keycloak/auth/](http://localhost:8080/keycloak/auth/) will open the administration UI of Keycloak. The credentials are "admin" and "password".