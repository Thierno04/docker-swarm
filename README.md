  # What is Docker Swarm ?

* Cluster of Docker Engines is called a Docker swarm.
* In a microservice architecture, where you need to work on different project components on different machines and a master slave architecture where the   master nodes control the slave nodes.
* It is an archestration tool which allows you to manage multiple docker containers deployed on different machines.
* It helps in automatic load balancing while allowing you to leverage he power of docker containers and guarantees high service availability.

# What is Docker Stack ?
* Stacks allow for multiple services, which are containers distributed across a swarm, to be deployed and grouped logically.
* The services run in a stack can be configured to run serveral replicas, which are clones of the underlying container.
* To get a stack up and running just requires a docker-stack yaml file.
* The deployment of many inter-communicating microservices is where docker stack comes in.
