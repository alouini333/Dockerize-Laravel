# Dockerize Your Laravel application
This project is made to make it easier for Laravel developers to DEVELOP and SHIP their applications faster
It's not PRODUCTION oriented


Before copying the docker-compose and the docker directory, make sure you installed Docker.
Take a look at the [Docker documentation](https://docs.docker.com/install/). It's not magic.


Copy the docker directory and docker-compose to the root of your laravel application and run `docker-compose up -d`

You application will be available at http://localhost

# Database
In `docker-compose.yml` you can specify your `MYSQL_ROOT_PASSWORD` and `MYSQL_DATABASE`

