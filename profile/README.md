# Agent Consultant Council

### Independent AI opinions. Better-informed decisions.

Agent Consultant Council is an extensible, provider-independent consultation platform that enables AI agents to consult external AI models for independent feedback, architectural reviews, technical validation, debates, and decision support.

### Mission

Help AI agents make better-informed decisions through independent consultation while preserving user control, privacy, and the authority of the primary agent.

### Core Pillars
* **Consultant Intelligence** — Multi-provider consultations, independent reviews, debates, and verification.
* **Capability-Based Routing** — Dynamic capabilities, provider selection, and intelligent fallbacks.
* **Rules & Customization** — Configurable instructions, settings, preferences, and reusable skills.
* **Hooks & Governance** — Lifecycle automation, policies, permissions, and approvals.
* **Usage Management** — Provider quotas, budgets, and consumption controls.
* **Security & Privacy** — Context isolation, sensitive-data redaction, and outbound security.

### Repository Ecosystem

Our repositories are independently maintained components of one modular ecosystem.

| Repository | Responsibility |
| :--- | :--- |
| `council-docs` | Architecture and documentation |
| `council-contracts` | Shared interfaces and schemas |
| `council-core` | Consultation engine and orchestration |
| `council-security` | Security and privacy |
| `council-providers` | AI provider integrations |
| `council-mcp` | Model Context Protocol integration |
| `council-cli` | Command-line interface |

### Design Principles

* **Provider Independence** — Avoid vendor lock-in through modular provider integrations.
* **Modularity** — Keep components independently maintainable and extensible.
* **Capability-Based Routing** — Select consultants based on their strengths and configured capabilities.
* **Privacy First** — Share only the necessary context with external providers.
* **Configurable Governance** — Support rules, policies, preferences, and lifecycle controls.
* **Cost Awareness** — Manage provider usage, quotas, budgets, and spending.
* **Decision Transparency** — Preserve consultation feedback, supporting evidence, and differing opinions.
* **Primary Agent Authority** — Keep final decision-making with the primary agent and user.

### How It Works

1. A primary AI agent identifies a task that would benefit from external consultation.
2. The council evaluates the required capabilities and consultation requirements.
3. Eligible providers and consultant models are selected based on configured capabilities, policies, availability, and usage limits.
4. The security layer prepares and sanitizes the minimum necessary context.
5. Independent consultants provide feedback, reviews, challenges, and recommendations.
6. The council consolidates the consultation results and supporting evidence.
7. The primary agent evaluates the feedback and can request clarification or further debate.
8. The primary agent retains control over the final response and decision.

### Integrations

The platform is designed to support multiple integration methods:

* Model Context Protocol (MCP)
* Command-line interface (CLI)
* Web-based administration interface
* API integrations
* Local and remote AI providers
* Extensible provider and capability plugins

### Development

Agent Consultant Council is developed as a modular, multi-repository ecosystem.

Each repository has its own responsibilities, development lifecycle, and releases while following shared architectural contracts and conventions.

For architecture, technical specifications, and development documentation, visit `council-docs`.

### Project Philosophy

The primary AI agent remains in control.

Consultant agents are independent sources of feedback. They can challenge assumptions, identify risks, propose alternatives, and validate technical decisions.

Their responses are advisory, not automatically authoritative.

The goal is not simply to make AI agents communicate with more AI agents. It is to provide a structured, secure, configurable, and cost-aware consultation infrastructure that helps AI agents make better-informed decisions.
