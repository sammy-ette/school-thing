# PHP CRUD App

This is a CRUD app written in PHP based on [this here](https://www.tutorialrepublic.com/php-tutorial/php-mysql-crud-application.php) for a school assignment.

# How to Deploy
Docker is used to host both the web app and the MySQL Database.  
Just clone the repo and put up both services with Docker.

Don't forget to move the .env.example to .env and fill in the required variables (`DB_PASSWORD` and `DB_ROOT_PASSWORD`).

You can modify the `docker-compose.yml` to your liking in this repository.

```sh
git clone https://github.com/sammy-ette/school-thing
cd school-thing
docker compose up -d
```
