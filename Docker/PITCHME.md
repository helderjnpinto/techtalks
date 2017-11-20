# Docker stuff

## Tech talk @Yarilabs
 ![Docker ](https://upload.wikimedia.org/wikipedia/commons/thumb/4/4e/Docker_(container_engine)_logo.svg/250px-Docker_(container_engine)_logo.svg.png) 

---

### Helder Pinto - @helderjnpinto(github)

helder@yarilabs.com
hp_ctt@hotmail.com

---


## Sobre a talk

* About Docker
* Docker vs VM
* Working with Docker Containers
* Working with Docker Images
* Network and Data Management for Containers
* Docker Orchestration with compose
* Sharing Data with Containers
* Running Services in a Container

---

# About Docker 
 ![Docker ](https://upload.wikimedia.org/wikipedia/commons/thumb/4/4e/Docker_(container_engine)_logo.svg/250px-Docker_(container_engine)_logo.svg.png) 
 
* Original author:
    - Solomon Hykes.
* Original product owner: 
    - dotCloud.
        "(was a "Paas" `Platform as a service` company owned by cloudControl)"

* Written in: 
    - GO lang.

* Platforms: 
   - Linux:  x86-64, ARM (experimental)
   - Windows: Windows with Hyper-V capabilities

+++

# Docker 

- Docker is the most popular container software

    - An alternative to Docker is rkt (Rocket)

## Docker Engine

- The Docker runtime

- Software to make run docker images

## Docker Hub

- Online service to **store** and **fetch** docker images

- Also allows you **build docker** images online

## Docker Store

- Online Service with Trusted and Enterprise Ready Containers, Plugins, and Docker Editions

+++ 

# Docker Benefits

- **Isolation** you ship a binary with all the dependencies.
    - no more it works on my machine, but not in production.

- Close **parity** between dev, QA and prod env.

- Docker makes development teams able to ship faster.

- Run the same docker image, unchanged, on laptops, data center VMs and Cloud providers.

- Docker uses Linux Containers (a kernel feature) for OS level isolation


---

# Docker vs VM
 
 <div style="text-align: center;" >
 <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/4e/Docker_(container_engine)_logo.svg/250px-Docker_(container_engine)_logo.svg.png" alt="vms" style="width: 150px;"/>
 <span>  - VS - <span> 
 <img src="https://helio.loureiro.eng.br/images/stories/2017/VirtualBox_logo.png" alt="vms" style="width: 50px;"/>
 </div>

![Docker ](https://i.stack.imgur.com/pG94I.png) 

+++

#  

---
* Working with Docker Containers
* Working with Docker Images
* Network and Data Management for Containers
* Docker Orchestration with compose
* Sharing Data with Containers
* Running Services in a Container

