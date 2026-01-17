# Gonzalo Melosevich · Infrastructure & Data Showcase

**gonzalo-labs** is a public workspace for exploring and sharing **cloud platform, infrastructure, and data engineering patterns** inspired by real-world, enterprise-scale systems.

The repositories in this organization focus on:
- AWS cloud platform design
- Infrastructure as Code (Terraform)
- Secure CI/CD with OIDC (GitHub Actions)
- Multi-account AWS architectures
- Clear separation between platform infrastructure and application code

## What you’ll find here

The repositories in this organization demonstrate concrete, real-world patterns such as:

- **Infrastructure as Code with GitHub Actions**  
  See how I design and operate a secure AWS platform using Terraform and GitHub Actions with OIDC authentication:  
  👉 https://github.com/gonzalo-labs/aws-cloud-platform-iac-github-actions

- **Secure CI/CD without long-lived credentials**  
  Examples of CI/CD pipelines that authenticate to AWS using short-lived credentials and strict trust boundaries.

- **Multi-account AWS architectures**  
  Patterns for separating environments (dev / prod), minimizing blast radius, and enforcing guardrails across accounts.

- **Clear separation between platform infrastructure and application code**  
  Infrastructure is provisioned centrally via IaC, while application and Lambda code is deployed independently within defined boundaries.

- **Data ingestion and analytics building blocks**  
  Lightweight, observable services for ingesting public and external data sources into AWS-managed analytics platforms.

## Design philosophy

- **Security first**: no long-lived credentials in CI/CD
- **Explicit boundaries**: infrastructure and runtime code live in separate concerns
- **Predictable lifecycle**: changes are scoped, auditable, and reversible
- **Practical realism**: patterns reflect how teams operate in production, not just tutorials

This organization is intentionally opinionated and minimal, aiming to show *how things fit together* rather than maximizing features.

---

Maintained by **Gonzalo Melosevich F.** as a collection of reference patterns and experiments.