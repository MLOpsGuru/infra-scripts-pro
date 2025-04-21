# infra-scripts-pro 🚀

> A curated toolbox of automation and observability scripts for senior DevOps, SRE, and MLOps engineers.

## 🔧 What's Inside

Modular shell and Python scripts organized for reuse in CI/CD, cloud automation, and production incident tooling.

```
.
├── .github/workflows/ci.yml                # GitHub Actions pipeline
├── cicd/                                   # Linting, deploy, notify
├── docker/                                 # Container automation
├── kubernetes/                             # Cluster ops & debug
├── terraform/                              # IaC lifecycle tools
├── observability/                          # Monitoring & metrics
├── utilities/                              # Cloud backups, bootstrap
```

---

### 🔍 Key Features

✅ GitHub Actions CI with lint/test gates  
🔐 Secrets-free scripts, built for secure environments  
📦 Docker + K8s + Terraform ready  
📈 Linux health reporting + cost auditing tools  
🧰 Bootstrap utilities for fast setup  

---

### 💡 How to Use

- Scripts are standalone, documented, and modular  
- Use manually or automate via GitHub Actions, cron, or systemd  
- Suitable for real-world use or as starter templates

---

### 🧪 Code Hygiene

Scripts are:
- `shellcheck`-compliant (where applicable)
- YAML follows `yamllint` guidelines
- Folder and file structure reflect platform team best practices
- Cross-platform safe (LF line endings via `.gitattributes`)

---

### 📬 Contributions

Contributions welcome — especially improvements based on real-world CI/CD, Kubernetes, or Terraform experience.

---

### 👨‍💻 Maintainer

Built as part of a professional DevOps/MLOps portfolio, this repo curates tools that solve real infrastructure needs — fast, safely, and portably.

🔗 GitHub: [MLOpsGuru](https://github.com/MLOpsGuru)
