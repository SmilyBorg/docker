# docker
docker experiments


# Docker Images
* Nginx - nginx
* PHP - php:fpm
* Node
* Python
* Ruby



# Tools
* https://packagecontrol.io/packages/Dockerfile%20Syntax%20Highlighting
* https://packagecontrol.io/packages/GitHub%20Markdown%20Snippets
* https://packagecontrol.io/packages/GitHub%20Flavored%20Markdown%20Preview
* https://packagecontrol.io/packages/MarkdownEditing


= Useful commands =
```
# List running containers
docker ps

# Build an image called docker-whale based on the Dockerfile in the current directory
docker build -t docker-whale .

# List Docker images on the current system
docker images

# Run a container using the docker-whale image
docker run docker-whale

# Attach a shell to a running container called 665b4a1e17b6 for docker >= 1.3
docker exec -i -t 665b4a1e17b6 bash

# Attach a shell to a running container called 665b4a1e17b6 for docker < 1.3
docker attach 665b4a1e17b6

```

= Architecture =

= Examples =


= Links =
* http://docs.docker.com/windows/started/
* https://docs.docker.com/reference/builder/
* https://hub.docker.com/
* https://docs.docker.com/compose/
* http://stackoverflow.com/questions/19234831/where-are-docker-images-stored-on-the-host-machine
* http://docs.aws.amazon.com/elasticbeanstalk/latest/dg/create_deploy_docker_ecstutorial.html
* http://docs.aws.amazon.com/elasticbeanstalk/latest/dg/create_deploy_docker_v2config.html
* http://docs.aws.amazon.com/elasticbeanstalk/latest/dg/create_deploy_docker_image.html
* https://github.com/docker/docker/issues/1326
* http://thenewstack.io/understanding-the-docker-cache-for-faster-builds/
* http://stackoverflow.com/questions/17236796/how-to-remove-old-docker-containers
* https://intercityup.com/blog/downsizing-docker-containers.html
* http://blog.thoward37.me/articles/where-are-docker-images-stored/
* https://rwmj.wordpress.com/2013/06/19/the-boring-truth-full-virtualization-and-containerization-both-have-their-place/
* http://www.linuxjournal.com/content/containers%E2%80%94not-virtual-machines%E2%80%94are-future-cloud
* http://opensource.com/business/14/9/security-for-docker
* http://stackoverflow.com/questions/24225647/docker-any-way-to-give-access-to-host-usb-or-serial-device
