# Vprofile Project: Dockerized Java Application with Tomcat, MySQL, and Nginx

## Overview

The **Vprofile** project demonstrates how to deploy a Java-based web application using Docker. This setup includes the containerization of three main components: a **Tomcat** server for hosting the Java application, a **MySQL** database for data management, and **Nginx** as a reverse proxy server. Docker enables the separation of each service into its own container, providing a scalable and modular environment suitable for both development and production purposes.

## Technologies Used

- **Docker**: Containerization platform to build, ship, and run the application in isolated environments.
- **Java**: Programming language used for the backend of the web application.
- **Tomcat**: A Java-based application server that runs the Java web application.
- **MySQL**: A relational database management system used for managing the application's data.
- **Nginx**: A high-performance web server and reverse proxy that forwards HTTP requests to the Tomcat server.
- **RabbitMQ**: A message broker used for asynchronous communication between different components of the application.
- **Memcache**: A distributed memory caching system used to speed up database-driven applications by caching frequently accessed data.

## Project Structure

The project consists of three primary components, each defined by its own Dockerfile:

1. **Tomcat (Application)** - Serves the Java-based web application.
2. **MySQL (Database)** - Manages the application’s data storage.
3. **Nginx (Web Server)** - Acts as a reverse proxy, forwarding client requests to the Tomcat server.
4. **RabbitMQ (Message Broker)** - Handles message queuing for asynchronous communication.
5. **Memcache (Caching)** - Provides memory caching for performance improvement.

## Setup and Installation

To run this project, you’ll need **Docker** installed on your machine. If Docker is not yet installed, please refer to the official [Docker documentation](https://docs.docker.com/get-docker/) for installation instructions.

### Clone the Repository

First, clone the repository to your local machine:

```bash
git clone https://github.com/puremike/vprofile-project.git
cd vprofile-project
```
