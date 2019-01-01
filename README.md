# pckrdckr [![Build Status](https://cloud.drone.io/api/badges/yellowmegaman/pckrdckr/status.svg)](https://cloud.drone.io/yellowmegaman/pckrdckr)

Most basic docker image with latest stable docker + Hashicorp Packer

Example usage:
```
docker run -i -t -v /var/run/docker.sock:/var/run/docker.sock yellowmegaman/pckrdckr:latest version
```
