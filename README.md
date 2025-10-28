# Kubernetes & EKS with Pulumi
October 25, 2025

<p align="center">
<img width="200" height="200" alt="Image" src="https://github.com/user-attachments/assets/2f056229-dcef-474e-b046-fc931930161d" />
</p>

## Project Description

The Zephyr Archaeotech Emporium Online Store is a sample e-commerce application used in Pulumi’s Zephyr blog series to demonstrate best practices for managing infrastructure and applications. It’s based on an existing retail store sample app, but has been adapted for this workshop.

This workshop provides hands-on experience with infrastructure-as-code and application deployment, while teaching how to manage configuration, secrets, and deployment strategies across different environments. It also covers how to integrate local development workflows with CI/CD pipelines and cloud infrastructure for a seamless, end-to-end deployment process.

Link to the tutorial followed: [freeCodeCamp](https://www.youtube.com/watch?v=hK8wf18SasY&t=767s)

## Key Points

**1. Deployment Options**

***- Pulumi:*** You can deploy both the app and its supporting infrastructure through Pulumi. There are instructions for local testing as well as full deployments.

***- Docker Compose:*** For local development or quick testing, the app can run locally using Docker Compose.

***- Kubernetes:*** For more advanced deployment scenarios, the app can be deployed to a Kubernetes cluster using the provided manifests.

**2. Workflow for the Workshop**
- Start by running the app locally (Docker Compose) to test changes quickly.
- Use Pulumi to deploy infrastructure and the application for a more production-like setup.
- Optionally, deploy to Kubernetes to explore container orchestration and scaling.

## Other References

- [Pulumi's Zephyr series of blog posts](https://www.pulumi.com/blog/tag/zephyr/)
- [Source repository](https://github.com/aws-containers/retail-store-sample-app)
- [Instructions for using Pulumi](infra/README.md)
- [README](develop/pulumi/README.md)
