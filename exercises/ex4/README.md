# Exercise 4 — Complete the Governance Profile

## Overview

A verified agent needs a complete governance record. In this exercise you will review your agent's fact sheet for gaps, fill in the AI governance section, use the AI Governance Assistant to create an Architecture Decision Record, and set the AI risk classification.

**Duration:** 20 minutes

## Step 1 — Review the Fact Sheet for Gaps

Open your agent's fact sheet in SAP LeanIX and check the following:

| Field | What to check |
|-------|---------------|
| **Owner** | Is there a responsible person or team assigned? Navigate to the Subscriptions section and confirm or add yourself as Responsible. |
| **Architecture Decision** | Is this agent aligned to an approved architecture decision? Check the Decisions panel in the right sidebar. |
| **Description** | Is it accurate and complete enough for a governance review? |
| **AI Governance and Adoption** section | Are AI Agent Type, AI Agent Nature, AI Risk, and Approval State filled in? |

Note which fields are empty — these are your governance gaps.

## Step 2 — Fill in the AI Governance and Adoption Section

1. In the fact sheet, open the **AI Governance and Adoption** section.
2. Set the following fields based on what you know about your agent:

   | Field | Description | Example value |
   |-------|-------------|---------------|
   | **AI Agent Type** | How the agent interacts with users | Conversational |
   | **AI Agent Nature** | How it was built | Custom |
   | **AI Risk** | Risk level aligned with EU AI Act categories | Limited |
   | **Approval State** | Governance status — updated automatically on verification | *(leave for Exercise 5)* |

3. Save your changes.

## Step 3 — Create an Architecture Decision via the AI Governance Assistant

GlobalFlex AG requires that every agent in the inventory is linked to an Architecture Decision Record (ADR) documenting the governance rationale.

1. Navigate to **More** (top header) → **AI Governance Assistant** (also called EA Assistant).
2. Use the following prompt to generate an ADR for your agent:

   > *"Create an architecture decision record for [your agent's name] based on the AI governance and adoption insights."*

3. Review the generated ADR — it will include a Context, Decision, and Consequences section populated from your fact sheet data.
4. **Save** the ADR. It will be linked to your agent's fact sheet automatically.
5. Return to the fact sheet and confirm the architecture decision appears in the **Decisions** panel on the right sidebar.

> **Why this matters:** An ADR creates an auditable record of *why* this agent was approved — not just *that* it was. Future reviewers (and auditors) can see the reasoning, not just the badge.

## Step 4 — Set the AI Risk Classification

In the **AI Governance and Adoption** section, the **AI Risk** field captures risk classification aligned with the EU AI Act (Regulation 2024/1689):

| AI Risk value | When it applies |
|---------------|----------------|
| **High** | Significant impact on individuals or regulated sectors — e.g., HR decisions, credit scoring, critical infrastructure |
| **Limited** | Transparency obligations — e.g., chatbots, recommendation engines, AI-generated content |

For GlobalFlex AG's procurement assistant scenario, select **Limited** — it supports human decision-making but does not make autonomous decisions with legal or significant personal impact.

Save all changes.

> **Note:** Confirm the exact field options and any additional EU AI Act-specific fields with the responsible product and compliance team before your production governance rollout.

## Summary

The governance profile is complete: subscription owner set, AI governance section filled in, ADR created and linked, AI risk classified. The agent is ready for verification. In Exercise 5, you will formally approve it.

[Back: Exercise 3](../ex3/README.md) | [Next: Exercise 5 — Verify the Agent](../ex5/README.md)
