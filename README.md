# Awesome-Infrastructure-As-Code-IaC-Framework

## Top Infrastructure as Code (IaC) Framework Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Declarative Provisioning, Programming-Language IaC & Self-Hosted Frameworks*  

**Last updated: October 2026**



This repository tracks notable **commercial IaC platforms** and **open-source IaC frameworks** that let teams define cloud infrastructure as code — from declarative configuration languages and real programming-language SDKs to Kubernetes-native control planes and serverless deployment frameworks.



**Examples** include AWS Cloud Development Kit (CDK), Terraform Cloud, Pulumi, Crossplane, OpenTofu, Spacelift, env0, Scalr, Serverless Framework, and SST (the category leaders).



**Open-source emphasis**: IaC frameworks are one of the strongest open-source domains. **Terraform** and **OpenTofu** lead as the de facto declarative IaC standards with 44K and 26K+ GitHub stars respectively . **Pulumi** brings real programming languages to IaC with 23K+ stars . **AWS CDK** enables infrastructure definition in TypeScript, Python, Java, C#, and Go with 12K+ stars . **Crossplane** delivers Kubernetes-native cloud resource management . **Serverless Framework** pioneered serverless IaC with 46K+ stars . **SST** brings a modern TypeScript-first framework with 24K+ stars . **Troposphere** offers Python-based CloudFormation generation. **Terragrunt** and **Terramate** orchestrate Terraform at scale . This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



| Product | Description & Key Strengths | Starting Pricing | Free Tier Limits |
| :--- | :--- | :--- | :--- |
| **[Terraform Cloud](https://www.terraform.io/cloud)** | HashiCorp's managed IaC platform featuring remote state, collaboration, policy enforcement, and CI/CD integration. Best for enterprise Terraform governance. | **Essentials:** $0.10 per managed resource / month (pay-as-you-go) | **Free forever:** Up to 500 managed resources, unlimited users, 1 concurrent run. Includes $500 initial HCP credit. |
| **[Pulumi Cloud](https://www.pulumi.com/)** | Managed IaC platform supporting real programming languages (TypeScript, Python, Go, .NET, Java). Best for developer-centric IaC. | **Team:** $0.0005 per credit (~$0.37/resource/month) | **Free edition (Individual):** 1 user, unlimited resources/stacks. **Team Edition:** 150,000 free credits/mo (~200 managed resources for up to 10 users). |
| **[Spacelift](https://spacelift.io/)** | IaC orchestration platform supporting Terraform, OpenTofu, Pulumi, CloudFormation, and Kubernetes. Best for complex multi-IaC workflows. | **Starter+:** $20,000 / year | **Free tier:** Up to 2 users, 1 public worker (concurrency), unlimited runs. 14-day free trial for full feature evaluation (no credit card required). |
| **[env0](https://www.env0.com/)** | IaC automation platform featuring self-service environments with guardrails and AI capabilities. Best for developer self-service. | **Cloud Navigator (Paid):** Quote-based (~$1,500/mo flat starting rate for enterprise plans) | **Free forever:** Up to 250 runs/mo, 30 active environments, 1 deployment concurrency, unlimited users and self-hosted agents. |
| **[Scalr](https://scalr.com/)** | Terraform & OpenTofu automation platform featuring policy enforcement, organizational hierarchy, and cost management. Best for enterprise governance. | **Pro / Usage-based:** $99/month (includes base runs; additional runs at $0.99/run) | **Free forever:** Up to 50 runs/month, unlimited users, workspaces, and managed resources, 5 default concurrent runs. |



## Open-Source GitHub Projects



### Declarative IaC Languages



- **[Terraform](https://github.com/hashicorp/terraform)**  

  **The de facto IaC standard**, BUSL-1.1 licensed with **44,000+ GitHub stars** . **HCL configuration language for any cloud** — AWS, Azure, GCP, and 3,000+ providers . **The reference for infrastructure provisioning** . **Best for multi-cloud infrastructure as code** .



- **[OpenTofu](https://github.com/opentofu/opentofu)**  

  **Open-source Terraform fork**, MPL-2.0 licensed with **26,000+ GitHub stars** . **Community-driven under Linux Foundation** — no BSL concerns . **Drop-in replacement for Terraform** . **Best for organizations wanting open governance** .



- **[AWS CloudFormation](https://github.com/aws-cloudformation/cfn-lint)**  

  **AWS's native IaC service** — declarative YAML/JSON templates for AWS resource provisioning . **cfn-lint** validates CloudFormation templates against best practices . **Best for AWS-centric organizations** .



- **[Troposphere](https://github.com/cloudtools/troposphere)**  

  **Python library for generating AWS CloudFormation templates**, BSD-2-Clause licensed . **Write CloudFormation in Python** — full IDE support, loops, conditionals, and reusable functions . **Provides well-documented, type-safe API** for every CloudFormation resource . **Best for Python developers using CloudFormation** .



### Programming-Language IaC



- **[Pulumi](https://github.com/pulumi/pulumi)**  

  **IaC with real programming languages**, Apache-2.0 licensed with **23,000+ GitHub stars** . **TypeScript, Python, Go, .NET, Java** . **Full programming language power** — loops, functions, classes, and testing . **Best for developer-centric IaC** .



- **[AWS Cloud Development Kit (CDK)](https://github.com/aws/aws-cdk)**  

  **Define cloud infrastructure using familiar programming languages**, Apache-2.0 licensed with **12,000+ GitHub stars** . **TypeScript, JavaScript, Python, Java, C#, and Go** . **High-level constructs** that reduce boilerplate by 50-90% compared to raw CloudFormation . **Synthesizes to CloudFormation templates** . **CDK for Terraform (CDKTF)** extends the model to Terraform . **Best for AWS developers wanting programming-language IaC** .



- **[CDK for Terraform (CDKTF)](https://github.com/hashicorp/terraform-cdk)**  

  **Define Terraform infrastructure using programming languages**, MPL-2.0 licensed . **TypeScript, Python, Java, C#, and Go** . **Synthesizes to Terraform configuration** . **Best for programming-language Terraform** .



- **[SST](https://github.com/sst/sst)**  

  **Modern TypeScript-first framework for deploying full-stack applications to AWS**, MIT licensed with **24,000+ GitHub stars** . **Ion** — a new engine that deploys to AWS with zero-config, live Lambda development, and automatic resource linking . **"Serverless Stack"** approach — higher-level abstractions than raw CDK . **Best for TypeScript developers deploying to AWS** .



- **[Winglang](https://github.com/winglang/wing)**  

  **A programming language for the cloud**, Apache-2.0 licensed . **Combines infrastructure and application code in one language** . **Compiles to Terraform, CloudFormation, and Kubernetes** . **Best for unified cloud development** .



### Serverless IaC Frameworks



- **[Serverless Framework](https://github.com/serverless/serverless)**  

  **The original serverless IaC framework**, MIT licensed with **46,000+ GitHub stars** . **Deploy serverless functions and resources to AWS Lambda, Azure Functions, and more** . **Plugin ecosystem and multi-cloud support** . **Best for serverless deployments** .



- **[AWS SAM (Serverless Application Model)](https://github.com/aws/serverless-application-model)**  

  **AWS's serverless framework**, Apache-2.0 licensed . **Simplifies serverless application definition and deployment** . **SAM CLI** for local testing and debugging . **Best for AWS serverless** .



- **[Architect](https://github.com/architect/architect)**  

  **Functional, stateless, and open-source serverless framework**, Apache-2.0 licensed . **Deploy AWS Lambda, API Gateway, and DynamoDB with minimal configuration** . **Best for simple serverless deployments** .



### Kubernetes-Native IaC



- **[Crossplane](https://github.com/crossplane/crossplane)**  

  **Kubernetes-native cloud resource management**, Apache-2.0 licensed with **10,000+ GitHub stars** . **Extends Kubernetes API to manage cloud resources** — provision AWS, Azure, GCP from Kubernetes . **Compositions for reusable infrastructure patterns** . **The standard for Kubernetes-native infrastructure** . **Best for platform teams building internal developer platforms** .



- **[Helm](https://github.com/helm/helm)**  

  **The package manager for Kubernetes**, Apache-2.0 licensed with **29,000+ GitHub stars** . **Charts package Kubernetes manifests** . **Best for Kubernetes application deployment** .



- **[Kustomize](https://github.com/kubernetes-sigs/kustomize)**  

  **Kubernetes configuration customization**, Apache-2.0 licensed . **Template-free configuration overlay** . **Best for Kubernetes configuration management** .



- **[Jsonnet](https://github.com/google/jsonnet)**  

  **Configuration language for JSON/YAML**, Apache-2.0 licensed . **Used with Tanka and ksonnet for Kubernetes** . **Best for templated configuration** .



### Orchestration & Workflow



- **[Terragrunt](https://github.com/gruntwork-io/terragrunt)**  

  **Terraform wrapper for DRY configurations**, MIT licensed with **8,000+ GitHub stars** . **Orchestrates Terraform across accounts and environments** . **Best for complex multi-account deployments** .



- **[Terramate](https://github.com/terramate-io/terramate)**  

  **Orchestration and code generation for Terraform**, MPL-2.0 licensed . **Adds stacks, orchestration, and GitOps to Terraform** . **Best for scaling Terraform deployments** .



- **[Atlantis](https://github.com/runatlantis/atlantis)**  

  **Terraform pull request automation**, Apache-2.0 licensed with **8,000+ GitHub stars** . **Collaborative IaC via pull requests** . **Best for Terraform collaboration** .



### Additional Strong Open-Source Options



- **Ansible** — Agentless configuration management and orchestration .

- **Chef** — Policy-driven infrastructure automation .

- **Puppet** — Declarative configuration management .

- **SaltStack** — Event-driven infrastructure automation .

- **Packer** — Machine image builder .

- **Vagrant** — Development environment automation .

- **Nix** — Reproducible package and system configuration .

- **Cloud-init** — Standard for early initialization of cloud instances .

- **Open Policy Agent** — Policy-as-code enforcement for IaC .

- **Checkov** — IaC security scanning .

- **tfsec** — Terraform security scanner .

- **Infracost** — Cloud cost estimation for IaC .



**Frameworks for building custom IaC solutions**: Combine **Terraform** or **OpenTofu** for multi-cloud provisioning with HCL . Use **Pulumi**, **AWS CDK**, or **SST** for programming-language IaC . Deploy **Crossplane** for Kubernetes-native cloud resource management . Choose **Serverless Framework** or **AWS SAM** for serverless deployments . Integrate **Terragrunt** or **Terramate** for orchestration at scale . Use **Atlantis** for PR-based Terraform workflows . Choose **Helm** and **Kustomize** for Kubernetes configuration . Note that true enterprise IaC with managed state, policy enforcement, and cost optimization (Terraform Cloud, Spacelift, Scalr) remains primarily commercial territory; open-source stacks provide strong provisioning, orchestration, and policy foundations that require integration for complete IaC deployments.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- IaC frameworks control infrastructure and credentials. **Secure state files and secrets** — state contains sensitive data . Self-hosted solutions require proper security hardening and backup procedures.

- **Terraform's BUSL license** prompted the creation of **OpenTofu** under Linux Foundation governance . Evaluate licensing against your use case before committing.

- **State management is critical** — remote state backends (S3, GCS, Azure Blob) with locking are essential for team collaboration . Never commit state files to Git .

- **IaC security scanning is essential** — use Checkov, tfsec, or similar tools to catch misconfigurations before deployment .

- **License considerations**: Terraform uses BUSL-1.1, OpenTofu uses MPL-2.0, Pulumi uses Apache-2.0, AWS CDK uses Apache-2.0, SST uses MIT, and Serverless Framework uses MIT. Verify licensing against your use case before committing.

- The open-source ecosystem provides strong provisioning, orchestration, and policy foundations, but **managed state, policy enforcement, and cost optimization** remain primarily commercial offerings.



---



**Made for platform engineers, cloud architects, and organizations seeking IaC framework sovereignty.**  

Let's make infrastructure as code more open, transparent, and declarative.
