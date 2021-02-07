# What you did with docker?

    1. Involved in using of Docker to build images using maven and Experienced in deploying Micro Services to App Servers using Jenlins pipelines.
    2. Used Jenkins and pipelines to drive all micro services builds out to the Docker-registry and then deployed to Kubernetes Clusters.
    6. Extensively worked on Docker containers by deploying and maintaining production environment using AWS EC2 instances.

# Docker issues?
    Pod killed with out of memory, 
    Pod is running but no responding
    Pod is unable to connect to upstream
    The node on which the pod is running having issues (Timeout issues, Upload is taking time, Blocking traffic because of payload type)

# Ci/cd pipeline... flow
     Repositories will include a docker file and Jenkins file..
     Docker file consists of baseimage, run, copy, env, expose &entrypoint commands & details...
     Jenkins file consists of metadata.. like service name teamname manager name
     Calling methods inside Jenkins file
     
# Deployment
    So in order to create like whenever we are taking the source code compiling it then automatically pushing that into a Docker image. 
    I mean to select creating an image out of it. So then usually we run the test, make sure that image that has the same functionality that we are looking for. 
    So once the test has been successfully done. We ship them and store that it remote repository, like j frog artifactory, 
    then we can use containers, apply that in the pod definitions within Kubernetes, for all our micro services.
    
    So basically using built in templates for pod definitions for our service definitions for the deployments. 
    We are being to automate all the deployments such that we have zero downtime.
    And we are also implementing advanced deployment techniques like blue green Canary.
    
# jenkins, github, docker  
So basically for the source code repository(GitHUb), integrate that within Jenkins and basically in order to trigger that action I have used like web hooks.
So once we build the package using like Maven. I've been working with Java based application so I have used like Gen plugin for automated testing. 
And once it has been successfully done. Then ntegrated that within sonar cube in order to build out the code coverage static analysis in order to come up with a better quality code.

# Yes, I have managed like the environment variable choosing like shared libraries across like multiple projects. As part of like dependencies and also creating a     custom library from scratch within Jenkins.

# in my last assignment have been dockerized most of the Spring Boot applications and middleware applications like j boss, Tomcat Apache for configuration changes     and a production part so that when I've used like dockerfile in order to achieve that,
 
    
# keywords we use in order to build a Docker file:
    So in order to build our Docker file will be specified different keywords like from will be specify where we are taking the base image and run command, we use       for initialize anythings and expose command we use for expose the source port and the target port and cmd. Basically we use that in order to initialize anything     at building up the image entry point is time when we launched the image or the container.
    
# Docker build and Docker run ( Storing base images)
    using a "Docker hub" or "Docker registry", in order to store our "base images".
    Once the build and test is successfully done, we store our like artifactory within like Nexus or j frog. But the base images we will store that source code         repository. And like enterprise Docker registry.
    
# For scanning of the images we used anchor and probably within Jenkins plugin.

# Helm charts: 


    Yes, basically I use like Helm charts. As part of like deployment techniques and 
    parallely I use the Ansible in order to automate that task for setting up a Kubernetes cluster deployments
 
    Managed Kubernetes charts using Helm, and Created reproducible builds of the Kubernetes applications, managed Kubernetes deployment and service files and           managed releases of Helm packages.
 
    Extensively worked with Scheduling, deploying, managing container replicas onto a node using Kubernetes and experienced in creating Kubernetes clusters work         with Helm charts running on the same cluster resources.
    
    Proficient knowledge with Helm charts to manage and release of helm packages.
    
# Helm Use cases:
    
    Think that you have a couple squads that develop microservice for some company. 
    If you can make a Chart that works for most of them, the deploy of each  microservices would differ only by the image and the resources required. 
    This way you get an standardized deployment and easier to all developers.

    Another use case is deploying applications which requires a lot of moving parts. 
    For example, if you want to deploy a Grafana server on Kubernetes you're probably going to need at least a Deployment and a Configmap, 
    then you would need a service that matches this deployment. And if you want to expose it to the internet you need an ingress too.

    One relatively simple application, would require 4 different YAMLs that you would to manually configure and make sure everything is correct
    instead you could do a simple helm install and reuse the configuration that someone has already made, 
    sometimes even the company who created the Application.
    
    
# No, unless the the container has been terminated or we have destroyed the container, but the data will be there is no loss of the data if you just exit that
    
    

    


