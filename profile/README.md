<p align="center">
  <img src="https://raw.githubusercontent.com/Quality-Max/.github/main/profile/logo.png" alt="QualityMax" width="300">
</p>

<h3 align="center">AI-Powered Test Automation Platform</h3>

<p align="center">
  Generate, execute, and maintain end-to-end tests for web applications — from a single URL to full CI/CD integration.
</p>

<p align="center">
  <a href="https://app.qamax.co"><strong>Platform</strong></a> &nbsp;&middot;&nbsp;
  <a href="https://github.com/Quality-Max/qualitymax">Documentation</a> &nbsp;&middot;&nbsp;
  <a href="https://github.com/marketplace/actions/qualitymax-e2e-tests">GitHub Action</a>
</p>

---

## What We Build

QualityMax crawls your web application, understands its structure, and generates production-ready Playwright test suites. Tests run in the cloud or on your own infrastructure, with self-healing capabilities that keep them working as your app evolves.

### Core Capabilities

- **AI Test Generation** — Point at a URL, get comprehensive E2E tests with assertions and page object models
- **Playwright Execution** — Run tests in cloud browsers or locally via our agent, with video recording and screenshots
- **CI/CD Integration** — GitHub Action that runs your test suite on every push or pull request
- **Self-Healing Tests** — AI detects and fixes broken selectors automatically when your UI changes
- **Test Management** — Organize test cases by project, track execution history, and manage test runs

---

## Repositories

| Repository | Description |
|---|---|
| [**qualitymax**](https://github.com/Quality-Max/qualitymax) | Platform documentation and public issue tracker |
| [**qualitymax-github-action**](https://github.com/Quality-Max/qualitymax-github-action) | GitHub Action for running QualityMax tests in CI/CD pipelines |
| [**qualitymax-demo-playground**](https://github.com/Quality-Max/qualitymax-demo-playground) | Demo repository showing GitHub Action integration in practice |
| [**qamax-auth-cli**](https://github.com/Quality-Max/qamax-auth-cli) | CLI tool for capturing auth sessions used during AI crawling |

---

## Quick Start

### Run tests in your CI/CD pipeline

```yaml
# .github/workflows/e2e-tests.yml
name: E2E Tests
on: [push, pull_request]

jobs:
  test:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
      - uses: Quality-Max/qualitymax-github-action@v1
        with:
          api-key: ${{ secrets.QUALITYMAX_API_KEY }}
          project-name: my-project
```

### Try the platform

Visit [**app.qamax.co**](https://app.qamax.co) to get started.

---

## Links

- **Platform**: [app.qamax.co](https://app.qamax.co)
- **Documentation**: [qualitymax repo](https://github.com/Quality-Max/qualitymax)
- **GitHub Action**: [Marketplace](https://github.com/marketplace/actions/qualitymax-e2e-tests)
