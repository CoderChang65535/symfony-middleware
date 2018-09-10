# symfony-middleware

**PREPARE**
-
Rename `app/conf/oarameters.yml.dist` to `app/conf/oarameters.yml` and replace with your own configs.

**RUN**
-

Use Symfony PHP web server for development.
```
  php bin/console server:run
```
And open [http://localhost:8000/][1] in browser.

[1]:  http://localhost:8000/

**CLEAN CACHE**
-
```
php bin/console cache:clear --env=prod

```
**UPDATE**
-
Use composer to update Symfony.
```
composer update
```
