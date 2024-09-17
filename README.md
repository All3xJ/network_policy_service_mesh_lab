# Kubernetes Network Policies and Service Meshes Lab

This repository contains materials for a hands-on lab exploring Kubernetes Network Policies and Service Meshes. The lab is designed to provide practical experience with these essential technologies for improving network security and service communication in Kubernetes environments.

## Table of Contents

1. [Introduction](#introduction)
2. [Lab Environment Setup](#lab-environment-setup)
3. [Part 1: Kubernetes Network Policies](#part-1-kubernetes-network-policies)
4. [Part 2: Service Mesh with Bookinfo Application](#part-2-service-mesh-with-bookinfo-application)
5. [Comparison of Network Policies and Service Meshes](#comparison-of-network-policies-and-service-meshes)
6. [Troubleshooting](#troubleshooting)

## Introduction

This lab aims to provide hands-on experience with:

- Implementing and testing Kubernetes Network Policies to control pod communication
- Deploying and configuring Istio as a Service Mesh
- Applying traffic management using Istio's Virtual Services and Destination Rules
- Implementing mutual TLS (mTLS) between services
- Using observability tools like Kiali, Grafana, and Jaeger in Istio
- Understanding the different use cases for Network Policies and Service Meshes

## Lab Environment Setup

The lab environment requires:

- Docker
- Minikube with Cilium CNI
- Kubectl
- Istio

Detailed setup instructions are provided in the lab document.

## Part 1: Kubernetes Network Policies

This section covers:

- Default behavior of pod-to-pod communication
- Creating basic ingress deny-all policies
- Allowing ingress traffic from specific pods
- Implementing egress policies

## Part 2: Service Mesh with Bookinfo Application

This section explores:

- Installing and configuring Istio
- Deploying the Bookinfo sample application
- Implementing traffic management with Virtual Services and Destination Rules
- Enabling mutual TLS (mTLS) authentication
- Using observability tools (Kiali, Grafana, Jaeger)

## Comparison of Network Policies and Service Meshes

The lab provides a comparison of Network Policies and Service Meshes, discussing their pros and cons, and best practices for their use.

## Troubleshooting

The lab includes a section on troubleshooting, providing useful commands and strategies for diagnosing issues in Kubernetes, Network Policies, and Service Meshes.

## Resources

- Lab document (PDF)
- YAML files for various configurations used in the lab

## Note

This lab is designed for educational purposes and may require significant system resources, particularly when running Istio. It's recommended to have at least 16GB of RAM for optimal performance.
