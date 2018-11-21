After the Docker image has been build, we can now use Docker to run the image
as a container locally. But we also need additional infrastructure, so we use
a Docker Compose file to fire up everything together.

## Exercise

Have a look at the `docker-compose.yml` file and the service definitions
for the service, database and message queue. `less docker-compose.yml`{{execute}}

Next, start the complete stack using Docker Compose. `docker-compose up`{{execute}}
