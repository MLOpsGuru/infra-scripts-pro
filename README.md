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

## 🔍 Key Features

- ✅ GitHub Actions CI with lint/test gates
- 🔐 Secrets-free scripts, designed for real infra
- 📦 Docker + K8s + Terraform ready
- 📈 Linux health monitoring + cost auditing
- 🧰 Fast setup tools for new environments

## 💡 How to Use

- Each script is standalone and documented
- Integrate with GitHub Actions or cron/systemd
- Use as templates or production tools

## 🧪 Quality Signals

- `shellcheck` compliance (Bash)
- `yamllint` for all workflow files
- Folder naming and logic follow platform team best practices

---

## 📬 Contributions

If you're a platform engineer and want to add battle-tested infra utilities, PRs are welcome.

---

## 🧠 Author

Built by an engineer on a 10-week mission to demonstrate senior DevOps/MLOps readiness. Follow the [GitHub profile](https://github.com/MLOpsGuru) for project logs and updates.
