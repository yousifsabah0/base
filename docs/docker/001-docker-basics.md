# Docker Basics

In this guide we'll learn everything about Docker.

- [What is Docker ?](#what-is-docker)
- [How Docker works ?](#how-docker-works)
- [Which problems Docker solves ?](#which-problems-docker-solves)

## What is Docker ?

Docker is a platform that makes it easy to deploy your applications by separating the application code from the underlying infrastructure. With Docker, you can significantly reduce the time between writing code and deploying it. Docker achieves this by using a concept called "[Containerization](./002-containers.md)".

## How Docker works ?

Docker takes the code you have written and copies it inside a box, this box contains everything your application needs to run, e.g. the code, the libraries (packages), tools, and settings. This allows the application to run consistently and reliably across different environments, regardless of the underlying operating system.

There's 3 key concepts of Docker

1. **Docker Container** / Isolated units that package your application.
2. **Docker Images** / Blueprints that defines how to build the container.
3. **Docker Engine** / The software that builds, runs, and manages your containers.

## Which problems Docker solves?

- **Inconsistent environments** / Traditional applications can be finicky about the environment they run in. Docker ensures consistency by providing a standardized containerized environment.

- **Slow deployments** / Deploying applications can be a slow and error-prone process. Docker allows for faster and more reliable deployments by packaging everything together.

- **Wasted resources** / Virtual machines can be resource-intensive. Containers are lightweight and share the underlying operating system, making them more efficient.
