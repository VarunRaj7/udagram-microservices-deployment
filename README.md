## Refactoring Monolith Udagram as Microserivces

The Udagram has the following components which are then turned as microservices.

    1. Frontend
    2. Backend
        a. /feed api
        b. /users api

These components are shown in the below picture with their dependencies:

![dependency-graph](https://github.com/VarunRaj7/udagram-microservices-deployment/blob/master/img/dependency-graph.png)

The final microservices design:

![microservices-design](https://github.com/VarunRaj7/udagram-microservices-deployment/blob/master/img/microservice-design.png)

The screenshots of docker images and travis builds:

[ScreenShots](https://github.com/VarunRaj7/udagram-microservices-deployment/tree/master/img)

The code for the respective docker images of pods can be found:

1. [Frontend](https://github.com/VarunRaj7/udagram-frontend)

2. Backend:
   a. [feed](https://github.com/VarunRaj7/udagram-feed-api)
   b. [users](https://github.com/VarunRaj7/udagram-users-api)

3. [Reverse-Proxy](https://github.com/VarunRaj7/udagram-reverse-proxy)
