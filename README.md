# container-packer [![Build Status](https://cloud.drone.io/api/badges/yellowmegaman/container-packer/status.svg)](https://cloud.drone.io/yellowmegaman/container-packer)

Most basic docker image with latest stable docker + Hashicorp Packer

Example usage:
```
docker run -i -t -v /var/run/docker.sock:/var/run/docker.sock yellowmegaman/container-packer:latest version
docker run -i -t -v /var/run/docker.sock:/var/run/docker.sock quay.io/yellowmegaman/container-packer:latest version
```
