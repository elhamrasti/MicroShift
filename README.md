Deployment and Optimization of Kubernetes Cluster with MicroShift on RHEL

This repository contains the documentation and implementation details for deploying and optimizing a Kubernetes-based cluster using MicroShift on Red Hat Enterprise Linux (RHEL) 9.5. The project focuses on enabling efficient edge computing solutions in resource-constrained environments by leveraging containerized applications.

Overview

MicroShift, a lightweight version of OpenShift, provides a powerful Kubernetes distribution designed specifically for edge computing. This project demonstrates how to deploy, configure, and manage MicroShift on RHEL, ensuring stability, minimal service disruption, and efficient resource utilization in edge environments.

Key Features

Kubernetes Cluster Deployment: Setting up a Kubernetes cluster using MicroShift on RHEL 9.5.
Edge Computing Optimization: Ensuring minimal latency and maximum performance in edge devices and environments.
System Upgrades: Analysis of the impact of upgrading RHEL and MicroShift, focusing on CPU, memory usage, and pod stability during upgrades.
Objectives

Provide a practical guide for deploying MicroShift in edge environments.
Implement best practices for upgrading RHEL and MicroShift while ensuring pod stability and system continuity.
Offer actionable insights and recommendations for enhancing the reliability and performance of edge computing systems.
Project Structure

Theory: 

Overview of containers, Kubernetes, OpenShift, and MicroShift.
Methods and Material:

Hardware selection and configuration of RHEL 9.5.
Proposed Solution/Implementation: Detailed walkthrough of the MicroShift installation, pod management, and troubleshooting.
Upgrading: Focus on the effects of upgrading RHEL and MicroShift on system resources and pod behavior.
Summary and Conclusions: Key findings and future optimization suggestions.

Requirements

RHEL 9.5 (or compatible version)
MicroShift (latest version)
Docker or Podman (for container management)
Hardware suitable for edge computing (e.g., servers or single-board computers)
Installation

Follow these steps to deploy MicroShift on RHEL 9.5:

Install RHEL 9.5 on your device.
Install and configure MicroShift using the instructions provided in the documentation.
Create and manage Kubernetes pods using the appropriate CLI tools.
Analyze the effects of system upgrades and ensure pod stability.
