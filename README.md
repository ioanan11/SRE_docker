# Containerisation with Docker
## Microservice Architecture (Microservices)
### What are Microservices?

Microservice architecture is a distinctive method of developing software systems that tries to focus on building single-function modules with well-defined interfaces and operations. The trend has grown popular in recent years as Enterprises look to become more Agile and move towards a DevOps and continuous testing.

### Microservice vs. Monolithic Architecture

![alt text]()

#### Strengths vs Weaknesses

![alt text]()

#### When to use what?

**A simple application.**  Small applications which do not demand much business logic, superior scalability, and flexibility work better with monolithic architectures.
**A complex and scalable application.** The microservices architecture will make scaling and adding new capabilities to your application much easier. So if you plan to develop a large application with multiple modules and user journeys, a microservice pattern would be the best way to handle it.


## What is Docker?

Docker is an open platform for developing, shipping, and running applications. Docker enables you to separate your applications from your infrastructure so you can deliver software quickly. With Docker, you can manage your infrastructure in the same ways you manage your applications.

### Docker vs. VM

![alt text]()

Docker is **faster to start**, **smaller in size** and **easier to integrate**.

# How to set up Docker

## Step 1: Install Docker 

Access this link for Docker installation: https://docs.docker.com/desktop/windows/install/

**Note** : It may prompt you to install something else. Follow those steps
**Note 2** : You may need to restart your machine

## Step 2: Create Docker account

Access this link to create your Docker hub account if you don't have one already: https://hub.docker.com/ 

## Step 3: Allow WSL integration

After installation is completed, open Docker.

```
Settings > Resources > WSL Integration
```

Make sure the box is ticked. 

![alt text]()

## Step 4: Use Docker!

Now you can use docker. Let's run some commands

```
docker pull hello-world
docker run hello-world
```
