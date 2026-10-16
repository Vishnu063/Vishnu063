# DevOps portfolio

A starting point for reviewing my cloud and DevOps projects. Each linked reviewer guide points to source, suggests a demonstration, and states what still needs validation.

## Start with these projects

| Project | What to review | Evidence boundary |
| --- | --- | --- |
| [DevOps Platform Toolkit](https://github.com/Vishnu063/devops_platform/blob/main/INTERVIEW.md) | Kubernetes release checks, incident reports, and approved recovery | 97 local regression tests passed in the 16 October review; live acceptance is separate |
| [Troubleshooting Labs](https://github.com/Vishnu063/devops-troubleshooting-labs/blob/main/INTERVIEW.md) | A broken Git lab, an actual repair, and a recovery check | 100 evidence cases; 24 runnable standard labs plus 3 compound incidents |
| [DevOps Triage Assistant](https://github.com/Vishnu063/devops-triage-assistant/blob/main/INTERVIEW.md) | Scoped collection, diagnosis, and repair-plan approval | 178-test suite completed with 3 live Docker tests skipped in this review |
| [PharmaCare / CloudLaunch](https://github.com/Vishnu063/cloudlaunch) | FastAPI/PostgreSQL app, Jenkins deployment and rollback, permission tests | Current deployment and complete end-to-end coverage need a fresh check |
| [URL shortener](https://github.com/Vishnu063/urlshort) | Application tests, CI, Terraform, Ansible, Helm, and Argo CD | Source available; no fresh deployment was performed in this portfolio review |

## Other project areas

| Repository | Review focus |
| --- | --- |
| [Git practice notes](https://github.com/Vishnu063/Demo) | A small repository for Git practice. It is not an application or a deployment project. |
| [Static website delivery with GitHub Pages](https://github.com/Vishnu063/my-ticketing-system) | A static web page with a GitHub Actions workflow targeting GitHub Pages. The current workflow is not an AWS deployment pipeline. |
| [Git and Jenkins practice](https://github.com/Vishnu063/First_repo) | A collection of early Git exercises with a Jenkinsfile and small source/text files. |
| [Hostel management application — fork](https://github.com/Vishnu063/Hostel-Manag) | A fork of a Java servlet/JSP application with DAO and entity layers. |
| [Static website deployment practice](https://github.com/Vishnu063/Project) | Static HTML/CSS files with a GitHub Actions deployment workflow. |
| [AWS infrastructure with Terraform](https://github.com/Vishnu063/AWS-Infrastructure-Automation-Project) | Terraform configuration organized into VPC, EC2, and S3 modules, with an existing GitHub Actions workflow. |
| [HRMS application — fork](https://github.com/Vishnu063/new-hrms-sourcecode) | An inherited application source tree organized into backend and frontend directories. |
| [AWS backup and disaster-recovery lab](https://github.com/Vishnu063/Project-Nova) | Terraform configuration and Lambda scripts for AWS backup and cross-region recovery experiments. |
| [Python application and Jenkins experiment](https://github.com/Vishnu063/Project123) | A Python application, Dockerfile, and Jenkinsfile alongside media and experimental dependencies. |
| [CI/CD learning collection — fork](https://github.com/Vishnu063/myweb) | An inherited collection of Jenkins, Docker, Kubernetes, Terraform, and application examples. |
| [Container and Terraform experiments](https://github.com/Vishnu063/My_Project) | Application services and Docker Compose configurations alongside Terraform infrastructure directories. |
| [DevOps trivia prototype](https://github.com/Vishnu063/devops-trivia-game) | A Flask/SQLite quiz API with a static frontend and Docker configuration. |
| [Wanderlust deployment lab — fork](https://github.com/Vishnu063/Wanderlust-Mega-Project1) | A forked travel-blog application with Docker and Jenkins/GitOps deployment material. |
| [Kubernetes manifest starter](https://github.com/Vishnu063/devsecops-platform) | Namespace, Deployment, and Service manifests for an Nginx-based workload. |
| [Kubernetes and GitOps lab](https://github.com/Vishnu063/my-k8s-project) | A nested devsecops-platform project containing application, Terraform, Kubernetes, Argo CD, monitoring, and workflow material. |
| [PromptShield security gateway prototype](https://github.com/Vishnu063/Promptshield) | Python gateway code with injection/PII detectors, rate limiting, tests, Docker, Kubernetes, and Terraform material. |
| [SecureMicro delivery lab](https://github.com/Vishnu063/SecureMicro) | A Node.js backend, static frontend, Redis, Jenkins pipeline, Terraform infrastructure, and Helm chart. |
| [CreatorOS placeholder](https://github.com/Vishnu063/creatoros) | A repository name and introductory README; no application implementation was found in the inspected tree. |
| [Java DevSecOps delivery lab](https://github.com/Vishnu063/devsecops-demo) | A Java application with a Maven build, Dockerfile, Jenkinsfile, Helm environments, and AWS Terraform definitions. |
| [Voting application deployment lab](https://github.com/Vishnu063/votesecops) | A multi-service voting application with Docker/Swarm, Kubernetes, Helm, and monitoring configurations. |
| [Activepieces deployment practice](https://github.com/Vishnu063/devops-cicd-project) | A short Jenkins deployment/HTTP-check pipeline, Compose configuration, and backup script. |
| [ROOT — The Last Engineer](https://github.com/Vishnu063/root-the-last-engineer) | A browser-native adventure prototype with a separate 500-question DevOps training campaign. |

## Forks and early work

Hostel-Manag, new-hrms-sourcecode, myweb, Wanderlust-Mega-Project1, and VoiceStudio are forks. Their upstream authors retain credit; a fork alone is not evidence of my contribution. Review commit diffs when discussing work on them. VoiceStudio's upstream documentation was left intact in this review.

Demo, First_repo, MySecGit, and My-repo-vishnu are learning material. CreatorOS and the empty Terraform/Wanderlust-Mega-Project repositories are placeholders rather than completed projects. Private repositories are not presented as public interview demos.

## How I would demonstrate a project

I start with its purpose, follow the relevant source, reproduce a failure or useful result, and explain the observation that verifies the outcome. I distinguish work I changed from inherited code, and local tests from live provider acceptance.

This index records the source review on 16 October 2026. It does not imply that every repository has been deployed, fully audited, or independently reviewed. Deployment-sensitive documentation changes may be in draft pull requests until their integration is reviewed.
