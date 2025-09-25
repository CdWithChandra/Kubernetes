# Kubernetes Tutorial (K8s) 2025 🚀 Full Course
[![Kubernetes](https://img.shields.io/badge/Kubernetes-v1.34-blue?logo=kubernetes)](https://kubernetes.io/docs/home/) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)  
Subscribe My YouTube Channel [Easy Beginner Tutorials](https://www.youtube.com/@CodeWith_Chandra)  
Unlock the secrets of Kubernetes with easy-to-follow tutorials, real-world projects, and insider tips that elevate your coding journey.

## Table of Contents

1. [What is Kubernetes ](#WhatisKubernetes)
2. [Pods](#Pods)

## 1. What is Kubernetes {#What is Kubernetes}
Kubernetes is an open-source platform designed to automate the deployment, scaling, and management of containerized applications.  
This repository provides ultra-simple Kubernetes YAML examples to get you started with core concepts like Pods, Replicasets and Deployments (for managing Pods and replicas) and Services (for exposing apps). Designed for absolute beginners—no complex features like volumes or secrets. We'll use a basic nginx web server as the backend to demonstrate deployment, scaling, and access.

These examples assume a local Kubernetes cluster (e.g., Minikube).

## Simple Breakdown for Beginners
> [!IMPORTANT]
> Before Kubernetes, tools like Docker let you package apps into containers (self-contained units with code, dependencies, and runtime). But managing hundreds or thousands of these containers manually (starting, stopping, scaling) is chaotic. Kubernetes solves that.

## Why Kubernetes?
> Kubernetes emerges as the go-to solution by acting as an intelligent orchestrator that automates the entire lifecycle of your apps—from deployment and updates to monitoring and recovery.

Kubernetes (K8s) handles self-healing (restarting failed Pods), load balancing, and portability across environments. Perfect for microservices—from small tests to global services (used by Netflix, Spotify, etc.).

- **Scalability**: Handles apps from small tests to massive, global services.
- **Portability**: Runs on any cloud (AWS, GCP, Azure), on-premises, or your laptop (via Minikube).
- **Efficiency**: Optimizes resources, reduces downtime, and simplifies DevOps.
- **Ecosystem**: Integrates with tools like Helm (packaging), Istio (service mesh), and CI/CD pipelines.

For more, see the [official Kubernetes intro](https://kubernetes.io/docs/tutorials/kubernetes-basics/).

## 2. Pods {#Pods}

- **Kubernetes Cluster**: Install [Minikube](https://minikube.sigs.k8s.io/docs/start/) for local testing (`minikube start`).
- **kubectl**: The Kubernetes CLI (comes with Minikube or install via [official docs](https://kubernetes.io/docs/tasks/tools/install-kubectl/)).
- **Docker**: Optional, but helpful for understanding images ( Docker desktop Installed on your local machine )
- Basic terminal knowledge. No prior K8s experience needed! ( macOS )

## Setup Instructions
> [!TIP]
> This video guide will help you [install Kubernetes on your local machine](https://youtu.be/DR736ESFs_U)  

1. Start your cluster:  




