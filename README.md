# AI Containers

This is a compose file containing easy setup of several AI tools

## Pre-requisites

The compose definition has been mostly tested with Docker.

To install Docker, follow the official instructions [here][Docker Install].

[Docker Install]: https://docs.docker.com/engine/install/

## GPU Support

Check the official documentation from NVIDIA on how to install the container
toolkit [here][Nvidia Container Install].

[Nvidia Container Install]: https://docs.nvidia.com/datacenter/cloud-native/container-toolkit/latest/install-guide.html#installation

## Execution

To run all the containers, simply run the `docker compose` command below.

```bash
docker compose up -d
```