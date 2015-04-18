# Docker Cheat Sheet

## boot2docker
- `boot2docker init`: Initialize boot2docker. Will download VM image.
- `boot2docker shellinit`: Prep the local environment for interacting with the VM. Includes `export` commands needed to set environment variables.
- `boot2docker up`: Start the VM.
- `book2docker ip`: Get the VM's IP.
- `book2docker ssh`: SSH into the VM.

## Basics
- `docker run -d -P -v /local/dir:/container/dir --name foo container`: Start a container nameed "foo" with port forwarding, mapping a local directory to a directory in the container.
    - `docker run -d -P -v /Users/dhuffman/dave/fundockerisfun/web:/usr/share/nginx/html --name web nginx`: Start a NGinx container and map a local directory to the default NGinx public directory.
- `docker exec -i -t container bash`: Connect to a running container.

## Links
- <http://viget.com/extend/how-to-use-docker-on-os-x-the-missing-guide>