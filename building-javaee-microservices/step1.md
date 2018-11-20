First, we need to build the microservice and the image using Docker. We are
going to use a multi-stage build for this.

1. Change into the project directory. `cd building-javaee-microservices`{{execute}}

2. Have a look the `Builderfile` to get an impression of the simplicity of doing
containerized builds. `less Builderfile`{{execute}}

3. Build the Docker image by running the following command: `docker build -t javaee8-service:1.0.1 -f Builderfile .`{{execute}}
