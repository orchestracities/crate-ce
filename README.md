# crate-ce
The CrateDB Community Edition (CrateDB CE) does not include any Enterprise features but can be run on as many nodes as you wish.

## Tags

- 4.0.4
- 4.0.12
- 4.1.1
- 4.1.8
- 4.2.1
- 4.2.2


# How to Use This Image

```sh
$ docker run -p 4200:4200 orchestracities/crate:4.2.2 -Cdiscovery.type=single-node

```

Inspired by:

- https://github.com/crate/docker-crate
- https://hub.docker.com/_/crate/
- https://github.com/r2dedios/crate-ce-docker
