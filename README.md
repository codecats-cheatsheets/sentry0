# Sentry0
### Installation
```sh
docker-compose up
```
### After Install
```sh
docker ps
docker exec -it [directory_sentry_1] bash
```
Migrations:
```sh
sentry upgrade
```
If you use your app in cloud you'll need add ALLOWED_HOSTS, to allow all hosts, login into container:
```sh
echo "ALLOWED_HOSTS = ['*']" >> /etc/sentry/sentry.conf.py
```

### Todos

 - More autoamatic install (no interactive)
 - basic config in file

License
----

MIT
