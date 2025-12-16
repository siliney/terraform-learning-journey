# 🚀 Terraform Learning Journey

> **Infrastructure as Code (IaC) Learning Repository**  
> Practical Terraform examples and hands-on exercises

[![Terraform](https://img.shields.io/badge/Terraform-1.14+-623CE4?logo=terraform)](https://terraform.io)
[![AWS](https://img.shields.io/badge/AWS-Cloud-FF9900?logo=amazon-aws)](https://aws.amazon.com)
[![Dev Container](https://img.shields.io/badge/Dev_Container-Ready-blue?logo=docker)](https://code.visualstudio.com/docs/remote/containers)

## 📚 What's Inside

This repository contains my hands-on learning materials for **Developing Infrastructure as Code with Terraform**. Each lesson includes practical examples, working code, and real-world scenarios.

### 🎯 Learning Objectives
- Master Terraform fundamentals and advanced concepts
- Build scalable cloud infrastructure on AWS
- Implement Infrastructure as Code best practices
- Automate deployment workflows

## 🗂️ Project Structure

```
├── lessons/
│   ├── 01/           # Terraform Basics & Hello World
│   ├── 03/           # Resource Management
│   ├── 04/           # State Management
│   ├── 05/           # Advanced Configurations
│   └── atlantis/     # Atlantis Integration
├── .devcontainer/    # VS Code Dev Container setup
└── slides/           # Learning materials
```

## 🚀 Quick Start

### Prerequisites
- Docker Desktop
- VS Code with Dev Containers extension

### Using Dev Container (Recommended)
1. Clone this repository
2. Open in VS Code
3. Click "Reopen in Container" when prompted
4. Start coding! Terraform is pre-installed

### Manual Setup
```bash
# Install Terraform
curl -fsSL https://apt.releases.hashicorp.com/gpg | sudo apt-key add -
sudo apt-add-repository "deb [arch=amd64] https://apt.releases.hashicorp.com $(lsb_release -cs) main"
sudo apt-get update && sudo apt-get install terraform
```

## 📖 Lessons Overview

| Lesson | Topic | Status | Key Concepts |
|--------|-------|--------|--------------|
| 01 | Hello Terraform | ✅ Complete | Basic syntax, outputs |
| 03 | Resource Management | 🔄 In Progress | AWS resources, dependencies |
| 04 | State Management | 📋 Planned | Remote state, locking |
| 05 | Advanced Topics | 📋 Planned | Modules, workspaces |

## 🛠️ Technologies Used

- **Terraform** - Infrastructure as Code
- **AWS** - Cloud Provider
- **Docker** - Containerized development
- **VS Code** - Development environment
- **Git** - Version control

## 📝 Learning Notes

Each lesson includes:
- 📄 Terraform configuration files (`.tf`)
- 📖 README with explanations
- 🖼️ Screenshots of results
- 💡 Best practices and tips

## 🤝 Contributing

This is a personal learning repository, but feel free to:
- Open issues for questions
- Suggest improvements
- Share your own learning experiences

## 📄 License

This project is for educational purposes. Course materials credit to original authors.

---
⭐ **Star this repo** if you find it helpful for your Terraform learning journey!
