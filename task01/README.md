## Task 1

For task 1, we're going to deploy a popular open-source music streaming server: [Navidrome](https://www.navidrome.org/).

The most straightforward approach is to use [minikube](https://minikube.sigs.k8s.io/docs/). By referring to the handbook and familiarising yourself with Kubernetes resources, you will be able to complete this task. It is recommended starting by translating the provided [Docker Compose](https://www.navidrome.org/docs/installation/docker/) file into manifests and applying them locally. Please place your Kubernetes configuration files inside this directory.

<ins>Using Helm and Kompose is banned for this task.</ins>

Success is defined as being able to access the Navidrome instance via localhost on your machine and completing [report.md](../report.md).

If you would like to take this a step further, you can experiemnt with configuring persistence or public routing, however they are not strictly necessary for this task.

### (Optional) Simple Docker Implementation

You can try out using the Docker compose file too if you've never used Docker before. 

1. Install [Docker](https://www.docker.com)
2. Make a file called docker-compose.yml
3. Copy in the [Docker Compose](https://www.navidrome.org/docs/installation/docker/) contents into it
4. In the directory, use the command `docker compose up`

Your navidrome server should be up and running.
