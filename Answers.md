### Your responses to the short answer questions should be laid out here using markdown.

For help with markdown syntax, [go here](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)


1. Question: Describe the differences between a Docker container and a virtual machine. What makes a container more aptly-suited for portability?

    Virtual Machine is a virtualized or simulated environment, they have their own individual operating system, usually takes a long time to set-up and get up and running. A docker container is also a virtualized environment however it runs in a kernel layer and it is easy to customize with a Dockerfile and starts up very fast.

2. Question: Using the command `docker run -p 49160:8080 -d <your_docker_username>/<your_docker_image_name>`, what does `49160:8080` specify?

    It runs a docker container on port 8080 and maps that port to an external port 49160.

3. Question: What is the main purpose of using a "container orchestration platform" such as Kubernetes or Docker Swarm?

   Being able to clone multiple docker images and balancing the load on each one of them for best performance.

4. Question: How do you change the number of replicas in a Kubernetes cluster?

    Using a deployment.yml configuration file and setting the options inside the file.

5. Question: What does it mean to scale a deployed application 'horizontally'? What does it mean to scale 'vertically'?
    
    Vertical scaling means usually adding more performance and memory and space to the same machine so it can handle the load. Horizontal scaling means adding more machines to handle the load instead.

6. Question: Heroku also utilizes software containers for deployment. What is the main difference between the 'free' tier of containers on Heroku vs. the paid tiers?

    Free tier usually have less ram and can only run 1 process, where paid can run multiple processes.
