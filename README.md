# Docker Java Image
Docker image of Java Virtual Machine that adds additional information about the container itself.

### Get started

`docker run -it fayndee/java:oracle-java8 bash --login -c "YOUR_COMMAND_HERE"`

### Information exposed as environment variables

environment variable  | value
--------------------- | --------
DOCKER_CONTAINER_NAME | Primary name of your container (i.e. NAMES in `docker ps`). It is specially useful when the name is assigned dynamically at runtime (e.g. using [docker-compose](https://github.com/docker/compose)).
