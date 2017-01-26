# compose-samples
This repository contains some sample Compose file mostly used to deploy some stack, like for Docker Swarm monitoring, elk or some other.

The [blog post](http://jmkhael.io/deploy-swarm-services-with-the-new-docker-stack-and-a-compose-file-2/) documents the monitoring stack.

## Docker Swarm monitoring stack

This stack is composed of two service wich I tend to always create first on a Swarm:
* the [Visualizer](https://github.com/ManoMarks/docker-swarm-visualizer) and 
* [Portainer](http://portainer.io)


