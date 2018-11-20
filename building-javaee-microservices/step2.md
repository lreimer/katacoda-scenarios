After the Docker image has been build, we can now use Docker to run the image
as a container locally. But we also need additional infrastructure, so we use
a Docker Compose file to fire up everything together.

1. Have a look at the `docker-compose.yml` file, and have a look at the service
definitions for the microservice, the database and the message queue.
`less docker-compose.yml`{{execute}}

2. Now, fire up the complete stack using Docker Compose. `docker-compose up -d`{{execute}}

3. Check that everything is running. `docker-compose ps`{{execute}}

4. Have a look at the logs. `docker-compose logs -f`{{execute}}
