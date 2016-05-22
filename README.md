Hotsuite Microservice Challenge
================================


**Problem**: build a system using Graph DB to represent microservice dependency graph.
Imagine 100s of microservices calling each other on different API endpoints
using REST, how would you know which service depends on another? how often API
calls are being made from one service to another? Does one service always call
all endpoints of another service, or usually just one or two etc…?


## Components

The proposed solution consists of three repositories. One for the API server, one for data visualization and another one as a library to allow easy integration with WSGI applications.

Inside each one them there is a readme explaining its functionality in details.

* [microdot-api](https://github.com/hootsuite-ms-challenge/microdots-api)
* [microdot-portal](https://github.com/hootsuite-ms-challenge/microdots-portal)
* [microdot-python](https://github.com/hootsuite-ms-challenge/microdots-python)
