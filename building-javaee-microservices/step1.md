First, we need to build the microservice and the image using Docker. We are
going to use a multi-stage build for this.

## Exercise

Have a look the `Builderfile` to get an impression of the simplicity of doing
containerized builds (press Q to exit). `less Builderfile`{{execute}}

Build the Docker image by running the following command:
`docker build -t javaee8-service:1.0.1 -f Builderfile .`{{execute}}
