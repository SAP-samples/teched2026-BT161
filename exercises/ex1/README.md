# Exercise 1 — The Governance Dashboard

## Overview

Before taking any governance action, you need to understand what is happening in your landscape. In this exercise you will orient yourself in the AI Agent Hub dashboard and inventory, then navigate to the Discovery Inbox to find the agent assigned to you for this workshop.

**Duration:** 15 minutes

## Background

AI Agent Hub in SAP LeanIX continuously discovers agents across your connected SAP and third-party environments. It surfaces two types of agents in the inbox:
- **Standard SAP agents** — discovered automatically from your connected SAP system (pre-loaded for this workshop)
- **Custom agents** — built and deployed by teams in your organization, appearing alongside standard agents once connected systems report them

Both types arrive in the same inbox and go through the same governance process. This is by design: governance applies regardless of who built the agent.

For this workshop, each participant has one agent pre-loaded in the Discovery Inbox. Your agent is named with your **participant number** from your session card — for example, *"GlobalFlex Procurement Assistant P07"*. You will govern this agent throughout the session.

## Step 1 — Review the Dashboard

1. In SAP LeanIX, open the **AI Agent Hub Dashboard**.
2. Take a moment to read the overview. You should see:
   - Total agents, MCP servers, and LLMs in the inventory
   - Agents by verification status (verified, unverified)
   - Agents by discovery source — SAP system, third-party (e.g., ServiceNow)
   - Recent governance activity

> **What you are seeing:** GlobalFlex AG has already connected its SAP system to AI Agent Hub. Standard agents have been discovered automatically. The inbox is waiting for your attention.

## Step 2 — Explore the Inventory

1. Navigate briefly to the **Inventory** view.
2. Use the filter to see agents grouped by type:
   - **SAP Standard Agents** — delivered by SAP, part of licensed solutions
   - **Custom Agents** — built by teams in your organization
   - **Third-Party Agents** — running in external environments (e.g., ServiceNow, Microsoft)
3. Return to the Dashboard when you are done.

## Step 3 — Find Your Agent in the Discovery Inbox

1. Navigate to the **AI Agent Discovery Inbox**:
   *Inventory → Inventory Tools (top right) → Discovery Inbox → AI Agent Discovery*
2. Apply the filter **Status: Action Needed** to focus on unreviewed agents.
3. Locate your agent by searching for your participant number — for example, *P07*.
4. Open the discovery item and review the detail panel:
   - **Description** — what the agent claims to do
   - **Discovered Fact Sheets** — fact sheets AI Agent Hub has automatically suggested as related
   - **Business Capability suggestion** — does the suggested mapping make sense for GlobalFlex AG?
5. Do not add to inventory yet — that is the first step of Exercise 2.

> **Discussion prompt:** Which agents in the inbox surprised you most — and why would they not already be on the EA team's radar at GlobalFlex AG?

## Summary

You have oriented yourself in the AI governance dashboard and located the agent you will govern throughout this workshop. In Exercise 2, you will review the full discovery details and add your agent to the inventory.

[Back: Getting Started](../ex0/README.md) | [Next: Exercise 2 — From Discovery to Inventory](../ex2/README.md)
