# gonzalo-labs

**gonzalo-labs** is a public workspace for exploring and sharing **cloud platform, infrastructure, and data engineering patterns** inspired by real-world, enterprise-scale systems.

The repositories in this organization focus on:
- AWS cloud platform design
- Infrastructure as Code (Terraform)
- Secure CI/CD with OIDC (GitHub Actions)
- Multi-account AWS architectures
- Clear separation between platform infrastructure and application code

## What you’ll find here

### 🔧 Platform & Infrastructure Patterns
Reference implementations that demonstrate how mature platform teams:
- bootstrap AWS accounts securely
- manage shared infrastructure with low blast radius
- enforce guardrails via IAM and policy-as-code
- operate multi-environment (dev / prod) setups

### ⚙️ CI/CD & Automation
Examples of:
- GitHub Actions with AWS OIDC authentication
- environment-based deployments with approvals
- least-privilege deployment roles
- promotion flows aligned with enterprise governance

### 📊 Data & Analytics Building Blocks
Small, focused services that show how to:
- ingest public and external data sources
- build observable, idempotent data pipelines
- keep application code decoupled from infrastructure provisioning

## Design philosophy

- **Security first**: no long-lived credentials in CI/CD
- **Explicit boundaries**: infrastructure and runtime code live in separate concerns
- **Predictable lifecycle**: changes are scoped, auditable, and reversible
- **Practical realism**: patterns reflect how teams operate in production, not just tutorials

This organization is intentionally opinionated and minimal, aiming to show *how things fit together* rather than maximizing features.

---

Maintained by **Gonzalo Melosevich F.** as a collection of reference patterns and experiments.