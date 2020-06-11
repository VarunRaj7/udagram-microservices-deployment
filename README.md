## Refactoring Monolith Udagram as Microserivces

The Udagram has the following components which are then turned as microservices.

    1. Frontend
    2. Backend
        a. /feed api
        b. /users api

These components are shown in the below picture with their dependencies:

<img align="center" src="https://github.com/VarunRaj7/udagram-microservices-deployment/blob/master/img/dependency-graph.png" width="400" height="400" >

<!-- ![dependency-graph]( = 50x50) -->

The final microservices design:

<img align="center" src="https://github.com/VarunRaj7/udagram-microservices-deployment/blob/master/img/microservice-design.png" width="800" height="500">

<!-- ![microservices-design]( = 150x100){ width=100px height=100px} -->

The screenshots of docker images and travis builds:

[ScreenShots](https://github.com/VarunRaj7/udagram-microservices-deployment/tree/master/img)

The code for the respective docker images of pods can be found:

1. [Frontend](https://github.com/VarunRaj7/udagram-frontend)

2. Backend:
   a. [feed](https://github.com/VarunRaj7/udagram-feed-api)
   b. [users](https://github.com/VarunRaj7/udagram-users-api)

3. [Reverse-Proxy](https://github.com/VarunRaj7/udagram-reverse-proxy)
