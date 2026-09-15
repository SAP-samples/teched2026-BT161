# Exercise 2 — From Discovery to Inventory

## Overview

Your agent is now live in Joule Work. In this exercise you will open the AI Agent Discovery Inbox and find it — alongside standard SAP agents that were discovered automatically from GlobalFlex AG's SAP system. You will review the discovery details and add your agent to the governed inventory.

**Duration:** 15 minutes

## Background

The AI Agent Discovery Inbox is where AI Agent Hub surfaces everything it has found. Two types of agents appear here:
- **Standard SAP agents** — discovered automatically from the connected SAP system; these often arrive already linked to relevant IT components and business capabilities
- **Custom agents** — deployed by teams in Joule Work; these arrive with less context attached and typically require more governance work

Both types go through the same review-and-approve process. Your agent is the custom one — the one GlobalFlex AG's EA team (you) has no prior record of.

## Step 1 — Open the AI Agent Discovery Inbox

1. In SAP LeanIX, navigate to:
   **Inventory → Inventory Tools *(top right)* → Discovery Inbox → AI Agent Discovery**
2. Apply the filter **Status: Action Needed** to focus on unreviewed agents.
3. You should see a mix of standard SAP agents and the custom agent you deployed in Exercise 1.

## Step 2 — Identify Your Agent

1. Locate your agent by name — it includes your 3-digit participant code.
2. Open it. Notice the difference in the detail panel compared to a standard SAP agent:
   - Standard agents often have **Discovered Fact Sheets** already suggested (linked IT components, business capabilities)
   - Your custom agent may have fewer automatic suggestions — this reflects real-world governance: custom agents require more manual investigation

## Step 3 — Review the Discovery Details

In the detail panel for your agent, review:

- **Description** — what the agent claims to do
- **Creation Timestamp** — when it first appeared in the landscape
- **Integration source** — confirms this came from Joule Work
- **Discovered Fact Sheets** — fact sheets AI Agent Hub has automatically suggested as related
- **Additional Suggestions** — other fact sheets the system thinks may be relevant

Read through the details. Treat yourself as an EA team member seeing this agent for the first time.

## Step 4 — Check the Analytics

1. From the discovery item, open the agent's fact sheet and navigate to the **Analytics** tab.
2. Review the usage data AI Agent Hub has collected:
   - **Total Sessions**, **First Active / Last Active**, **Average Tokens per Session**

> **Think about it:** Even a brand-new agent can start accumulating sessions before governance catches up. In a real scenario — what process would you put in place to close that gap?

## Step 5 — Add to Inventory

1. Return to the discovery item and click **Add to Inventory**.
2. The agent is now part of the governed inventory — status changes to **Unverified**.
3. Verify that a new AI Agent fact sheet has been created, including its relationship to any suggested IT components.

## Summary

Your agent is now in the inventory alongside the standard SAP agents. In Exercise 3, you will use the AI Governance Assistant to find out whether GlobalFlex AG already has something similar — and document the succession relationship.

[Back: Exercise 1](../ex1/README.md) | [Next: Exercise 3 — Find Similar Agents & Set a Predecessor](../ex3/README.md)
