<!-- ================= HEADER ================= -->

<h1 align="center">🚀 DevOps | Platform Engineer | Site Reliability Engineer (SRE)</h1>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com/?lines=AWS+%7C+Kubernetes+%7C+Terraform+%7C+GitOps;Platform+Engineering+%7C+SRE+%7C+DevSecOps;Scalable+%7C+Reliable+%7C+Production+Systems&center=true&width=700&height=45">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/AWS-Cloud-orange?style=for-the-badge&logo=amazonaws">
  <img src="https://img.shields.io/badge/Kubernetes-Orchestration-blue?style=for-the-badge&logo=kubernetes">
  <img src="https://img.shields.io/badge/Terraform-Infrastructure_as_Code-5C4EE5?style=for-the-badge&logo=terraform">
  <img src="https://img.shields.io/badge/GitOps-ArgoCD-red?style=for-the-badge&logo=argo">
  <img src="https://img.shields.io/badge/CI/CD-Automation-black?style=for-the-badge&logo=githubactions">
</p>

<hr>

<!-- ================= ATS SUMMARY ================= -->

<h2>👋 Professional Summary</h2>

<p>
DevOps / Platform Engineer with hands-on experience building and operating <b>scalable, distributed systems</b> on AWS.
Specialising in <b>Kubernetes, Infrastructure as Code (Terraform), CI/CD automation, and Site Reliability Engineering (SRE)</b>.
</p>

<p>
Proven ability to design <b>secure, highly available, and fault-tolerant systems</b> with strong focus on:
</p>

<ul>
  <li><b>Cloud Platforms:</b> AWS (EKS, ECS, IAM, VPC, ECR, Route53)</li>
  <li><b>Infrastructure as Code (IaC):</b> Terraform (modular, reusable architecture)</li>
  <li><b>Container Orchestration:</b> Kubernetes (EKS), Docker</li>
  <li><b>CI/CD Pipelines:</b> GitHub Actions, GitLab CI (OIDC, secure pipelines)</li>
  <li><b>GitOps:</b> ArgoCD (declarative deployments)</li>
  <li><b>Observability:</b> Prometheus, Grafana, Loki, CloudWatch</li>
  <li><b>DevSecOps:</b> SonarQube (SAST), Trivy (SCA, container scanning)</li>
  <li><b>Systems:</b> Linux</li>
</ul>

<p>
Strong focus on <b>automation, reliability, scalability, and production readiness</b>, aligned with SRE principles
(SLIs, SLOs, monitoring, alerting, and incident response).
</p>

<hr>

<!-- ================= GITHUB STATS ================= -->

<h2>📊 Engineering Metrics</h2>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=JamaEngineer&show_icons=true&theme=radical" height="165">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=JamaEngineer&theme=radical" height="165">
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=JamaEngineer&layout=compact&theme=radical">
</p>

<hr>

<!-- ================= PROJECTS ================= -->

<h2>🏗️ (Production-Grade Systems)</h2>

<h3>⚡ Kubernetes Platform Engineering | GitOps | AWS EKS</h3>

<p><b>Tech:</b> AWS EKS, Terraform, ArgoCD, Helm, GitLab CI, Docker, Prometheus, Grafana, Loki</p>

<pre>
Developer → GitLab CI (OIDC) → Build/Test/Scan → ECR → ArgoCD → EKS Cluster
                                                         ↓          ↓
                                                         L → Observability (Prometheus/Grafana/Loki)
</pre>

<ul>
  <li>
    Built a <b>production-grade Kubernetes platform</b> on AWS using Terraform (VPC, EKS, IAM, ALB, ECR)
  </li>

  <li>
    Migrated workloads from <b>ECS to EKS</b> using progressive traffic shifting for zero-downtime cutover
  </li>

  <li>
    Implemented secure <b>CI/CD and GitOps workflows</b> using GitHub Actions, OIDC, ArgoCD, and Helm
  </li>

  <li>
    Enforced <b>policy-driven security</b> using OPA Gatekeeper, Trivy, SonarQube, IRSA, and External Secrets
  </li>

  <li>
    Automated <b>TLS certificate management</b> using cert-manager with Let’s Encrypt HTTP-01 and DNS-01 challenges
  </li>

  <li>
    Built observability using <b>Prometheus, Grafana, and Loki</b> for monitoring and troubleshooting
  </li>

  <li>
    Improved developer feedback loops using <b>AWS Lambda and EventBridge</b> Slack integrations
  </li>

  <li>
    Optimised Kubernetes workloads using HPA and resource tuning, reducing <b>compute usage by ~30%</b>
  </li>
</ul>

<b>Impact:</b>
<ul>
  <li>Reduced infrastructure provisioning time by <b>~80%</b> (15 → 3 mins)</li>

  <li>Improved deployment reliability and rollback consistency through GitOps workflows</li>

  <li>Enabled zero-downtime deployments and scalable multi-environment infrastructure</li>

  <li>Improved incident detection and troubleshooting through centralised observability</li>
</ul>

<p><b>👉 <a href="https://github.com/JamaEngineer/GitLabKubernetesProject">View Repository</a></b></p>

<hr>

<h3>🔄 Blue/Green Deployment System | AWS ECS | CI/CD</h3>

<p><b>Tech:</b> AWS ECS (Fargate), Terraform, GitHub Actions, CodeDeploy, ALB, Docker, CloudWatch</p>

<pre>
GitHub Actions → Build/Test/Scan → ECR → CodeDeploy → Blue/Green Environments → ALB → Users
</pre>

<ul>
  <li>Built <b>container-based platform</b> on AWS ECS (Fargate) using Terraform</li>
  <li>Implemented <b>blue/green deployment strategy</b> with automated traffic shifting</li>
  <li>Designed <b>CI/CD pipelines</b> with integrated security scanning (SonarQube, Trivy)</li>
  <li>Automated <b>Docker build, image registry (ECR), and deployment workflows</b></li>
  <li>Reduced deployment time by <b>50%+</b> through pipeline optimisation</li>
  <li>Configured <b>monitoring, alerting, and automated rollback</b> using CloudWatch</li>
  <li>Validated system reliability via <b>failure injection and rollback testing</b></li>
</ul>

<p>
<b>Impact:</b>
<ul>
  <li>Achieved zero-downtime deployments</li>
  <li>Improved system reliability and release safety</li>
  <li>Embedded DevSecOps practices into delivery pipeline</li>
</ul>
</p>

<p><b>👉 <a href="https://github.com/JamaEngineer/ECSBlueGreenProject">View Repository</a></b></p>

<hr>

<!-- ================= CORE COMPETENCIES ================= -->

<h2>🎯 Core Competencies</h2>

<ul>
  <li><b>Platform Engineering:</b> Kubernetes platforms, multi-environment systems</li>
  <li><b>Site Reliability Engineering (SRE):</b> monitoring, alerting, incident response</li>
  <li><b>Cloud Architecture:</b> scalable, highly available distributed systems</li>
  <li><b>Infrastructure Automation:</b> Terraform, CI/CD pipelines</li>
  <li><b>DevSecOps:</b> secure software supply chain, vulnerability scanning</li>
  <li><b>Observability:</b> metrics, logs, dashboards, system visibility</li>
</ul>

<hr>

<!-- ================= CURRENT FOCUS ================= -->

<h2>📌 Current Focus</h2>

<ul>
  <li>Advanced Kubernetes platform engineering</li>
  <li>Scaling GitOps for multi-cluster environments</li>
</ul>

<hr>

<!-- ================= CONTACT ================= -->

<h2>🤝 Contact</h2>

<p>
Open to <b>DevOps Engineer, Platform Engineer, and Site Reliability Engineer (SRE)</b> opportunities.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/jamajama1/">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin">
  </a>
</p>

<hr>

<p align="center"><i>💡 Explore my repositories to see production-grade cloud and platform engineering projects.</i></p>
