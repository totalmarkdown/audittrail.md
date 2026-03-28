# AUDITTRAIL.md

> *Defines tamper-proof logging for every action an AI agent takes*

[![License: CC0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
[![Part of agent-md-specs](https://img.shields.io/badge/part%20of-agent--md--specs-blue)](https://github.com/totalmarkdown/agent-md-specs)
[![Maintained by TotalMarkdown](https://img.shields.io/badge/maintained%20by-TotalMarkdown.ai-8B5CF6)](https://totalmarkdown.ai)

**Maintained by TotalMarkdown.ai**
· License: CC0 1.0 Universal — Public Domain
· Part of [agent-md-specs](https://github.com/totalmarkdown/agent-md-specs)
· [Discussions](https://github.com/totalmarkdown/audittrail.md/discussions)

> TotalMarkdown.ai is currently in development. Star this repo to follow progress.

---

> **Canonical Source:** This spec is maintained in the main
> [agent-md-specs](https://github.com/totalmarkdown/agent-md-specs) repository.
> This repo is an auto-synced mirror for easy discovery and download.
> To report issues or submit changes, please open a PR or issue on the
> [main repository](https://github.com/totalmarkdown/agent-md-specs).

## What is AUDITTRAIL.md?

AUDITTRAIL.md is the accountability spec. It defines how every consequential agent action is recorded in a tamper-resistant format — hash-chain integrity, cryptographic signing, compliance-specific retention periods (GDPR 3 years, HIPAA 6 years, SOX 7 years, EU AI Act 10 years), and non-repudiation binding back to the human who authorized the agent.

When an AI agent acts autonomously, organizations need irrefutable proof of what happened, when, and under whose authority. AUDITTRAIL.md provides this.

Create an AUDITTRAIL.md for any agent in a regulated industry, making decisions affecting real people, or deployed in environments requiring audit compliance.

---

## Quick Start

```bash
curl -O https://raw.githubusercontent.com/totalmarkdown/audittrail.md/main/AUDITTRAIL.md
```

Add to your project root and customize for your agent.

---

## When to use AUDITTRAIL.md

- Any agent in a regulated industry (finance, healthcare, legal)
- Agents that make decisions affecting real people or systems
- Enterprise deployments requiring audit compliance (SOC 2, SOX, GDPR)

---

## Where it fits

Works alongside INTENT.md (intent hash included in each audit entry), ATTESTATION.md (entries signed with agent's credential), DELEGATION.md (delegation reference in each entry), PROVENANCE.md (data lineage tracking), and ENFORCEMENT.md (audit trail verifies compliance).

---

## The Full Spec

→ [AUDITTRAIL.md](./AUDITTRAIL.md)

---

## Part of agent-md-specs

One of 178 specs in [agent-md-specs](https://github.com/totalmarkdown/agent-md-specs)
— the open standard library covering every dimension of AI agent configuration.

---

## Contributing

1. Open an issue describing your proposed change
2. Fork and make your edit
3. Open a PR — all contributions must be CC0

---

## License

[CC0 1.0 Universal](./LICENSE) — Public Domain.
Use freely for any purpose, no attribution required.

---

*Maintained by TotalMarkdown.ai*
*Part of [agent-md-specs](https://github.com/totalmarkdown/agent-md-specs)*
