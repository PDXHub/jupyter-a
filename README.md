## Overview

This repo contains a docker-compose setup for Jupyter Notebook [stacks](https://github.com/jupyter/docker-stacks/#stacks-tags-versioning-and-progress). You can use a pre-built stack, or create your own using one of those as a base.

It is designed to be run as a [Libre.sh](https://github.com/indiehosters/libre.sh) [application](https://github.com/indiehosters/applications), but can be deployed on any Docker host with Compose.

## Installing

On Libre.sh, you can provision a new domain with this app with the following one liner:

    sudo libre provision -a "github.com/PDXHub/jupyter-a" -u your.domain.name -s

You can also put env vars on the command line after `sudo`:

    sudo NOTEBOOK_IMAGE=jupyter/minimal-notebook PASSWORD=changeme /bin/sh ./scripts/install

