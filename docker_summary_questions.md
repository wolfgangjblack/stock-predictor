## Interview Readiness:
1. What does it mean to create a Docker image and why do we use Docker images?

- creating a docker image allows us to control the environment of the system we're deploying by defining the environment and only carrying around the requirements. 

- we use docker images to ensure our enviroment is the same no matter what system we're running on. For instance, we don't need to be concerned with different library versions or hardware issues. 


2. Please explain what is the difference from a Container vs a Virtual Machine?

- a virtual machine runs a persistent OS that may have additional subroutines that takes memory and bandwidth. You must also choose how to split your hardware capabilities alongside a VM when running them. They're typically best used for dev work, not necessarily for deployment

- a container is the env/system built from a docker image that can be run and will execute CMDs. for us, that typically means running the model and outputting some inference. These are 'lightweight' compared to the VM and doesn't persist or have additional subroutines

3. What are 5 examples of container orchestration tools (please list tools)?

- Kubernetes
- Google Container Engine
- Google Cloud Run
- AWS EC2 Container Service
- Azure Container Instance

4. How does a Docker image differ from a Docker container?

- The key difference between a Docker image vs a container is that a Docker image is a template that defines how a container will be realized. A Docker container is a runtime instance of a Docker image