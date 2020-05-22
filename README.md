# TastyIgniter Docker
Run with docker compose for automatic database configuration

    mkdir tastyigniter && cd tastyigniter
    curl -LO https://github.com/Robsgalaxy/TastyIgniter/raw/master/docker-compose.yml
    docker-compose up -d

Browse to http://localhost:8001/setup.php of your docker host. The TastyIgniter setup wizard will show up. Wait for a minute for the database container to come up and then run the setu$


Alternatively if you don't want to use docker compose you can run it manually

    docker run -d -p 80:80 robomac/tastyigniter

Run the setup and connect to a mysql db.

## Credits
TastyIgniter: https://github.com/tastyigniter/TastyIgniter
