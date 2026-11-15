# Ali Khaleel Hassan

**Cloud Security · Cloud Engineering · DevSecOps · IAM**

Cloud security-focused software engineer studying Software Engineering and Business Management (double honours, graduating 2028). I work on identity and access management, securing CI/CD pipelines, and container security, and I've built multi-tenant access control for a production-bound security operations platform as founder of NeXLock Systems.

Open to remote roles in cloud security, cloud engineering, DevSecOps and IAM.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-alihvss-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/alihvss)
[![GitHub](https://img.shields.io/badge/GitHub-haliyu280--source-181717?style=flat&logo=github&logoColor=white)](https://github.com/haliyu280-source)

---

## Projects

### [Overreach](https://github.com/haliyu280-source/overreach): AWS IAM policy analyzer and CI security gate

- Scans IAM policy JSON for overly permissive access (full admin, `iam:*` privilege escalation, service-wide wildcards) and ranks findings by severity
- Handles action lists and skips Deny statements to avoid false positives; pytest suite covers detections and policies that must stay clean
- Runs in GitHub Actions next to unit tests and a Trivy image scan, and blocks pull requests that add dangerous policies
- Packaged in a hardened Docker image (slim base, non-root user)

`Python` `pytest` `Docker` `Trivy` `GitHub Actions` `AWS IAM`

### SentinelEye: multi-server Linux monitoring platform

- Started as a Bash health-check tool (CPU, memory, disk, uptime, processes) with thresholds, JSON output and exit codes
- Grew into an agent-based setup: agents report metrics to a FastAPI backend that evaluates health and raises alerts in a React dashboard

`Bash` `Python` `FastAPI` `React` `Docker` `Vercel`

### NEXOPS (private): security operations platform at NeXLock Systems

Founder of NeXLock Systems. Built NEXOPS, a pre-launch security operations platform with multi-tenant data isolation using PostgreSQL Row-Level Security, role-based access control, serverless integrations, and a mobile field app. Company code stays private.

---

## Skills

| Area | Tools and concepts |
|---|---|
| Cloud & security | AWS (IAM, MFA, CloudTrail), least privilege, IAM policy analysis, container security, CI/CD security gates, application security (JWT, RBAC, Row-Level Security) |
| DevOps | Docker, GitHub Actions, Git (branches, pull requests), Linux |
| Infrastructure as code & orchestration | Terraform, Kubernetes (working knowledge) |
| Languages | Python, Bash, JavaScript, SQL |
| Backend & web | FastAPI, Supabase, PostgreSQL, REST APIs, React, Vercel |
| Networking | TCP/IP, DNS, VPCs, NAT, security groups |
| Monitoring | Splunk (searches, alert rules) |

---

## Certifications & training

- NVIDIA Deep Learning Institute: Building AI Agents with Multimodal Models (Nov 2026)
- Google: Introduction to AI (Apr 2026)
- Pearson: Ethical hacking coursework, CEH curriculum Unit 1 (Mar 2026)
