# CST8918 – Lab A03 Submission

## Student Information

| Field        | Details                                    |
| ------------ | ------------------------------------------ |
| Students Name | Xinyi Zhao - Sara Mirzaei                               |
| Course       | CST8918 – Cloud Development and Operations |
| Lab          | Lab A03                                    |
| Branch Name  | `lab-a03`                             |
| Repository   | https://github.com/XinyiZhao-cloud/cst8918-w24-a03-weather-pulumi/tree/lab-a03                 |

---

# Overview

This lab demonstrates the use of Pulumi for Infrastructure as Code (IaC), cloud resource provisioning, deployment configuration, and environment management.

---

# Task 1 – Environment Setup

## Description

Configured the local development environment and initialized the Pulumi project.


# Task 2 – Pulumi Configuration

## Description

Configured Pulumi stack variables and environment-specific settings.

## Commands Used

```bash id="p9rkf8"
pulumi config set frontendPort 3001
pulumi config set backendPort 3000
pulumi config set mongoPort 27017
pulumi config set mongoHost mongodb://mongo:27017
pulumi config set database cart
pulumi config set nodeEnvironment development
pulumi config set protocol http://
```

---

# Task 3 – Infrastructure Deployment

## Description

Provisioned and deployed the infrastructure resources using Pulumi.

## Commands Used

```bash id="p0ybj8"
pulumi up
```

# Task 4 – Docker Containers

## Description

Built and ran the required Docker containers for the application services.

## Commands Used

```bash id="gq4xjb"
docker ps
docker images
```
---

# Task 5 – Application Verification

## Description

Verified that the application services were successfully deployed and accessible.

## Verification Steps

* Verified frontend accessibility
* Verified backend API functionality
* Verified container status
* Verified Pulumi stack deployment

---

# Git Branch Information

## Current Branch

```bash id="t0g8zk"
git branch
```

# Final Result

The Pulumi infrastructure deployment and application configuration were completed successfully. All required services and containers were deployed and verified.

---

# Screenshots

## Running Application Screenshot (on both sides)

> <img width="975" height="579" alt="image" src="https://github.com/user-attachments/assets/38366999-588d-41a3-8087-55da989d6714" />
> <img width="1470" height="816" alt="image" src="https://github.com/user-attachments/assets/0a1e9c63-290c-4476-a91c-85b97feadc0f" />


---

## Resource Group in Azure

> <img width="2172" height="1158" alt="image" src="https://github.com/user-attachments/assets/f04ed22d-5083-453d-af77-99815d6ed41f" />

---

## Terminal
> <img width="2940" height="1666" alt="image" src="https://github.com/user-attachments/assets/8cd2654f-6ce8-4122-9f3e-ec488d2c2c02" />

