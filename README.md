# CI/CD Pipeline Scaffolder

![Node.js](https://img.shields.io/badge/Node.js-18-green)
![Jenkins](https://img.shields.io/badge/Jenkins-2.0-red)
![SonarQube](https://img.shields.io/badge/SonarQube-Quality-blue)

A CLI tool for automating the creation of secure-by-design CI/CD pipelines.

## Objective
Accelerate project bootstrapping by generating standardized `Jenkinsfile` templates with built-in security gates (SAST/DAST).

## Features
- **Shift-Left Security**: Pre-configured SonarQube steps.
- **Template Engine**: Dynamic pipeline generation based on project type (Java, Node, Python).
- **Infrastructure as Code**: Generates accompanying Docker/K8s manifests.
