# Mariusz Borowiak

**Solution Architect — Supply Chain Planning & Logistics** · design authority, integrations & LLM agent systems · United Kingdom (remote)

I own design and architecture decisions for enterprise supply chain platforms — most recently the integration strategy for a **3-country RELEX demand planning rollout** (file & API integrations, data migration, cutover, hypercare) and European rollout standards (API standards, integration patterns, cyber security practices). I capture requirements with business leads in early-stage workshops and work shoulder-to-shoulder with the engineers who build, keeping delivery to the agreed designs and standards.

Ten years in supply chains from the ground up: warehouse floor → 160-truck transport planning → national SAP support → software development → solution architecture.

**Seeking: Forward Deployed Engineer / AI-forward delivery roles** — requirements, architecture, and agent systems that ship.

## AI agent systems

**Agent harness design** · **agent skills engineering** — human-in-the-loop / human-gated approvals · RAG · document classification & extraction · structured-output validation · prompt engineering · tool use & orchestration · model-tier routing & fallback design

Current builds — private deployments, public repos land here soon:

- **Papierman** *(papierman.com, in development)* — single-tenant, EEA-resident document archive for regulated records: one Docker unit image per customer from a private registry, HashiCorp Vault secrets, Keycloak OIDC, LLM classification intake on a hardened agent harness (human-approve gates, quarantine, attempt caps)
- **Autonomous purchasing agent** — buys online without ever touching money unattended: a human-gated payment approval state machine (approve/decline cards, approval boundaries, timeout-cancel, idempotent retry), browser automation, voice in/out
- **Video → knowledge articles** — transcript → LLM-structured chaptered articles → self-hosted knowledge library; event-ledger job log, crash-safe requeue

## Supply chain

RELEX demand planning · SAP ECC6 · WMS/ERP · EDI ordering · multi-country rollout architecture (discovery → integrations → cutover → hypercare)

## Stack

`Python` `Go` `C#/.NET` `SQL (PostgreSQL / SQL Server)` `AWS` `Docker` `SSIS` `PowerShell / Bash` `GitHub`

## Public work

- [**Agent_Memory_system**](https://github.com/borowiak-m/Agent_Memory_system) — knowledge-base system for the [Pi coding agent](https://pi.dev): accumulates insights, decisions and domain knowledge across sessions

## Contact

<mariusz.borowiak@proton.me> · [linkedin.com/in/linked-mariusz-borowiak](https://linkedin.com/in/linked-mariusz-borowiak)
