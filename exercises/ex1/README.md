# Exercise 1 — The Governance Dashboard & Deploy Your Agent

## Overview

Before taking any governance action, you need to understand what is happening in your landscape. Then you will do something that makes this workshop unique: you will deploy your own agent in Joule Work, which will trigger its appearance in the AI Agent Discovery Inbox — the same agent you will govern for the rest of the session.

**Duration:** 15 minutes

## Background

AI Agent Hub in SAP LeanIX continuously discovers agents across your connected SAP and third-party environments. It surfaces two types of agents in the inbox:
- **Standard SAP agents** — discovered automatically from your connected SAP system (pre-loaded for this workshop)
- **Custom agents** — built and deployed by teams in your organization using Joule Work (you will create one shortly)

Both types arrive in the same inbox and go through the same governance process. This is by design: governance applies regardless of who built the agent.

## Step 1 — Review the Dashboard

1. In SAP LeanIX, open the **AI Agent Hub Dashboard**.
2. Take a moment to read the overview. You should see:
   - Total agents, MCP servers, and LLMs in the inventory
   - Agents by verification status (verified, unverified)
   - Agents by discovery source — SAP system, Joule Work, third-party (e.g., ServiceNow)
   - Recent governance activity

> **What you are seeing:** GlobalFlex AG has already connected its SAP system to AI Agent Hub. Standard agents have been discovered automatically. The inbox is waiting for your attention.

## Step 2 — Explore the Inventory

1. Navigate briefly to the **Inventory** view.
2. Use the filter to see agents grouped by type:
   - **SAP Standard Agents** — delivered by SAP, part of licensed solutions
   - **Custom Agents** — built with Joule Work by teams in your organization
   - **Third-Party Agents** — running in external environments (e.g., ServiceNow, Microsoft)
3. Return to the Dashboard when you are done.

## Step 3 — Deploy Your Workshop Agent in Joule Work

Each participant will deploy their own agent so that everyone governs a unique fact sheet — avoiding conflicts in the shared workspace.

1. Switch to the **Joule Work** browser tab.
2. Navigate to the **develop** section (or the agent builder area — your trainer will point this out if the label differs).
3. Open the **starter agent template** provided for this workshop.
4. Rename the agent by appending your **3-digit participant code** to the name — for example, if the template is called *"GlobalFlex Procurement Assistant"*, rename it *"GlobalFlex Procurement Assistant – ABC"* (replacing ABC with your code from your session card).
5. **Publish / Deploy** the agent.

Your agent is now live in Joule Work. In Exercise 2, you will see it appear in the AI Agent Discovery Inbox.

> **What just happened:** Publishing the agent in Joule Work triggers the AI Agent Hub integration. The agent is detected and queued for governance review — just like it would be if a colleague in GlobalFlex AG's procurement team had deployed it without telling the EA team.

## Summary

You have oriented yourself in the AI governance dashboard and deployed the agent you will govern throughout this workshop. In Exercise 2, you will open the AI Agent Discovery Inbox and begin the governance process.

[Back: Getting Started](../ex0/README.md) | [Next: Exercise 2 — From Discovery to Inventory](../ex2/README.md)
