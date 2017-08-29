
# About quests 
Quests are designed as replacements of courses on cloudassessments.com. The goal is to build more of a journey and story telling experience.

Quest story line proposal: April has started working for a startup that has a monolithic application currently running on vm's. She has been assigned the challenge of helping the organization increase the speed of code production, reduce the cost of scaling, and become more agile. After recently learning about containers she decides to peruse this solution and modify the instaflam's application to work in a service oriented architectures running on containers. Immediately before worrying about running containers in production she jumps in to setup the code set on using docker containers for her developers. She knows that this will help increase development time and reduce setup issues for developers working on the project.

# Course/Quest Name: Learn Docker With Anthony James
* About this course // Want to cover the depth of the quest/course and what we hope to accomplish and why it matters to your development and how it solves caling and business problems
* About Anthony James // Only if you want
* What we will accomplish in this quest // Will show the working application, that we will be building through the quest and then work backwards
* History of containers

# Acitivity 1: Getting Started With Docker
* History of containers // Quick run down of the history of containers (I'm worried this is to boring, thoughts?)
* Working with Docker Hub image repository // show how to find 'official' images and how they typically make the associated 'Dockerfile' used to build it in Github
* Micro services, containers, and vm's o' my! // Describe what problems containers solve and how the solve them.
* Connecting to docker hub
* Running docker images // We will pull a docker image with our demo app from a public repo and run it. Goal is to get into "doing stuff" first and then back into building it from scratch - Basic of docker run command, detached mode etc
* Understanding Docker caching // We'll make a change to our docker file and look at docker "layering"
* Architecture accomplishment overview // Now that you are running your first application lets talk about how it works and why
Challenge Activity: Will present the student with a vm, the challenge will be to get docker setup and running and pull down the application from the public docker repository.

# Activity 2: Dockerizing our node.js application
* Application overview and github // Will walk through the "single container version" of the  application. We will get to building the multi-container version but to keep concepts simple here we won't have that.
* Defining the container with the Dockerfile // Learn how to build the docker file and attributes within the docker file to run the application. We'll also probably mention briefly how this concept works as service
* Building application container // Build the image, run, make change, learn to clear cache, build again, then delete images.
* Tagging // Wonderful world of tagging and name spaces
* Port Redirection // Accessing your container by redirecting the container's listening ports to a port on the underlying host 
* Volume Redirection // Perform builds/change files/update configurations by mounting the underlying host directory to a key location inside your container
* Optional: uploading the image to your personal repository // Take your work home with you if you want. 
Challenge Activity: Will present the student with a Docker container and the proper application files for dockerizing. 

# Activity 3: Building services with Docker compose
* What are container services and how does Docker compose help

# Activity 4: Monolithic vs Service Oriented Architecture 
* How containers solve scaling and business problems
* How micro services work with containers
* Migrating and running monolithic applications with containers
* Migrating monolithic applications to micro service oriented architecture.
* Service structure concepts for containers

# Activity 5: Docker Networking
* Default Docker Networks // What networks are created by Docker by default and what are they for (docker network ls, inspect, create, rm)
* Deprecation // Docker has deprecated the widely used --link now that container networks can be customized, important to know since many implementations still use and all current certifications still reference

# Activity 6: Pushing to docker repositories 

# Activity N: This is the last activity it will be designed to introduce advanced concepts and will also be used as the first activity of the container deep dive quest.
* Docker Storage // Illustrate the 'layering' method of building images and containers and how they are cached
* Managing Containers and Images // Removing containers, removing images (and orphaning containers based on them)
* Introduction to Docker Swarm // How swarm enhances Docker in a multi-container and node implementation
