# drupal8-docker
minimal Drupal 8 installation with docker

# usage

```bash
# start containers
bin/up

# stop containers
bin/stop

# clean containers
bin/clean-containers

# show status
bin/status

# ssh into a running container
bin/ssh <CONTAINER_NAME>

# clean images to empty space on disk
bin/clean-images
```

Start your containers and then navigate to [http://localhost:8080](http://localhost:8080) to run your drupal installation.
