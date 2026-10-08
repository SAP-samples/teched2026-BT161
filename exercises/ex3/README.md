# Exercise 3 — Complete the Governance Profile

## Overview

Your agent is now in the inventory but its governance record is incomplete. In this exercise you will fill in what the EA team can determine independently — assign yourself as an observer, and link the agent to the Architecture Decision Record you created in Exercise 1. Fields that only the agent's business owner can answer (AI Risk, AI Model, Business Criticality, Functional Fit, AI Agent Business Value, Technical Fit) will be collected in the next exercise via a survey.

**Duration:** 15 minutes

## Step 1 — Review the Fact Sheet for Gaps

Open your agent's fact sheet in SAP LeanIX and check the following:

| Field | What to check |
|-------|---------------|
| **Description** | Should be pre-filled from the discovery data. Confirm it accurately describes what this agent does. |
| **Responsible subscriber** | Auto-assigned to the person who deployed this agent in Joule Studio. Check who is listed. |
| **Build Type** | Should be pre-filled as **Custom** from the deployment metadata. Confirm it is set. |
| **Architecture Decision** | Not yet linked. You will link it in Step 4. |
| **AI Risk** | Empty — requires the agent's business owner. Goes to survey in Exercise 4. |
| **AI Model** | Empty — requires the agent's business owner. Goes to survey in Exercise 4. |
| **Business Criticality** | Empty — requires the agent's business owner. Goes to survey in Exercise 4. |
| **Functional Fit** | Empty — requires the agent's business owner. Goes to survey in Exercise 4. |
| **AI Agent Business Value** | Empty — requires the agent's business owner. Goes to survey in Exercise 4. |
| **Technical Fit** | Empty — requires the agent's business owner. Goes to survey in Exercise 4. |

## Step 2 — Add Yourself as Observer

The **Responsible** subscriber is already set to the person who deployed the agent. As the EA team member reviewing this agent, your role is **Observer**.

1. Navigate to the **Subscriptions** section of the fact sheet.
2. Add yourself as **Observer** subscriber.

> **Why Observer, not Responsible?** The Responsible role belongs to the person accountable for the agent — the business owner or deploying team. The EA team oversees governance but does not own the agent itself. Observer means you will be notified of changes without taking on operational accountability.

## Step 3 — Validate the Description

The agent description was pulled in automatically during discovery. Before proceeding:

1. Read the description carefully.
2. Confirm it accurately reflects what this agent does at GlobalFlex AG — not just a generic template.
3. If the description is thin or inaccurate, you can use LeanIX's built-in AI to improve it: hover over the Description field in edit mode and look for the **AI-generate** option (sparkle icon).

## Step 4 — Link the Architecture Decision

Your agent is subject to the policy you documented in Exercise 1. Now link them.

1. Navigate to **More** (top header) → **EA Assistant** (or open the ADR directly from **Architecture Decisions**).
2. Find the ADR you created in Exercise 1 — search for your participant number.
3. Open the ADR and navigate to the **Impacted Fact Sheets** section.
4. Add your agent's fact sheet to the ADR.

> **Why from the ADR side?** Architecture decisions are linked by adding fact sheets to the ADR — not by editing individual fact sheets. This keeps the decision as the single source of truth: all agents subject to a policy are listed in one place.

5. Return to your agent's fact sheet and confirm the ADR now appears in the **Decisions** panel in the right sidebar.

## Summary

The EA team's portion of the governance record is now complete: you are assigned as Observer, the description is confirmed, and the ADR has been linked. The remaining fields — AI Risk, AI Model, Business Criticality, Functional Fit, AI Agent Business Value, and Technical Fit — require input from the agent's business owner. In Exercise 4, you will send them a survey to collect that information.

[Back: Exercise 2](../ex2/README.md) | [Next: Exercise 4 — Collect Missing Information via Survey](../ex4/README.md)
