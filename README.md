## Refactoring Monolith Udagram as Microserivces

The Udagram has the following components which are then turned as microservices.

    1. Frontend
    2. Backend
        a. /feed api
        b. /users api

These components are shown in the below picture with their dependencies:

    ![dependency-graph]()

The final microservices design:
  
 ![microservices-design]()

The screenshots of docker images and travis builds:
  
 []()

The code for the respective docker images of pods can be found:

    1. Frontend:

    2. Backend:
        a. /feed:
        b. /users:

    3. Reverse-Proxy:
