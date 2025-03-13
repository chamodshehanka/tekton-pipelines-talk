# Chat Loop Back Off Ep. 50 - Tekton Pipelines 

Origin:
Tekton started as a project within Google's Knative initiative, focused on building cloud-native CI/CD systems. 

Open Source:
Tekton was later donated to the Continuous Delivery Foundation (CDF) in early 2019, becoming an open-source project. 

Community Driven:
Tekton is now a collaborative project, with contributions from Google, other organizations, and a growing community. 

Google's Involvement:
Google continues to actively participate in the project, including staffing a dedicated team and participating in the governing board. 

CI/CD Framework:
Tekton is a framework for building and running CI/CD systems, enabling developers to work seamlessly with both cloud providers and on-premise infrastructures. 

Kubernetes Native:
Tekton leverages Kubernetes resources and concepts to define and manage CI/CD pipelines. 

Ref: https://opensource.googleblog.com/2020/05/the-tekton-pipelines-beta-release.html

Explore Tekton Documentation: https://tekton.dev/

## How to Guide

https://tekton.dev/docs/how-to-guides/clone-repository/

## Prerequisites
To follow this How-to you must have a Kubernetes cluster up and running and kubectl properly configured to issue commands to your cluster.

Install Tekton Pipelines:

```shell
kubectl apply --filename \
https://storage.googleapis.com/tekton-releases/pipeline/latest/release.yaml
```
See the Pipelines installation documentation for other installation options.

Install the [Tekton CLI](https://tekton.dev/docs/cli/), `tkn`, on your machine.

## Install Tekton Dashboard

https://tekton.dev/docs/dashboard/install/

```shell
tkn dashboard --port-forward
```