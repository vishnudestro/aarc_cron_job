AARC API's Routine check
---

The module is to run a periodic check on the API system, Once a hit was done it store related data in database periodically.

#### Initializing the Cron job using docker

1. You need to build the docker image first.
    `docker buid -t <image name> .`

    Example: ` docker build -t aarc_cronjob .`

2. You also need to run the docker container using the builded image.

    `docker run --name <container name> -d <image name>`

    Example: `docker run --name aarc_cronjob -d aarc_cronjob`

