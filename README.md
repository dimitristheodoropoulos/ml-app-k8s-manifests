ML App Kubernetes Manifests

This repository contains the Kubernetes manifests for the ml-app machine learning application. It is designed to be used with a GitOps tool like ArgoCD for automated deployment.
📁 Repository Structure

    base/: Contains the core, reusable Kubernetes manifest files (deployment.yaml and service.yaml).

    production/: Contains the Kustomize overlay that customizes the base manifests for the production environment.

🔗 Part of a Larger Project

This repository is a component of the Linux Infrastructure Automation Lab project, a personal home lab that demonstrates an end-to-end DevOps and MLOps pipeline.