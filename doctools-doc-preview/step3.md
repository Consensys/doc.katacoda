Build the doc with the Doctools Docker image.

Go in the doc site directory and execute the Docker Compose command.

## Task

First, go in the `template-docsite` directory: `cd template-docsite`{{execute}}.

Copy the `.env.template` file to a new `.env` file that will never be commited:

`cp .env.template .env`{{execute}}

We don't have to modify it for this simple demo.

Then run `docker-compose up -d`{{execute}}

Bravo, the preview service is running as a Docker container!

You can now preview your doc by looking at the live served site, here served at https://[[HOST_SUBDOMAIN]]-8000-[[KATACODA_HOST]].environments.katacoda.com for the online demo but will be `http://0.0.0.0:8000` on your local machine.
