# Exercise 4 — Complete the Governance Profile

## Overview

A verified agent needs a complete governance record. In this exercise you will review the new agent's fact sheet, identify the gaps, simulate an owner conversation, and use the AI Governance Assistant to fill in the governance section — including AI risk classification aligned with the EU AI Act.

**Duration:** 20 minutes

## Step 1 — Review the Fact Sheet

Open the new agent's fact sheet in AI Agent Hub and review the following fields:

| Field | What to check |
|-------|---------------|
| **Owner** | Is there a responsible person or team assigned? |
| **Architecture Decision** | Is this agent aligned to an approved architecture decision? |
| **Description** | Is it accurate and complete enough for a governance review? |
| **Data Access** | Which systems and data sources does it connect to? |
| **AI Governance and Adoption** section | Are the AI Agent Type, AI Agent Nature, AI Risk, and Approval State fields completed? |

Note which fields are empty or incomplete — these are your governance gaps.

## Step 2 — Check Architecture Decision Alignment

1. Locate the **Architecture Decision** relation on the fact sheet, or check the **Decisions** panel in the right sidebar.
2. If an architecture decision is linked, review it — does the agent's design and purpose align with the decision? Architecture decisions in AI Agent Hub follow the format *ADR-XX-NNN: [Title]* and include a Context, Decision, and Consequences section.
3. If no architecture decision is linked, note this as a gap.

> **Tip:** Use the AI Governance Assistant to ask: *"Is there an architecture decision in our workspace that covers agents of this type?"*

## Step 3 — Simulate the Owner Conversation

In a real governance process, you would reach out to the agent's owner (or the team that built it) to fill in missing information. For this exercise, your trainer has provided the answers you would have received:

**Simulated owner response:**
- *"The agent was built by the [TEAM NAME] team to support [USE CASE]."*
- *"It accesses [SYSTEM/DATA] to perform [ACTION]."*
- *"We consider it a limited-risk system — it supports human decision-making but does not make autonomous decisions with legal or significant personal impact."*
- *"There is no architecture decision formally linked, but it follows the standards from [DECISION NAME]."*

Use these answers in the next step.

## Step 4 — Update the Governance Section via the AI Governance Assistant

1. Open the **AI Governance Assistant**.
2. Ask it to help you update the governance fields based on the owner response. For example:

   > *"Based on this description, help me fill in the AI Governance and Adoption section for this agent. The owner confirmed it is a limited-risk system that supports human decision-making in [USE CASE] and accesses [DATA]."*

3. Review the assistant's suggested updates and apply them to the fact sheet.

## Step 5 — Set the AI Risk Classification

1. In the **AI Governance and Adoption** section, locate the **AI Risk** field.
2. Set the classification based on the agent's characteristics:

| AI Risk value | When it applies |
|---------------|----------------|
| **High** | Systems with significant impact on individuals or operating in regulated sectors — e.g., HR decisions, credit scoring, critical infrastructure |
| **Limited** | Systems with transparency obligations — e.g., chatbots, recommendation engines, AI-generated content |

3. For this agent, select **Limited** based on the owner's description.
4. Also confirm the **AI Agent Type** (e.g., Conversational) and **AI Agent Nature** (e.g., Pre-Built or Custom) fields are completed.
5. Save all changes.

> **Note:** The **AI Risk** field in AI Agent Hub captures risk classification aligned with the EU AI Act (Regulation 2024/1689). Confirm the exact field options and any additional EU AI Act-specific fields with the responsible product and compliance team before your production governance rollout.

## Summary

The governance profile is complete: owner confirmed, architecture alignment documented, AI risk classification set. The agent is ready for verification. In Exercise 5, you will formally approve it.

[Back: Exercise 3](../ex3/README.md) | [Next: Exercise 5 — Verify the Agent](../ex5/README.md)