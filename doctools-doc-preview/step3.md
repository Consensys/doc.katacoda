Build the preview with the Doctools Docker image.

Go in the documentation site directory and execute the `docker-compose` command.

## Task

First, go in the `template-docsite` directory: `cd template-docsite`{{execute}}.

Then run `docker-compose up -d`{{execute}}

Bravo, the preview service is running as a Docker container on this playground environment!

You can now preview your doc by looking at the [live preview site](https://[[HOST_SUBDOMAIN]]-8000-[[KATACODA_HOST]].environments.katacoda.com).

_Note that the preview address above only works for this online playground._

_When you will run the preview on your local machine, site will be visible at `http://0.0.0.0:8000`._
