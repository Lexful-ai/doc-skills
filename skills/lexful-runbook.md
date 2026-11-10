---
name: lexful-runbook
description: Document an operational response to an alert or service outage.
---

# Runbook

Use this workflow to draft or review a runbook for a defined organization or service.

## Inputs

Trigger, affected service, triage evidence, recovery options, escalation roles, and update cadence.

Confirm the organization and subject before reading records. Use authorized sources and link supporting evidence. Mark gaps as pending and distinguish proposed values from verified facts. Ask a focused question when a missing input changes the next action or makes the draft misleading.

## Document layout

- Trigger
- Triage
- Recovery and rollback
- Escalation and communications
- Recovery verification

Use an action-specific title, native headings, ordered lists for sequences, and tables for fields that readers need to compare. Use approved vault references for credentials. Keep reusable guidance free of client-specific links and embeds.

## Format choices

Lead with the trigger and severity in plain text. Number triage in the order responders should perform it. Use a **If you observe | Recovery action | Rollback trigger** table for distinct branches. Keep escalation thresholds and update cadence in short bullets that responders can scan.

Use native editor elements. Keep tables narrow and cells brief. Use a list for a single sequence and prose for context or rationale. Reserve a blockquote for an attributed excerpt or a short stop condition that needs to stand out.

## Acceptance checks

Map observations to actions. Set a rollback threshold and validate recovery from an affected user or endpoint before closing.

Return a reviewable draft with unresolved items clearly marked. If the user requests a Lexful write, confirm the target organization, search for an existing document, and use the native editor or a supported document tool. Reopen the saved record to verify the content and return its link.
