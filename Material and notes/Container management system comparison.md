Comparison of Docker swarm and kubernetes:


purpose:
management tool to be used for scaling container groups. ("contianer orchestration")


Docker Swarm:

pros:

cons:


kubernetes:

pros: 

cons:


Outcome: 
In terms of learning to use "contianer orchestration" on a beginner basis, and having it to be
needed only on a small scale, with no need for specialized tools, I have desided to focus on
learning Docker swarm, as it will also be simple to setup with the docker already isntalled. if I needed 3rd-party addon
to do features such as logging of operation and status.



links:

https://circleci.com/blog/docker-swarm-vs-kubernetes/#c-consent-modal
notes / extracts:

ocker Swarm

Docker Swarm is an open source container orchestration platform built and maintained by Docker. 
Under the hood, Docker Swarm converts multiple Docker instances into a single virtual host.
A Docker Swarm cluster usually contains three items:

    Nodes
    Services and tasks
    Load balancers

Nodes are individual instances of the Docker engine.
Nodes control your cluster and manage the containers used to run your services and tasks.
Docker Swarm clusters also include load balancing to route requests across nodes.

 "automated load balancing within the Docker containers."


 Which platform should you use?
 
 Both Kubernetes and Docker Swarm serve specific use cases. Which one is best for you depends on your team’s needs.
 
 For beginners, Docker Swarm is an easy-to-use and simple solution to manage containers at scale.
  If your company is moving to the container world and does not have complex workloads to manage,
   then Docker Swarm is the right choice.
 
 If you want a complete package with monitoring, security features, self-healing, high availability,
 and absolute flexibility for tricky or complex projects, then Kubernetes is the right choice.
 If you need all the capabilities of Kubernetes but are put off by its learning curve,
 then K3s is a good alternative.

https://spacelift.io/blog/docker-swarm-vs-kubernetes

pcitures for both Architecture.

"Is Docker Swarm better than Kubernetes?

Docker Swarm typically offers better performance for smaller workloads due to its lower overhead and simpler configuration.
Kubernetes, on the other hand, is more resource-intensive but provides advanced features like auto-scaling, high availability,
and fault tolerance, making it better suited for larger, complex systems.
The choice depends on the scale of your operations and the level of orchestration complexity required."

https://betterstack.com/community/guides/scaling-docker/docker-swarm-kubernetes/
Guides to deploying apply 

https://www.ibm.com/think/topics/docker-swarm-vs-kubernetes
Quick overview

