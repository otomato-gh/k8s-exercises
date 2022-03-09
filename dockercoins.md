Please deploy the Dockercoins application using the images available in [dockercoins](https://hub.docker.com/u/dockercoins) repository on Docker Hub.

Create a Deployment for each of the components: 
 - dockercoins/worker
 - dockercoins/rng
 - dockercoins/hasher
 - dockercoins/webui
 - redis
 
 Hint: use `kubectl create deployment --image=your_image_name`
 
 Then expose redis, rng and hasher for internal access.
 Then expose webui for external access.
 
 Verify everything works by visiting the webui and checking service logs.
 
