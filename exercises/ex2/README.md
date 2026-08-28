# Exercise 2 — From Discovery to Inventory

## Overview

Discovery is just an alert. Governance starts when you decide what to do about it. In this exercise you will open the AI Agent Discovery Inbox, investigate a newly discovered agent, review its usage analytics, and add it to your governed inventory.

**Duration:** 15 minutes

## Step 1 — Open the AI Agent Discovery Inbox

1. In AI Agent Hub, navigate to the **AI Agent Discovery Inbox**.
2. The inbox groups items by status: **Action Needed**, **Linked**, and **Rejected**. Focus on the **Action Needed** items.
3. Locate the discovery notification for the agent your trainer has pre-identified for this exercise and open it.

## Step 2 — Review the Discovery Details

The discovery item shows you what AI Agent Hub found automatically. Review the following in the detail panel:

- **Description** — what the agent claims to do
- **Creation Timestamp** — when it first appeared in the landscape
- **Integration source** — which system or service it was discovered in (e.g., SAP BTP, Microsoft Azure, AWS, ServiceNow)
- **Discovered Fact Sheets** — fact sheets AI Agent Hub has automatically suggested as related (e.g., a linked business capability or SAP application)
- **Additional Suggestions** — other fact sheets the system thinks may be relevant

Read through the details. Treat yourself as someone seeing this agent for the first time.

> **Think about it:** The "Discovered Fact Sheets" section shows what AI Agent Hub was able to infer automatically. What does a good automatic match tell you — and what does a missing match tell you?

## Step 3 — Check the Analytics

1. From the discovery item, open the agent's fact sheet and navigate to the **Analytics** tab.
2. Review the usage data AI Agent Hub has collected:
   - **Total Sessions** — how many times has this agent been invoked?
   - **First Active / Last Active** — how long has it been running?
   - **Average Tokens per Session** — a proxy for how intensive the interactions are

> **Think about it:** If an agent has been running for several months with hundreds of sessions and no governance record, what does that tell you about your organization's AI adoption patterns?

## Step 4 — Add to Inventory

1. Once you have reviewed the discovery details and analytics, return to the discovery item and click **Add to Inventory**.
2. The agent is now part of your governed inventory — it has moved from "discovered" to "under governance review."
3. Notice that the agent's status in the inventory is now **Unverified** — it is acknowledged, but not yet approved to run.

## Summary

The agent is now in your inventory. In Exercise 3, you will use the AI Governance Assistant to find out whether your organization already has agents doing something similar — and whether one of them should be the predecessor of this new one.

[Back: Exercise 1](../ex1/README.md) | [Next: Exercise 3 — Find Similar Agents & Set a Predecessor](../ex3/README.md)