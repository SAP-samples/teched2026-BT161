# Exercise 4 — Complete the Governance Profile

## Overview

A verified agent needs a complete governance record. In this exercise you will review the new agent's fact sheet, identify the gaps, simulate an owner conversation, and use the AI Governance Assistant to fill in the governance section — including EU AI Act classification.

**Duration:** 20 minutes

## Step 1 — Review the Fact Sheet

Open the new agent's fact sheet in AI Agent Hub and review the following fields:

| Field | What to check |
|-------|---------------|
| **Owner** | Is there a responsible person or team assigned? |
| **Architecture Decision** | Is this agent aligned to an approved architecture decision? |
| **Description** | Is it accurate and complete enough for a governance review? |
| **Data Access** | Which systems and data sources does it connect to? |
| **AI Governance Section** | Are the regulatory and risk fields completed? |

Note which fields are empty or incomplete — these are your governance gaps.

## Step 2 — Check Architecture Decision Alignment

1. Locate the **Architecture Decision** field or relation on the fact sheet.
2. If an architecture decision is linked, review it — does the agent's design and purpose align with the decision?
3. If no architecture decision is linked, note this as a gap.

> **Tip:** Use the AI Governance Assistant to ask: *"Is there an architecture decision in our workspace that covers agents of this type?"*

## Step 3 — Simulate the Owner Conversation

In a real governance process, you would reach out to the agent's owner (or the team that built it) to fill in missing information. For this exercise, your trainer has provided the answers you would have received:

**Simulated owner response:**
- *"The agent was built by the [TEAM NAME] team to support [USE CASE]."*
- *"It accesses [SYSTEM/DATA] to perform [ACTION]."*
- *"We consider it a limited-risk agent under the EU AI Act — it supports human decision-making but does not make autonomous decisions with legal or significant personal impact."*
- *"There is no architecture decision formally linked, but it follows the standards from [DECISION NAME]."*

Use these answers in the next step.

## Step 4 — Update the Governance Section via the AI Governance Assistant

1. Open the **AI Governance Assistant**.
2. Ask it to help you update the governance fields based on the owner response. For example:

   > *"Based on this description, help me fill in the AI governance section for this agent. The owner confirmed it is a limited-risk system under the EU AI Act. It supports human decision-making in [USE CASE] and accesses [DATA]."*

3. Review the assistant's suggested updates and apply them to the fact sheet.

## Step 5 — Set the EU AI Act Classification

1. Locate the **EU AI Act** section in the governance profile.
2. Set the **Risk Category** based on the agent's characteristics:

| Risk Category | When it applies |
|---------------|----------------|
| **Unacceptable risk** | Prohibited systems — e.g., biometric mass surveillance, social scoring |
| **High risk** | Systems in regulated sectors or with significant impact on individuals — e.g., HR decisions, credit scoring, critical infrastructure |
| **Limited risk** | Systems with transparency obligations — e.g., chatbots, AI-generated content |
| **Minimal risk** | All other AI systems with no specific regulatory requirements |

3. For this agent, select **Limited risk** based on the owner's description.
4. Save all changes.

> **Note:** The exact EU AI Act fields and classification guidance in AI Agent Hub are subject to confirmation with the responsible product and compliance team. The categories above reflect the EU AI Act (Regulation 2024/1689) as published.

## Summary

The governance profile is complete: owner confirmed, architecture alignment documented, EU AI Act classification set. The agent is ready for verification. In Exercise 5, you will formally approve it.

[Back: Exercise 3](../ex3/README.md) | [Next: Exercise 5 — Verify the Agent](../ex5/README.md)