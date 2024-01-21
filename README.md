# Microservices Architecture for Posts and Comments

![Microservices](https://img.shields.io/badge/Microservices-Enabled-brightgreen.svg)
![Node.js](https://img.shields.io/badge/Node.js-v14.0.0-green.svg)
![Express](https://img.shields.io/badge/Express-v4.17.1-blue.svg)
![Docker](https://img.shields.io/badge/Docker-Ready-blue.svg)
![Kubernetes](https://img.shields.io/badge/Kubernetes-Deployed-blue.svg)
![Skaffold](https://img.shields.io/badge/Skaffold-Integrated-orange.svg)

## Overview

This repository presents a microservices-based architecture for managing posts and comments, built with Node.js and Express. The services are containerized using Docker and can be easily deployed and orchestrated with Kubernetes. Skaffold is seamlessly integrated into the development workflow for enhanced automation.

## Features

- **Microservices Architecture:** Decoupled services for posts and comments, promoting scalability and maintainability.
- **Node.js and Express:** Utilizing the popular and efficient Node.js runtime with Express for building robust APIs.
- **Dockerized Services:** Each microservice is containerized with Docker, ensuring consistency across development and deployment environments.
- **Kubernetes Orchestration:** Kubernetes manifests are provided for effortless deployment, scaling, and management of the microservices.
- **Skaffold Integration:** Streamline development with Skaffold, providing automated workflows for continuous development, testing, and deployment.

## How it Works

### Post Server
- Responsible for creating and managing posts.

### Comment Server
- Manages the creation of comments associated with posts.

### Moderation Server
- Ensures moderation of comments based on predefined rules.

### Query Server
- Holds a copy of posts and comments for efficient querying.

### Asynchronous Approach
- Utilizes an event bus for asynchronous communication between microservices.
- Enhances scalability and responsiveness by allowing services to operate independently.
