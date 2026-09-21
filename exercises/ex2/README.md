# Exercise 2 — From Discovery to Inventory

## Overview

Your agent is waiting in the Discovery Inbox. In this exercise you will review the discovery details, check the usage analytics, and add your agent to the governed inventory.

**Duration:** 15 minutes

## Background

The AI Agent Discovery Inbox is where AI Agent Hub surfaces everything it has found. Agents arrive here from connected systems — whether they are standard SAP agents discovered automatically, or agents deployed by teams in your organization. Both go through the same review-and-approve process.

Your agent was pre-loaded for this workshop to simulate a real discovery event: the EA team at GlobalFlex AG has no prior record of it, and it is your job to evaluate whether it belongs in the governed inventory.

## Step 1 — Open the AI Agent Discovery Inbox

1. In SAP LeanIX, navigate to:
   **Inventory → Inventory Tools *(top right)* → Discovery Inbox → AI Agent Discovery**
2. Apply the filter **Status: Action Needed** to focus on unreviewed agents.
3. Locate your agent using your participant number.

## Step 2 — Review the Discovery Details

In the detail panel for your agent, review:

- **Description** — what the agent claims to do
- **Creation Timestamp** — when it first appeared in the landscape
- **Discovered Fact Sheets** — fact sheets AI Agent Hub has automatically suggested as related
- **Additional Suggestions** — other fact sheets the system thinks may be relevant

Read through the details. Treat yourself as an EA team member seeing this agent for the first time.

## Step 3 — Compare with a Standard SAP Agent

Before adding your agent, briefly compare it with a standard SAP agent in the same inbox:

- Standard SAP agents often have **Discovered Fact Sheets** already suggested (linked IT components, business capabilities)
- Your agent may have fewer automatic suggestions — this reflects real-world governance: agents discovered with less metadata require more manual investigation

This difference in discovery richness is normal and expected.

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
