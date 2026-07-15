# Vulna

register: brand

## Product Purpose
Vulna is a free, open-source, self-hosted platform for security assessment,
vulnerability management, inventory, risk analysis, remediation, and reporting.
The central appliance includes a local Scout and can scan any approved network it
can reach. Remote VulnaScout endpoints run scanners at another site, while
VulnaRelay provides an advanced, scanner-free WireGuard path for centrally
executed scans.

Vulna is the orchestration, safety, asset-correlation, evidence, and workflow
layer around proven open-source scanners such as nmap, Nuclei, testssl.sh, and
OWASP ZAP. It is not another vulnerability engine. The complete stack is hosted
on GitHub under AGPL-3.0.

Positioning used on the site: one self-hosted control plane for assessment,
inventory, risk, remediation, and reporting across every authorized site.

## Current capability pillars

- Scope-controlled discovery, vulnerability, TLS, web, and controlled pentest
  workflows
- Central-only scanning, remote VulnaScout execution, and opt-in VulnaRelay
  tunneling
- Asset, service, software, passive-source, ownership, tag, and group context
- CVE intelligence and explainable, versioned risk scoring
- Finding decisions, remediation units, SLAs, ticket synchronization, and
  targeted verification
- Executive, technical, pentest, and full-spectrum PDF reports plus CSV and JSON
- Granular RBAC, MFA, WebAuthn, OIDC/SAML SSO, SCIM, service accounts, and audit
- Backup, restore, update, rollback, health, offline, privacy, and portability
  operations

## Users
- Homelabbers running racks and Pis at home
- Small businesses without dedicated security budgets
- Open-source / self-hosting enthusiasts (r/selfhosted crowd)
- Security and IT teams that need auditable multi-site assessment without a SaaS
  control plane

They are technical, allergic to SaaS lock-in and marketing fluff, and respect
projects that are honest about hardware requirements, licensing, and safety.

## Brand voice
Sturdy, practical, garage-built-but-professional. Spec-sheet honesty over
marketing superlatives. Three words: utilitarian, dependable, tinker-friendly.

## Anti-references
- Generic SaaS landing pages (gradient text, hero-metric stats, identical icon cards)
- Enterprise-y "book a demo" energy
- Crypto/neon aesthetics

## Strategic principles
- Dark theme (explicit requirement)
- Dark teal #006666 is the brand color and logo color (explicit requirement)
- GitHub is the primary CTA; there is nothing to buy
- Show all three deployment choices clearly: central-only, VulnaScout, and
  VulnaRelay
- Be explicit that native appliance, Scout, and Relay service hosts are currently
  Linux only
- Integrations and aggregate telemetry are opt-in; never imply that data cannot
  leave when an administrator deliberately configures an external destination
- Authorized use only: Vulna assesses systems you own or are permitted to test
