# devsecops-challenges

## Instruction

Please read through the small technical challenge, and make a fork of the repository to your private account and develop on it. Please ensure to edit the README.md file in order to give descriptions to your work.

Please do not worry if you cannot achieve all of the goals in the technical excercise. It is only meant to cover many areas, and you are only assessed on your strengths. We have a diverse team.

Finally and most importantly, be creative, be free, and have FUN!


## Challenges

### 01: Optimize Build

Each build cost money.
Please help us review and optimize the dockerfile to build an image effectively.


#### Bonus point

- There is an reliability issue with this app. Please spot it if you found
- Please define a small sensible container health check

### 02: Design and deploy infra

Please attempt one or both of these to the best of your ability:
A. Please help us write an infrastructure script (e.g. shell script, terraform script, using public modules are allowed) to deploy AWS infra to host:
- VPC
- Backend on ECS (can use nginx as example image)
- S3 bucket

B. Please write one generic shell script (using environment variables as secrets, e.g. for AWS) to: 
  1. generate docker images, and deploy to Elastic Container Registry
  2. deploy the infrastructure manifest above

#### Bonus point

- Please make sure the design secure and compliance with AWS Foundational Security Best Practices standard

- Scan to report resources without tag

### 03: Our engineer define k8s yaml to deploy resources but it's not work and we don't know why? Please review the k8s manifests and make recommendation to deploy an application with reliability and security is a must
