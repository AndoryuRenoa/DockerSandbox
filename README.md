# DockerSandbox

Experimenting with Docker, and then Kubernetes.

Learned a few things doing this.

1. In order to connect to anything on localhost on the same machine, the app in the docker container must be pointed towards the external ip address on this computer (it will be treated as though it is making a remote connection)

2. https requires the port forwarding to be setup properly for tls. For a spring-boot application the app may indicate that port at server.port in application.properties
