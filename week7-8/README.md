# Week 4: Introduction to web development, JavaScript and Git (source version control)


## What will I learn?
We’ll learn about the concept of test automation and know some automation tools in the market and and Git, source version control.
- Web development (Mostly focus on Front-end for this week)
- Source version control for beginners.


## What should I learn on weekend?
- [What’s Front-End](https://www.youtube.com/watch?v=GJ8jidDdWVg) (~15 min watch)
- [What’s Back-End](https://www.youtube.com/watch?v=WwbBOQaM0Zw) (~15 min watch)
- [Introduction to JavaScript] (~120 min tutorial)
- [Git & GitHub Crash Course For Beginners] (~40 min - 1 hour watch)
- [Git tutorial] (~ 60 min tutorial)

## What will we do in Guild?
**End Goal**:
- Write Dockerfiles to containerize our application jar with different java version or runtime.
- Modify our setup to build and push docker images versus deploying jar directly on AWS

**Pre-requisites**:
- Install Docker

**Rough steps**:
- What should be the base image we should use for our spring boot app?
- How do we copy over my compiled jar into the docker container?
- What should be the first command the container should run on startup?
- How do we expose my app running inside the docker container and access the app on my browser?
- How do we view our application logs?
- How do we publish this docker image to a registry so that it is available for use by the EC2 instance?
- Given our app is containerized, what if we want to use a different version of Java? What can we do?
- Let us extend our drawing and trace the route from the Load Balancer we deployed last week to our docker container.

## What if I want to know more!?
1. Deep Dive into Docker: [The Docker Book](https://www.amazon.com/Docker-Book-containerisation-new-virtualization-ebook/dp/B00LRROTI4) - written step-by-step for system administrators, operations staff on
2. [Docker Training](https://success.docker.com/training/) - compilation of self-paced and instructor-led courses offered by Docker
3. [Creating a Simple Docker Base Image](https://docs.docker.com/develop/develop-images/baseimages/)
4. [10+ Top Open-Source Tools for Docker Security](https://techbeacon.com/security/10-top-open-source-tools-docker-security)

---

*Copyright (c) 2018 ThoughtWorks; for individual use for training purposes and not to be distributed or sublicensed without further authorisation by ThoughtWorks.*
