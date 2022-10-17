# Continuous Integration Pipeline For Tooling Website


## Table of Contents
- Introduction
    - What is Jenkins?
    - Why Jenkins?
- Prerequisites
- Installation
- Configure Jenkins to copy files to the NFS server via ssh

### Introduction
The previous projects allow us to add new web servers to our project and set up a load balancer to distribute the traffic between them. However, we still need to manually copy the files to the web servers. This project would allow us to automate the task of configuring multiple web servers.

In the world of software development, agility and speed of software solutions delivery are key factors. To achieve this, we need to automate as much as possible, as that would guarantee fast and repeatable deployments. In this project, we will start by automating part of our routine tasks with a free and open-source tool called Jenkins.
This process is very much wrapped around the concept of <b>Continous Integration (CI)</b>.
CI is a software development practice where developers integrate code into a shared repository frequently, preferably several times a day. Each integration can then be verified by an automated build and automated tests. CD is a software release process that uses automated testing to validate if changes to a codebase are correct and stable for immediate autonomous deployment to a production environment.


#### What is Jenkins?
Jenkins is a self-contained, open-source automation server that can be used to automate all sorts of tasks related to building, testing, and delivering or deploying software. Jenkins is written in Java and it is an open-source tool. Jenkins is a continuous integration tool. It is used to build and test your software projects continuously making it easier for developers to integrate changes to the project, and making it easier for users to obtain a fresh build. It also allows you to continuously deliver your software by integrating with a large number of testing and deployment technologies.

Jenkins can be installed through native system packages, Docker, or it can also run standalone on any machine with the java runtime environment installed.

#### Why Jenkins?
Jenkins is a continuous integration tool. It makes it easier for thousands of developers around the world to reliably build, test, and deploy their software. As it helps keep track of the version control system and initiate and monitor a build system if there are any changes.


