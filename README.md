# TODO
We need to sort out image generation as it got out of sync w/r/t what got published on https://hub.docker.com/r/orchestracities/crate/tags
All images that got published before this commit:

- https://github.com/orchestracities/crate-ce/commit/d375176181f9f06c5dd8b697cf0f739bc43d1c45

have to be regenerated with the fixes in the above commit and then published again to Docker Hub, making sure the old images get overwritten. Also we should delete 4.04 from Docker Hub as it wound up there by accident and perhaps create a 4.0.12 release in this repo since we manually built and pushed a 4.0.12 image to Docker Hub.

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
