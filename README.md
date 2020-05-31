## Dockit - Manage Docker Containers

This is a repository for a simple web application developed using Flask to manage docker containers.

### Instructions

Here are the instructions to use this repository.

* Setup a system with docker server
* Make sure docker server is running on a port
* Clone this repository by running - `git clone https://github.com/dgadiraju/dockit-core.git`
* Go to **dockit-core** directory by running `cd dockit-core`
* Make sure Docker is setup in your PC
* Export environment variable - `export REMOTE_DOCKER_HOST=SERVER_ON_WHICH_DOCKER_CONTAINERS_TO_BE_MANAGED`
* Example - `export REMOTE_DOCKER_HOST=tcp://34.71.202.90:2375`
* Run `docker-compose up`
* Go to http://localhost:5000 to see the list of containers and images