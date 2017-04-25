# Docker Python Aiohttp Hello-World Server

This is a sample 'hello-world' server using [aiohttp](aiohttp.readthedocs.io).

Build the docker image with the command:

```
docker build -t docker-aiohttp-hello-world .
```

Run the docker container with the command:

```
docker run -p 5858:5858 docker-aiohttp-hello-world
```

You can hit the server at http://localhost:5858 and http://localhost:5858/other-routes .  

You can pull the built docker image from https://hub.docker.com/r/rendijssmukulis/docker-aiohttp-hello-world/

The walkthrough of how this project was built can be found [here](http://codevoid.io/building-a-hello-world-docker-image-for-a-python-service.html).

