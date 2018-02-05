# docker-antidote-alpine [![](https://images.microbadger.com/badges/image/pviotti/antidote-alpine.svg)](https://microbadger.com/images/pviotti/antidote-alpine)

This repository contains the [Docker](http://docker.io) file for a container 
image of [AntidoteDB](http://syncfree.github.io/antidote/index.html) based on Alpine Linux.

Image on Docker Hub: https://hub.docker.com/r/pviotti/antidote-alpine/  

The image on the `iptables` branch includes iptables, which can be useful to 
create network partitions for testing AntidoteDB.

## Running

```bash
$ docker pull pviotti/antidote-alpine:latest
$ docker run --rm -it -p "8087:8087" pviotti/antidote-alpine
```

## License

License: WTFPL.  
