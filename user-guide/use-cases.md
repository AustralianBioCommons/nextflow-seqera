---
title: Use cases the service
contributors: [Ziad Al-Bkhetan]
description: Organisation-level usage patterns for the Australian Nextflow Seqera Service.
toc: false
---

## Shared and private workspace model 

Organisations typically maintain a combination of shared and private workspaces. Shared workspaces contain resources that should be available across the entire organisation, including standard workflows and compute environments.

Individual research groups maintain private workspaces where they perform their own analyses and manage project-specific resources while still benefiting from the organisation-wide shared resources.

## Automated workspace provisioning

Organisations with a centralised support team automate the creation of new workspaces using the Seqera CLI. When a new research group is onboarded, the support team automatically: Creates the workspace. Configures standard settings. Populates the workspace with the organisation's approved compute environments. Adds common workflows and other shared resources where appropriate. This enables rapid, consistent onboarding across many research groups.

## Simplified HPC access using Open OnDemand

Some organisations integrate Open OnDemand with the Seqera service. Open OnDemand provides researchers with a simple interface for launching the Tower Agent on HPC systems.

## Running workflows across diverse compute infrastructure

Organisations successfully use the Seqera service with a wide range of compute backends, including:  Local HPC clusters using Slurm and PBS Pro, Amazon Web Services (AWS), Microsoft Azure, Google Cloud Platform (GCP), and Google Kubernetes Engine (GKE).

## Workflow and platform automation using the Seqera API

Users can utilise the Seqera API to automate routine platform operations. Typical examples include: Creating or managing workspaces. Managing users and permissions. Automating workflow execution. Integrating Seqera into existing institutional systems.

## Using Seqera as the backend for custom platforms

Users can use a dedicated Seqera workspace as the execution backend for another platform or web application. In this model: Users interact only with the external front-end. The front-end communicates with Seqera through the Seqera API. Seqera manages workflow execution, monitoring, and compute resources behind the scenes. This allows institutions to build domain-specific portals while leveraging Seqera's workflow orchestration capabilities.
