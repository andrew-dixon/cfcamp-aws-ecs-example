# CF Camp 2018 - Amazon Elastic Container Service (ECS) Example

This repo contains the code used to build the container used for the example shown in the Amazon Elastic 
Container Service (ECS) presentation by Andrew Dixon at CF Camp in Munich on Thursday 8th November 2018.

## Files

The repo contains the following files

* `buildspec.yml` - Used with AWS CodeBuild to build the container image, test it and push it to the Elastic Container Registry.
* `docker-compose.yml` - Used for local development / testing of the container.
* `Dockerfile` - Commands to create the container image
* `variables.env` - Included for completness, but is empty. Could be used to define key/value pairs of environment variables.
* `site/index.cfm` - The example index file for the site that is copied to the web server directory during the image build.
