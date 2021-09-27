# SICEI fake — Demo of a Dockerized web API

## Build and run

Build the Docker image:

```txt
docker image build . -t hercerm/sicei
```

Run the Docker image:

```txt
docker container run -p 8080:8080 -d --name c-hercerm-sicei hercerm/sicei
```

See the list of students: <http://localhost:8080/students>
