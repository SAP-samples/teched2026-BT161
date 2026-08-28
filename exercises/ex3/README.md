# Exercise 3 — Find Similar Agents & Set a Predecessor

## Overview

Before approving a new agent, a responsible governance team asks: do we already have something that does this? Duplicate agents create unnecessary complexity, split ownership, and increase your risk surface. In this exercise you will use the AI Governance Assistant to search your landscape for similar agents, and then link the right one as a predecessor of the new agent.

**Duration:** 15 minutes

## Step 1 — Open the AI Governance Assistant

1. In AI Agent Hub, open the **AI Governance Assistant**.
2. The assistant has access to your full agent inventory, fact sheet data, and architectural context from your connected LeanIX workspace.

## Step 2 — Query for Similar Agents

Ask the assistant a question in natural language. Try something like:

> *"Are there any other agents in our landscape that support the same business capabilities as [AGENT NAME]? Do any have a similar description or data access pattern?"*

Or more specifically:

> *"Show me agents in the inventory related to [business capability]. Which ones are still active and which are phased out?"*

Review the results. The assistant should surface one or more candidate agents with overlapping scope.

## Step 3 — Review the Candidate Agent

1. From the assistant's response, click through to the fact sheet of the most relevant candidate agent.
2. Review its details — including the **Analytics** tab to understand its usage history:
   - **Total Sessions**, **First Active**, **Last Active**, **Average Tokens per Session** — how long has it been in use and how heavily?
   - **Lifecycle status** — is it Active, Phase In, or Phase Out?
   - **Description** — does it overlap significantly with the new agent?
   - **Owner** — is there an accountable person?
   - **Approval State** — was it ever formally verified?
3. Also check the **Decisions** panel in the right sidebar — it shows architecture decisions already linked to this agent.
4. In this exercise, the candidate agent has already been marked as **Phase Out** — it is being replaced, and the new agent is its successor.

## Step 4 — Set the Predecessor Relationship

1. Return to the fact sheet of the **new agent** (the one you added to inventory in Exercise 2).
2. Locate the **Predecessor** field in the fact sheet.
3. Link the phased-out agent as the predecessor of the new agent.
4. Save the change.

> **Why this matters:** Setting a predecessor creates a traceable succession chain. Users who relied on the old agent can be pointed to the new one, and auditors can follow the governance history across agent generations.

## Summary

You have confirmed that the new agent is a legitimate successor to an existing one — not a duplicate. The predecessor is documented. In Exercise 4, you will complete the governance profile of the new agent before it can be verified.

[Back: Exercise 2](../ex2/README.md) | [Next: Exercise 4 — Complete the Governance Profile](../ex4/README.md)