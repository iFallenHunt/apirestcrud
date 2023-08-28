In this project, as a form of study, I created a REST API with crud linked to a postgreSQL database, all based on a docker container.

My main objective from this project was to understand more about backand tools with java spring and docker/docker compose.

Crud works in a simple way through the MAVEN manager, so from your IDE start all the necessary dependencies and run:

```
mvn clean package -DskipTests
```

```
docker compose up -d java_db
```

```
docker compose up -d java_app
```
after that the crud will be available at LOCALHOST:8000