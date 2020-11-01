# What you did with docker?

    1. Involved in using of Docker to build images using maven and Experienced in deploying Micro Services to App Servers using Jenlins pipelines.
    2. Used Jenkins and pipelines to drive all micro services builds out to the Docker-registry and then deployed to Kubernetes, Created Pods and managed using            Kubernetes.
    3. Initiated Microservices application through Docker and Kubernetes cluster formation for scalability of the application. Deployed Microservices with Ansible          Playbook in Docker containers
    4. Automated Compute Engine and Docker Image Builds with Jenkins and Kubernetes, created private cloud using Kubernetes that supports DEV, TEST and PROD                environments. 
    5. Worked on Integrating Docker container-based test infrastructure to Jenkins CI test flow and set up build environment integrating with Git and JIRA to              trigger builds using WebHooks and Slave Machines.
    6. Extensively worked on Docker containers by deploying and maintaining production environment using AWS EC2 instances. Worked on infrastructure with Docker            containerization using docker weave.
    7. Automated the installation of Kubernetes single node environment on a Jenkins slave node using Kubeadm setup scripts. Implemented a Continuous Delivery (CD)        pipeline with Docker, Jenkins and GitHub and AWS AMI's. 
    8. Used Kubernetes to deploy scale, load balance and manage Docker containers with multiple namespace ids.

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
    So in order to create like whenever we are taking the source code compiling it then automatically pushing that into a Docker image. I mean to select creating an     image out of it. So then usually we run the test, make sure that image that has the same functionality that we are looking for. So once the test, test has been     successfully done. We ship them and store that it remote repository, like j frog artifactory, then we can use containers, apply that in the pod definitions         within Kubernetes, for all our micro services. So basically using built in templates for pod definitions for our service definitions for the deployments. We are     being to automate all the deployments such that we have zero downtime. "And we are also implementing advanced deployment techniques like blue green Canary."
 
    
# keywords we use in order to build a Docker file:
    So in order to build our Docker file will be specified different keywords like from will be specify where we are taking the base image and run command, we use       for initialize anythings and expose command we use for expose the source port and the target port and cmd. Basically we use that in order to initialize anything     at building up the image entry point is time when we launched the image or the container.
    
# Docker build and Docker run ( Storing base images)
    using a "Docker hub" or "Docker registry", in order to store our "base images".
    Once the build and test is successfully done, we store our like artifactory within like Nexus or j frog. But the base images we will store that source code         repository. And like enterprise Docker registry.
    
# For scanning of the images are used like anchor and probably within Jenkins plugin.

# Helm charts: 
    Yes, basically I use like Helm charts. As part of like deployment techniques I use like cops on top of AWS, and parallely I use the Ansible in order to automate     that task for setting up a Kubernetes cluster deployments
 
    Managed Kubernetes charts using Helm, and Created reproducible builds of the Kubernetes applications, managed Kubernetes deployment and service files and           managed releases of Helm packages.
 
    Extensively worked with Scheduling, deploying, managing container replicas onto a node using Kubernetes and experienced in creating Kubernetes clusters work         with Helm charts running on the same cluster resources.
    Proficient knowledge with Helm charts to manage and release of helm packages.
    
    
    

    


