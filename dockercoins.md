Please deploy the Dockercoins application using the images available in [dockercoins](https://hub.docker.com/u/dockercoins) repository on Docker Hub.

Create a Deployment for each of the components: 
 - dockercoins/worker:v0.1
 - dockercoins/rng:v0.1
 - dockercoins/hasher:v0.1
 - dockercoins/webui:v0.1
 - redis
 
 Hint: use `kubectl create deployment <name> --image=your_image_name`
 
 Then expose redis (on port 6379), rng and hasher (on port 80) for internal access.
 Then expose webui for external access (on port 80 with NodePort).
 
 Hint: `kubectl expose deployment <name> --port=<port> <--type=Type>`
 
 Verify everything works by visiting the webui and checking service logs.
 
