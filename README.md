## Overview

This repo contains a docker-compose setup for various Jupyter Notebook variants.

It is designed to be run as a [libre.sh](https://github.com/indiehosters/libre.sh) [application](https://github.com/indiehosters/applications), but can be d
eployed on any Docker host with Compose.

## Installing

Run `scripts/install` to generate an `env` file.

It will prompt you for an image variant and a password, or you can specify them on the command line like so:

sudo NOTEBOOK_IMAGE=jupyter/minimal-notebook PASSWORD=changeme /bin/sh ./scripts/install

