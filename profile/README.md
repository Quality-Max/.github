# QualityMax

**Independent verification for AI-written code.**

Discover user journeys, generate and run tests, review changes, and inspect the evidence behind your next release.

[Website](https://qualitymax.io) · [Open QualityMax](https://app.qualitymax.io) · [Documentation](https://docs.qualitymax.io/) · [Standalone tools](https://docs.qualitymax.io/free-and-open-source/)

## Start here

| Your workflow | Get started |
|---|---|
| Use the platform to manage tests and inspect runs | [Web app quickstart](https://docs.qualitymax.io/quickstart-web-app/) |
| Connect your coding agent to hosted QualityMax | [MCP quickstart](https://docs.qualitymax.io/quickstart-mcp/) |
| Work locally with standalone tools | [qmax-mcp](https://github.com/Quality-Max/qmax-mcp), [qmax-code](https://github.com/Quality-Max/qmax-code), or [QA skills](https://github.com/Quality-Max/free-qa-skills) |

Hosted workflows use a QualityMax account. Standalone tools have their own prerequisites; model-assisted workflows may require a model provider or coding-agent subscription.

## What you can do

- **Turn user journeys into coverage.** Generate tests, execute them, and inspect results and available artifacts. [Start a first run →](https://docs.qualitymax.io/quickstart-web-app/)
- **Verify pull requests.** Combine code review, supported native test suites, generated-test feedback, and preview-browser checks. Gate availability and enforcement depend on configuration. [PR gates →](https://docs.qualitymax.io/code-review-gates/)
- **Get specialist review.** Use Nexus for attributed findings and shareable review reports. [Nexus →](https://docs.qualitymax.io/nexus-review/)
- **Evaluate AI applications.** Assess conversations and hallucination risks, and explore browser journeys with simulated users. [AI validation →](https://docs.qualitymax.io/ai-validation/) · [Agentic Eyes →](https://docs.qualitymax.io/agentic-eyes/)
- **Investigate and repair failing tests.** Review failure evidence and proposed repairs. [Self-healing →](https://docs.qualitymax.io/self-healing/)
- **Bring project context into Slack.** Ask project-aware questions and review supported action proposals. [Slack →](https://docs.qualitymax.io/slack/) · [Memory and grounding →](https://docs.qualitymax.io/memory-grounding/)
- **Manage and reuse test assets.** Organize cases and scripts, work with performance tests, and exchange QTML assets. [Test management →](https://docs.qualitymax.io/test-management/) · [Performance →](https://docs.qualitymax.io/performance/) · [QTML →](https://docs.qualitymax.io/export-qtml/)

## Explore the tools

| Project | Purpose | License / status |
|---|---|---|
| [qmax-mcp](https://github.com/Quality-Max/qmax-mcp) | Local browser inspection, scanning, Playwright reproduction generation, and test execution through MCP | MIT; standalone and optional hosted proxy modes |
| [qmax-code](https://github.com/Quality-Max/qmax-code) | Terminal agent for coding and testing, with standalone and connected workflows | Source available, FSL-1.1-ALv2 |
| [Free QA Skills](https://github.com/Quality-Max/free-qa-skills) | Reusable QA workflows for supported coding agents | Apache-2.0 |
| [9lives](https://github.com/Quality-Max/9lives) | Local test repair with reruns and reviewable diffs | MIT; prototype |
| [Test Grader](https://github.com/Quality-Max/qualitymax-grader) | Static Playwright test-quality grading | Apache-2.0 |
| [Supply Chain Scanner](https://github.com/Quality-Max/supply-chain-scanner) | Python dependency supply-chain checks | Apache-2.0 |
| [qmax local agent](https://github.com/Quality-Max/qmax-local-agent) | CLI and local execution agent for platform workflows | Apache-2.0 |

See each repository for its current requirements and limitations. The hosted platform and individual tools have different licensing and availability.

For integrations that embed QualityMax, see [Partner / White-label](https://docs.qualitymax.io/partner-white-label/). For responsive audits and managed flows, see [Mobile](https://docs.qualitymax.io/mobile/). Learn how to interpret [evidence and receipts](https://docs.qualitymax.io/evidence-trust/).

## See examples and integrations

[qmax-mcp demo](https://github.com/Quality-Max/qmax-mcp/tree/main/demo) · [9lives repair demo](https://github.com/Quality-Max/9lives/blob/main/demo/heal.gif) · [GitHub Action](https://github.com/Quality-Max/qualitymax-github-action) · [n8n workflows](https://github.com/Quality-Max/n8n-nodes-qualitymax) · [qmax-code releases](https://github.com/Quality-Max/qmax-code/releases/latest)

For the wider platform, visit the [public product guide](https://github.com/Quality-Max/qualitymax) and [documentation](https://docs.qualitymax.io/). Sovereign deployment is available as a [private preview](https://docs.qualitymax.io/deployment/).

To contribute to a tool, start with its repository's contribution guidance and issue tracker.
