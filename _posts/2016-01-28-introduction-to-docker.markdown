---
layout: post
title:  "Introduction to Docker"
date:   2016-01-28 17:50:49 -0700
categories: docker
---


**Introduction to Docker**

Docker is a software container just like a virtual image that can be used to isolate and integrate different components in day to day Software Development, Software Testing and Software Deployment/DevOps. As software application are getting complex day by day, the significance for a developer/tester to have his own isolated environment to play and mess around with has become even more crucial. Then again, the components that your application might consist may not be an open source component which then might require licences(i.e money). Docker solves this problem by providing a whole lot of software components in the form of docker objects for you to run locally. 

**Docker Hub**

Docker stores all the docker objects in the cloud called as 'Docker Hub'. The user can then pull whatever Docker object he wants to use. Once pulled, the you can start the VM running that docker object. 

**Use Case**

To keep this article short, I can directly jump to a use case that would better explain the purpose of Docker. Suppose, you are working on creating an application that uses Oracle as a database. Traditionally, you would have a shared Oracle server that you would be using across the team. With Docker, you can pull an Oracle Docker object and start the VM to run an Oracle instance locally. This gives you utmost freedom to tear down the instance whenever you want and mess around with the data without hampering the development time of someone else. 

**Alternative - AWS**