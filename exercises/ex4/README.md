# Exercise 4 — Prepare the Fact Sheet

## Overview

A complete governance record is what makes verification meaningful. In this exercise you will fill in what the EA team can determine independently — assign ownership, use LeanIX AI to draft the agent description, and create an Architecture Decision Record. Fields that only the agent's business owner can answer (AI Agent Type, AI Risk, AI Model) will be collected in the next exercise via a survey.

**Duration:** 15 minutes

## Step 1 — Review the Fact Sheet for Gaps

Open your agent's fact sheet in SAP LeanIX and check the following:

| Field | What to check |
|-------|---------------|
| **Description** | Is it accurate and complete enough for a governance review? If thin or missing — generate it in the next step. |
| **Owner** | Is there a responsible person or team assigned? Navigate to the Subscriptions section. |
| **Architecture Decision** | Is this agent aligned to an approved architecture decision? Check the Decisions panel in the right sidebar. |
| **AI Agent Type** | Is this field set? If not — this goes to the survey in Exercise 5. |
| **AI Risk** | Is a risk level assigned? If not — this also goes to the survey. |
| **AI Model** | Is the underlying model documented? If not — survey. |

Note which fields are empty. The ones only the agent's owner can answer will be handled in Exercise 5.

## Step 2 — Assign Yourself as Responsible

1. Navigate to the **Subscriptions** tab on the fact sheet.
2. Add yourself as **Responsible** subscriber.
3. This records that you, as the EA team member, are the governance owner for this agent — separate from the business owner the survey will identify.

## Step 3 — Generate a Description Using LeanIX AI

If the agent description is missing or too thin for a governance review, LeanIX can draft one for you using built-in AI.

1. Open the **Edit** view of the fact sheet (click the pencil or hover the Description field to reveal the edit option).
2. Look for the **AI-generate** option next to the Description field — usually shown as a sparkle icon or a "Generate" button.
3. Click it. LeanIX drafts a description based on the agent name, its linked fact sheets, and available metadata.
4. Review the generated text — adjust it if needed to accurately reflect what this agent does at GlobalFlex AG.
5. Save the description.

> **Why this matters:** A description generated from metadata is a starting point, not a final answer. Your job as the EA team is to verify it against what you know and correct anything that does not reflect reality.

## Step 4 — Create an Architecture Decision via the EA Assistant

GlobalFlex AG requires that every agent in the inventory is linked to an Architecture Decision Record documenting the governance rationale.

1. Navigate to **More** (top header) → **EA Assistant**.
2. Use the following prompt:

   > *"Create an architecture decision record for [your agent's name] based on the AI governance and adoption insights."*

3. Review the generated ADR — it will include a Context, Decision, and Consequences section populated from your fact sheet data.
4. **Save** the ADR. It links to your agent's fact sheet automatically.
5. Confirm the architecture decision appears in the **Decisions** panel on the right sidebar.

## Summary

The EA team's portion of the governance record is complete: you are the responsible owner, the description is documented, and an ADR has been created. The remaining fields — AI Agent Type, AI Risk, and AI Model — require input from the agent's business owner. In Exercise 5, you will send them a survey to collect that information.

[Back: Exercise 3](../ex3/README.md) | [Next: Exercise 5 — Collect Missing Information via Survey](../ex5/README.md)
