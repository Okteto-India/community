---
layout: post
title:  "Introduction to Okteto"
author: sangam 
categories: [K8s, okteto]
tags: [ Introduction  ]
image: assets/images/Intro-okteto.png
rating: 4.5
---

# Introduction to okteto 


- okteto is tool for all kubernetes Developer to build , run , debug there application without depending on heavy load on local machine . still you can develope application quick and faster . 

- you don't need anything installed on machine rather then okteto cli . remember when we use docker on your machine its take to much memory and other resources . and its very painful cycle to build docker containers again and again locally . but okteto will provide remote developement using power of okteto cloud . 

- Okteto provide Clean and Easy CLi tool without much understanding complexity of docker or kubernetes clustering and swarm .

# How Okteto Works Under the hood 

![](https://raw.githubusercontent.com/sangam14/ContainerLabs/master/img/how-its-work-okteto.png)

- okteto use concept of syncthing . its continuous file synchronization program . which workes in real time to synchronizes file between two or more computers .
   
- how this will help, well we have discussed that its don't need any kind of addition installation to run your kubernetes application because of syncthiing its will become much easier to run application .

- but in case of okteto its just not only synchronize file . but thing this way you have used docker build or docker container run kind of command to run or rebuild docker images thats where okteto is doing things more smarter . okteto will detect `okteto.yml` file when you enter okteto up . or you can deploy any kind of kubernetes application easly 
- Okteto Cloud is application catlog where you can check logs or even you can directly just copy the github URL or helm Release link and thats it within 2 min your application up and running even its provide some of pre-integrated application easy to edit , redeploy and monitor .

# Why Okteto 

- well now you know how okteto works or little overview but real question is why we need okteto ? right 
- lets check it out some of the advantage of using okteto 
    - Fast inner loop development
    - Production-like development environment
    - Replicability
    - Unlimited resources
    - Deployment independent
    - Works anywhere
