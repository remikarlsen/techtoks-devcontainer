# Tech toks Python devcontainer

This is a very simple demo example of a devcontainer used for a dockerized local Python dev env.

## Prerequisites
On your local machine:
- Docker
- VS Code
- VS Code extension 'Dev Containers'

After cloning this repo, run from Command palette: Dev Containers: Open in container, or Rebuild in container

## Run the server
In order to run the uvicorn server, run this inside the dev container:

`uvicorn src.main:app --host 0.0.0.0 --port 8888 --reload`


## Doc
https://code.visualstudio.com/docs/devcontainers/containers#_getting-started

