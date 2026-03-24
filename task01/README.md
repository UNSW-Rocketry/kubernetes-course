## Task 1

For task 1, we're going to deploy a popular open-source music streaming server: [Navidrome](https://www.navidrome.org/).



The most straightforward approach is to use [minikube](https://minikube.sigs.k8s.io/docs/). By referring to the handbook and familiarising yourself with Kubernetes resources, you will be able to complete this task. It is recommended starting by translating the provided [Docker Compose](https://www.navidrome.org/docs/installation/docker/) file into manifests and applying them locally. Please place your Kubernetes configuration files inside this directory.

Success is defined as being able to access the Navidrome instance via localhost on your machine.

If you would like to take this a step further, you can experiemnt with configuring persistence or public routing, however they are not strictly necessary for this task.