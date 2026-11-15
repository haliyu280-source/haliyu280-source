Ali Khaleel Hassan

Cloud Security · DevSecOps · IAM · Linux

Software Engineering and Business Management student (graduating 2028) focused on cloud security and infrastructure. I build security tooling end to end and test it like it's going to production: detection rules, automated tests, CI gates, hardened containers, and honest documentation of what it doesn't do yet.

Looking for remote internships and entry-level roles in cloud security, cloud support, or DevSecOps.

Projects
Overreach: AWS IAM policy analyzer and CI security gate
Scans IAM policy JSON for overly permissive access (full admin, iam:* privilege escalation, service-wide wildcards) and ranks findings by severity
Handles action lists and skips Deny statements to avoid false positives; pytest suite covers detections and policies that must stay clean
Runs in GitHub Actions next to unit tests and a Trivy image scan, and blocks pull requests that add dangerous policies
Packaged in a hardened Docker image (slim base, non-root user)

Python pytest Docker Trivy GitHub Actions AWS IAM

SentinelEye: multi-server Linux monitoring platform
Started as a Bash health-check tool (CPU, memory, disk, uptime, processes) with thresholds, JSON output and exit codes
Grew into an agent-based setup: agents report metrics to a FastAPI backend that evaluates health and raises alerts in a React dashboard

Bash Python FastAPI React Docker Vercel

NEXOPS (private): security operations platform at NeXLock Systems

I'm the founder of NeXLock Systems and built NEXOPS, a pre-launch security operations platform: multi-tenant data isolation with PostgreSQL Row-Level Security, role-based access control, serverless integrations, and a mobile field app. Company code stays private.

Skills
Area	Tools and concepts
Cloud & security	AWS IAM, MFA, CloudTrail, least privilege, IAM policy analysis, container security, CI/CD security gates
DevOps	Docker, GitHub Actions, Git (branches, pull requests), Linux
Languages	Python, Bash, JavaScript, SQL
Backend & web	FastAPI, Supabase, PostgreSQL, REST APIs, React, Vercel
Networking	TCP/IP, DNS, VPCs, NAT, security groups
Currently learning	Terraform, Kubernetes, AWS hands-on labs
Certifications & training
NVIDIA Deep Learning Institute: Building AI Agents with Multimodal Models (Nov 2026)
Google: Introduction to AI (Apr 2026)
Links
LinkedIn: linkedin.com/in/alihvss
GitHub: github.com/haliyu280-source
