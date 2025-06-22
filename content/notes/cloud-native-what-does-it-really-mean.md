+++
date = '2025-06-22'
draft = false
title = '[Cloud Native Fundamental] What Does “Cloud Native” Really Mean? ☁️'
tags = ['cloud', 'learning', 'development']
showTags = true
+++

## Introduction

Since landing my first job as a software engineer, I’ve realised enterprise applications are vastly different from university coursework projects. Those academic projects were short-lived—built to meet assignment goals and then abandoned. I never had to consider scaling, monitoring, or production because no one was using them. In contrast, enterprise apps are built to deliver business value. They must be scalable, observable, resilient, and easy to update continuously.

These concepts were new to me when I started working, as I hadn’t encountered them before. Luckily, I came across the term **Cloud Native** and picked up [Cloud Native in Action with Spring Boot and Kubernetes](https://www.manning.com/books/cloud-native-spring-in-action). It’s a perfect book for me since those are the technologies I’m working with. After finishing the fundamentals section, I wanted to collect my understanding and share what I’ve learned. This blog post is both a record of my key takeaways.

In this chapter, this blog covers the foundational concepts, including **what cloud native really means**, along with key definitions related to **cloud computing**—specifically its **deployment models** and **service models**.

## What Does “Cloud Native” Really Mean?

Before terms like microservices, Docker, or Kubernetes became common, Paul Fremantle defined a cloud-native application as

> “an application and middleware designed to work well in a cloud environment.” 
 
This means building applications specifically for the cloud—designed to fully leverage its scalability, elasticity, and automation—instead of simply migrating traditional apps to cloud servers.

The Cloud Native Computing Foundation (CNCF) expands on this by emphasising that cloud native technologies enable organisations to build scalable, resilient, and manageable applications in dynamic environments such as public, private, or hybrid clouds. Key techniques include containers, microservices, service meshes, immutable infrastructure, and declarative APIs.

## So What Is Cloud Then ?

To understand cloud-native applications, it’s important to first understand the context of the cloud itself, as these applications are specifically designed to work well in cloud environments.

The National Institute of Standards and Technology (NIST) defines cloud computing as 

> A model that enables convenient, on-demand access to a shared pool of configurable resources—such as servers, storage, and applications—that can be quickly provisioned and released with minimal effort or provider interaction.

The cloud provider manages the underlying infrastructure, so consumers don’t need to worry about physical resources like machines or networks. Companies moving to the cloud can access computing resources over a network (typically the internet) via APIs, allowing them to provision and scale resources on-demand and self-service. They only pay for the resources they actually use, making it a flexible and cost-efficient model.

No rule has been defined for where cloud infrastructure must reside or who manages it.

### Cloud Deployment Models

Cloud services can be delivered through several deployment models: private, public and hybrid cloud.

* **Private cloud** is dedicated to a single organisation. It can be managed in-house or by a third party and hosted on-premises or externally. It’s ideal for organisations handling sensitive data or needing strict compliance.
* **Public cloud** is open for public use, owned and operated by providers like AWS, Azure, or Google Cloud and hosted on their infrastructure.
* **Hybrid cloud** combines two or more distinct cloud environments (private or public), working together as a unified system.

### Cloud Computing Service Models

With the cloud environment in mind, it's also important to understand the different service models it offers. These define how much responsibility is managed by the provider versus the user. The key models are:

* **IaaS (Infrastructure as a Service):**
Offers basic computing resources like virtual machines, storage, and networking. Users manage the OS and apps.
Examples: AWS EC2, Azure VMs, Google Compute Engine.
* **CaaS (Container as a Service):**
Allows users to deploy and manage containers without handling underlying infrastructure.
Examples: Kubernetes services like Amazon EKS, Azure AKS, Google GKE.
* **PaaS (Platform as a Service):**
Provides a full development and deployment platform with runtime, middleware, and built-in services.
Examples: Heroku, Google App Engine, AWS Elastic Beanstalk, Azure App Service.
* **FaaS (Function as a Service):**
Serverless model where developers write functions triggered by events; infrastructure is fully abstracted.
Examples: AWS Lambda, Azure Functions, Google Cloud Functions.
* **SaaS (Software as a Service):**
Fully managed applications accessed by end users via web or mobile interfaces.Examples: GitHub, Microsoft 365, Proton Mail.

## Conclusion

Cloud native applications are distributed systems built specifically to run in the cloud, leveraging its scalable and flexible infrastructure. The cloud provides computing, storage, and networking resources as a pay-as-you-go commodity. These services are offered at various levels of abstraction—from infrastructure to software—enabling organizations to choose the right model for their needs.
