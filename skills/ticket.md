---
name: ticket
description: Route an MSP ticket request to the configured PSA specialist, including ticket review, updates, and documentation drafts.
---

# Ticket dispatcher

Use the provider named by the user or established by the ticket link or conversation. A bare ticket number is ambiguous when multiple PSAs are connected. Resolve the provider and ticket before changing anything. If Halo is the only relevant connected PSA, use it. Ask one focused question when the choice changes the target.

Load `halo-ticket` through the available skill tool for Halo. Carry the ticket ID, organization, requested operation, exact changes, and intended audience into the specialist. Other providers need their own specialist. If the Halo skill or connector is unavailable, state what is missing and use supplied evidence for any requested draft.

For documentation, retrieve the ticket and resolution through the provider specialist. Then load the requested documentation specialist, such as `lexful-sop` for a repeatable fix or `lexful-incident-review` for lessons from an incident. Pass the audience, confirmed cause, remediation, validation, and ticket and action citations. Flag missing evidence and label inferences. Keep drafts in chat unless the user requests a document write.

Example prompts:

- “Triage Halo #2488 as single-user impact and medium urgency. Leave assignment alone.”
- “Use the confirmed fix on Halo #2489 to draft an update to our shared-printer SOP. Cite the resolution and leave the draft unpublished.”
