# Lexful Documentation

A native Lexful Skill Kit for drafting and reviewing MSP documentation in Ask Lex. Install the kit in Lexful and use its slash commands out of the box.

| | |
| --- | --- |
| **Author** | Chris Day · Founder, Lexful |
| **Release** | 1.1.0 · 12 November 2026 |

Start with [`/lexful-docs`](skills/lexful-docs.md) and describe what you need. Use [`/lexful-docs-wayfinder`](skills/lexful-docs-wayfinder.md) when you know the situation but are unsure what to document. Use [`/lexful-docs-grill`](skills/lexful-docs-grill.md) to pressure-test a draft or settle decisions that block it. You can also invoke any specialist directly.

Ten standalone skills for drafting or reviewing MSP documents. Each command defines the inputs, document structure, and acceptance checks.

- [`/lexful-sop`](skills/lexful-sop.md) · SOP
- [`/lexful-runbook`](skills/lexful-runbook.md) · Runbook
- [`/lexful-client-onboarding`](skills/lexful-client-onboarding.md) · Client onboarding
- [`/lexful-client-offboarding`](skills/lexful-client-offboarding.md) · Client offboarding
- [`/lexful-environment-overview`](skills/lexful-environment-overview.md) · Environment overview
- [`/lexful-change-plan`](skills/lexful-change-plan.md) · Change plan
- [`/lexful-incident-review`](skills/lexful-incident-review.md) · Incident review
- [`/lexful-backup-restore-test`](skills/lexful-backup-restore-test.md) · Backup & restore test
- [`/lexful-qbr-brief`](skills/lexful-qbr-brief.md) · QBR brief
- [`/lexful-skill-design`](skills/lexful-skill-design.md) · Skill design

For ticket operations, start with [`/ticket`](skills/ticket.md) or invoke [`/halo-ticket`](skills/halo-ticket.md) directly with the Halo connector enabled. Use ticket history as evidence for SOP and incident review drafts.

See [INSTALL.md](INSTALL.md) for GitHub and manual installation.

## Changelog

### 1.1.0 · 12 November 2026

Added the ticket dispatcher and Halo ticket specialist, with ticket-to-SOP examples.

### 1.0.0 · 10 November 2026

Initial kit with ten document specialists, a router, a wayfinder, and a decision grill.
