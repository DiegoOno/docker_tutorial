# Docker Commands 

• docker container create - Creates a container; 

• docker run - Runs a command in a new container;

• docker container --rm run - Runs a command and after it removes the container;

•  docker start - Starts one or more stopped containers;

•  docker stop - Stop one or more running containers;

•  docker build - Builds an image form a Docker file;

•  docker pull - Pulls an image or a repository from a registry;

•  docker push - Pushes an image or a repository to a registry;

•  docker export - Exports a container's filesystem as a tar archive;

•  docker exec - Runs a command in a run-time container;

•  docker search - Searches the Docker Hub for images;

•  docker attach - Attaches to a running container;

•  docker commit - Creates a new image from a container's changes.

# Daemon mode - Containers manipulation

• docker container ls - List executing containers;

• docker container ls -a - List all containers;

• docker container inspect - Show a JSON with container specifications;
• docker container exec;
• docker container logs;

# Image management

• docker image pull <tag> - Download one image based on command tag

• docker image ls - list all images;

• docker image rm <tag> - Remove the image based on command tag

• docker image inspect <tag> - Show a JSON with image specifications;

• docker image tag <source> <tag> - Create a new tag based on the first tag or hash;

• docker image build -t <tag> - Allows to create a new image;

• docker image push <tag> - Allows to send a image or local tag 

# Docker Build

•  docker image build -t <tag_name> .

•  docker image build <args> -t <tag_name> . 

# Utils

• docker container --help

• docker image --help

• docker volume --help
