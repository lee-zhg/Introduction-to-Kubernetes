# Introduction to Kubernetes

<img src="https://kubernetes.io/images/favicon.png" width="200">


## Workshop Flow

### Prerequisites

1. Provision Kubernetes Cluster

    If you do not have access to a kubernetes environment, follow the instructions here to get one. It may take 15-30 minutes to provision a Kubernetes cluster. So, create the cluster as your first task in the session. 

    If you have access to a kubernetes environment, you may skip these steps.

    [Follow the lab instructions here](Lab0a)

1. CLI pre-requisites

    Complete these steps to install required CLI tools.

    [Follow the lab instructions here](Lab0b)

1. Connecting to your Kubernetes cluster

    Complete these steps to connect to your Kubernetes cluster.

    [Follow the lab instructions here](Lab0c)


### Lab 1 - Deploying application via CLI tool

This lab walks through creating and deploying a simple "guestbook" app written in Go as a net/http Server and accessing it.

[Follow the lab instructions here](Lab1)

### Lab 2 - Scaling and updating deployment via CLI tool

Builds on lab 1 to expand to a more resilient setup which can survive having containers fail and recover. Lab 2 will also walk through basic services you need to get started with Kubernetes and the IBM Cloud Container Service.

[Follow the lab instructions here](Lab2)

### Lab 3 - Deploying application via configuration file

Introduces configuration files used to describe deployments and services and their use to deploy an application.

[Follow the lab instructions here](Lab3)