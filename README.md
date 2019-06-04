# Docker Images
Repository of docker images for Postgres and plv8

## Postgres with plv8 [(mysticmind/postgres-plv8](https://hub.docker.com/r/mysticmind/postgres-plv8))
These images are based on the [official Postgres image](https://hub.docker.com/r/_/postgres/), and have the [plv8](https://github.com/plv8/plv8) extension installed and enabled.

### Tags
- [9.6-1.4](https://github.com/mysticmind/docker-images/blob/master/postges-plv8/9.6-1.4/Dockerfile)
- [10-1.4](https://github.com/mysticmind/docker-images/blob/master/postges-plv8/10-1.4/Dockerfile)

### Usage
```bash
$ docker run -d --name postgres mysticmind/postgres-plv8:9.6-1.4
```

Copyright © 2019 Babu Annamalai. Provided under [MIT](http://www.opensource.org/licenses/mit-license.php) license.
