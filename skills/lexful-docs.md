---
name: lexful-docs
description: Route a Lexful documentation request and start the right MSP document from a title, notes, or a described situation.
---

# Lexful documentation

Use the requested format when the user names it. Otherwise match the outcome they need to the table below. If the outcome is ambiguous and the choice would materially change the draft, use `/lexful-docs-wayfinder`.

| Situation | Command |
| --- | --- |
| Repeatable routine with a known result | `/lexful-sop` |
| Alert or outage response | `/lexful-runbook` |
| Bringing a client into support | `/lexful-client-onboarding` |
| Transferring ownership or ending support | `/lexful-client-offboarding` |
| Getting oriented to a client environment | `/lexful-environment-overview` |
| Planning a specific maintenance event | `/lexful-change-plan` |
| Learning from a resolved incident | `/lexful-incident-review` |
| Planning or recording a restore test | `/lexful-backup-restore-test` |
| Preparing a client review and decisions | `/lexful-qbr-brief` |
| Defining how an agent skill should work | `/lexful-skill-design` |

Load the selected skill using the available skill tool and follow it. Carry forward the resolved client or organization, audience, objective, source links, and requested operation. If skill loading is unavailable, use any supplied specialist text or state which format guidance is missing and proceed with a draft where possible.

Start drafting in the same turn when the format and scope are clear. If several documents would help, start with the one needed for the user's next decision and list any related documents as follow-ups. Check for an existing record before a requested Lexful write. Creating, updating, or sharing a record requires authorization for that operation.

Route explicit requests to stress-test a draft or resolve a blocking judgment call to `/lexful-docs-grill`. Pass the proposed format, evidence, and unresolved choices. Resume the specialist draft with the settled decisions.
