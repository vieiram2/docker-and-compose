Adds [docker-compose](https://github.com/docker/compose) to the [official Docker image](https://hub.docker.com/_/docker/).

Can be used for docker-in-docker in GitLab like this:

```
  image: vieiram2/docker-and-compose:1.12.1-1.8.0
  services:
    - docker:1.12.1-dind
```

Each branch in this repo corresponds to a Docker image in the format [docker-version]-[docker-compose-version].
