---
title: "Build Event Driven Dashboard With AWS API Gateway v2 Websockets"
date: 2021-04-02T00:41:14+11:00
draft: true
toc: true
tags:
    - AWS
    - Websockets
    - Event Driven Architecture
---

## Introduction

This post is going to take you through Websockets in the AWS API Gateway V2 Service
and building a Event Driven Dashboard to show data changes in real-time.

### What are Websockets?

Websockets are a type of persistent connection between a Client and a Server that allow bi-directional data flow between the two parties.
These are useful in scenarios where the client might need to be notified of changes on the server side in real time without the need to
send a request, the server in this case can asynchronously send data to the client via the existing connection.

Unlike the `http` and `https` scheme that are normally associated with the REST API Endpoint call implementation, WebSockets use the scheme
of `ws (for standard connections)` or `wss (for secure connections)`. So an example websocket service endpoint might look something like
`wss://websocket.service`.

For a more detailed overview of the Websocket Protocol, check this [blog](https://sookocheff.com/post/networking/how-do-websockets-work/#:~:text=A%20WebSocket%20is%20a%20persistent,between%20a%20client%20and%20server.).

### Getting started with AWS API Gateway v2

#### What is AWS API Gateway V2?

AWS API Gateway V2 is the next iteration of the [API Gateway Service](https://aws.amazon.com/api-gateway/) from AWS (Amazon Web Services)
How does is differ from v1?

### Making Websockets with AWS API Gateway v2

How does API Gateway

### Creating an Event Driven Dashboard

### Source Code / References

* [Crypto Dashboard Source Code (GitHub)](https://github.com/jwillanderson)
