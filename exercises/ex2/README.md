# Exercise 2 — From Discovery to Inventory

## Overview

Discovery is just an alert. Governance starts when you decide what to do about it. In this exercise you will open the inbox, investigate a newly discovered agent, review its analytics, and add it to your governed inventory.

**Duration:** 15 minutes

## Step 1 — Open the Inbox

1. In AI Agent Hub, navigate to the **Inbox**.
2. You will see a list of items requiring your attention. Locate the discovery notification for the agent your trainer has pre-identified for this exercise.
3. Open the discovery item.

## Step 2 — Review the Discovery Details

The discovery item shows you what AI Agent Hub found automatically:

- **Agent name and description** — what the agent claims to do
- **Source environment** — where it was found (SAP BTP, S/4HANA, third-party system, etc.)
- **Discovery date** — when it first appeared in the landscape
- **Data connections** — which systems and APIs the agent has access to

Read through the details. Treat yourself as someone seeing this agent for the first time.

## Step 3 — Check the Analytics

1. From the discovery item, navigate to the **Analytics** tab or section.
2. Review available usage data:
   - How often has this agent been invoked?
   - Which users or teams have been using it?
   - What data has it accessed?

> **Think about it:** If an agent has been running for 3 months with 400+ invocations and no governance record, what does that tell you about your organization's AI adoption patterns?

## Step 4 — Add to Inventory

1. Once you have reviewed the discovery details and analytics, locate the **Add to Inventory** action.
2. Confirm the action. The agent is now part of your governed inventory — it has moved from "discovered" to "under governance review."
3. Notice that the agent's status in the inventory is now **Unverified** — it is acknowledged, but not yet approved to run.

## Summary

The agent is now in your inventory. In Exercise 3, you will use the AI Governance Assistant to find out whether your organization already has agents doing something similar — and whether one of them should be the predecessor of this new one.

[Back: Exercise 1](../ex1/README.md) | [Next: Exercise 3 — Find Similar Agents & Set a Predecessor](../ex3/README.md)