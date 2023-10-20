# The Representational State Transfer (REST) Architecture

**By Ayush**
**Date: October 20, 2023**

## Abstract

The Representational State Transfer (REST) architecture is a widely adopted architectural style for designing networked applications. This paper will give precise knowledge about REST architecture.

## 1. Introduction

REST , or REpresentational State Transfer, is an architectural style for providing standards between computer systems on the web, making it easier for systems to communicate with each other.

## 2. Principles of REST

### 2.1. Statelessness

In stateless architecture server stores no information about client's session states.
But, only servers the request for client.

### 2.2. Resources(data)

In REST, resources are central to the design. Resources are entities that can be identified and manipulated using a URI (Uniform Resource Identifier). Resources are manipulated through standard HTTP methods, such as GET (read), POST (create), PUT (update), and DELETE (remove).

### 2.3. Representations(data format)

Resources can have multiple representations, such as XML, JSON, or HTML formats. Clients can choose the representation that best suits their needs, and the server provides a standardized way to request different representations for a resource.

### 2.4. Uniform Interface

Different URLs are meant for different data requests based on the methods that the client pass
This includes standard HTTP methods, such as GET, POST, PUT, DELETE, and a common set of status codes. This uniformity simplifies client-server interactions and encourages separation of concerns.
**e.g.**

1. https://restcountries.com/v3.1/alpha/co
2. https://restcountries.com/v3.1/all
   they both give different results

## 3. Practical Applications

REST architecture is widely used in various domains, including web services, cloud computing, and Internet of Things (IoT). Some practical applications include:

### 3.1. Web APIs

Many modern web APIs are built on REST principles. Companies like Twitter, Facebook, and Google provide RESTful APIs to allow developers to access and interact with their services.

### 3.2. IoT

REST is a suitable choice for IoT devices due to its lightweight nature. IoT devices can communicate with cloud services using RESTful APIs to exchange data and instructions.

## References

1. What is REST by [Codecademy](https://www.codecademy.com/article/what-is-rest)
2. Youtube
   1. Stateful vs Stateless Architecture - System Design Basics by [Cloud Advocate](https://www.youtube.com/watch?v=P8D6P-6KVNM)
   2. REST API Master Course by [JR ACADEMY](https://youtube.com/playlist?list=PLqwmiTs6Z6PG9-0JT_Zt_gKCxyshjCwEA&si=Vu2bRpi_6E_AIpZs)
