# n8n Docker Setup
This Docker config contains an instance of n8n with Ollama support. Allowing you to couple the two tools in the same Docker container.

## Requirements
- Docker or Docker Desktop

## Setup
Pull the repo into the local directory of your choice.

Create two directories in your project root folder to mount to the container for persistance:
- ``local-files`` - n8n uses this directory to store documents output from your automations, as well as where you can put files you want n8n to use in your automations
- ``ollama-models`` - this is where your Ollama instance will store the models you pull down

Once the directories have been created, spin up the container:
``docker compose up``

## Resources
[n8n Documentation Site](https://docs.n8n.io/) - n8n's docs for your reference
[Ollama Docs](https://docs.ollama.com/) - documentation site for Ollama

