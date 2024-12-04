# GitHub Actions Lab

A hands-on laboratory for learning and implementing GitHub Actions CI/CD workflows. This project demonstrates practical implementation of continuous integration using GitHub's native automation tools.

[![test](https://github.com/nabilshadman/gha-lab/actions/workflows/test.yml/badge.svg)](https://github.com/nabilshadman/gha-lab/actions/workflows/test.yml)

## 🎯 Overview

This lab provides practical experience with GitHub Actions, focusing on automated testing and continuous integration principles. Through simple Python examples, it demonstrates workflow configuration, automation triggers, and CI pipeline setup.

## ⚙️ Implementation

The project includes:
- Basic Python script (`hello.py`) for testing workflow execution
- GitHub Actions workflow configuration
- Automated test execution on push/pull request
- Status badge integration

## 🔧 Workflow Structure

```yaml
.github/
└── workflows/
    └── test.yml    # Main workflow configuration
```

## 🚀 Getting Started

1. Clone the repository
```bash
git clone https://github.com/yourusername/gha-lab.git
cd gha-lab
```

2. Examine the workflow file at `.github/workflows/test.yml`

3. Make changes to trigger the workflow:
```bash
# Modify hello.py
git add .
git commit -m "test: trigger workflow"
git push
```

4. Monitor the workflow execution in the Actions tab of your GitHub repository

## 📊 Status Tracking

The status badge above provides real-time feedback on workflow execution status. Click the badge to view detailed workflow runs and logs.

## 🔍 Learning Outcomes

- Understanding GitHub Actions workflow structure
- Implementing basic CI/CD pipelines
- Configuring automated tests
- Monitoring workflow execution
- Interpreting workflow results

## 📚 Resources

- [GitHub Actions Documentation](https://docs.github.com/en/actions)
- [Workflow Syntax Reference](https://docs.github.com/en/actions/reference/workflow-syntax-for-github-actions)
- [GitHub Actions Marketplace](https://github.com/marketplace?type=actions)
