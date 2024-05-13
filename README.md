Example how to share pipeline definitions between namespaces.

# Introduction

In this example, we have a user who has some pipeline definition in a namespace and he wants to share it between namespaces. 

![Architecture](images/architecture.png)

# Configuration

For this example, I'm using:
* OpenShift 4.15
* Openshift Pipelines 1.14.4 base on tekton 0.56.4

## Users

* user1: admin in namespace pipelines
* user2: admin in namespace app

# Producedure

## Create the namespace

