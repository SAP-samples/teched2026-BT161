# Exercise 1 — The AI Agent Hub Dashboard

## Overview

Before reviewing any individual agent, your AI Governance Center of Excellence has just come out of a committee meeting with a policy decision that needs to be documented. In this exercise you will create an Architecture Decision Record (ADR) to formalize that policy, then orient yourself in the dashboard and inventory to understand the current state of AI at GlobalFlex AG.

**Duration:** 20 minutes

## Background

GlobalFlex AG's AI governance committee has concluded that **all finance agents interacting with S/4HANA data must run on the SAP Joule Studio runtime** and must undergo formal governance review before going live. Your job is to document this as an official Architecture Decision Record so that every agent review from this point forward can be checked against it.

You will use the **EA Assistant** — the AI-powered assistant in SAP LeanIX — to draft the ADR from a plain-language description.

## Step 1 — Create an Architecture Decision

1. Navigate to **More** (top header) → **EA Assistant**.
2. Use the following prompt to generate the ADR. Replace `[PXX]` with your participant number (e.g., P07):

   > *"Create an architecture decision titled 'Finance Agents on S/4HANA Must Use Joule Studio Runtime — [PXX]' documenting the following policy: All AI agents that interact with S/4HANA financial data at GlobalFlex AG must be deployed on the SAP Joule Studio runtime. This decision applies to standard and custom-built agents. Agents that do not comply must be migrated or decommissioned. The rationale is auditability, data residency compliance, and alignment with the SAP AI governance framework."*

3. Review the generated ADR — it will include a **Context**, **Decision**, and **Consequences** section.

> **The ADR is saved automatically and its status is set to Accepted.**

> **Why your participant number matters:** Because everyone in this session shares one workspace, including your participant number in the ADR title makes it easy to find your own ADR later when you link it to your agent in Exercise 3.

> **Why this comes first:** Architecture decisions document policy at the organization level — before you look at any individual agent. In Exercise 3, you will link your agent to this ADR to show it is subject to this policy.

## Step 2 — Review the Dashboard

1. In SAP LeanIX, navigate to the **AI Agent Hub Dashboard**.
2. Take a moment to read the overview. You should see:
   - Total agents, MCP servers, and LLMs in the inventory
   - The AI pipeline: how many agents are in **Discovery**, **Inventory**, and **Verified** status
   - Agents by verification status (verified, unverified)
   - **Connected systems** — Joule Studio, SAP Cloud ALM, Signavio, and others feeding discovery data into AI Agent Hub

> **What you are seeing:** GlobalFlex AG has already connected its SAP system to AI Agent Hub. The dashboard gives you a real-time governance posture: how many agents exist, how many are verified, and how much AI activity is happening in your landscape right now.

## Step 3 — Drill Into a Pre-Verified Agent

The dashboard shows agents already in the inventory. Before reviewing your own agent, take a moment to see what a fully governed agent looks like.

1. Navigate to the **Inventory** view.
2. Filter by: **Application** type + **AI Agent** subtype.
3. Open the pre-loaded standard SAP agent that has already been verified for this workshop — your trainer will tell you which one to open.
4. Explore the fact sheet:
   - **Relations Explorer** — visualize which IT components, business capabilities, and other fact sheets this agent is connected to
   - **Analytics** tab — view usage data: sessions, first/last active, average tokens per session
   - **Subscriptions** — see who is assigned as Responsible and Observer
   - **Change Log** — see the history of every governance action taken on this fact sheet

> **This is your audit trail.** Every field change, subscription update, and verification decision is recorded here. This is what a complete governance record looks like when you have finished today's exercises.

## Step 4 — Link the ADR to the Standard Agent

You have now created an ADR and reviewed a standard SAP agent. Link them together: the EA Assistant session you opened in Step 1 is still active.

1. Navigate back to **More** (top header) → **EA Assistant**.
2. In the same session, use the following prompt (replace the agent name with the one your trainer specified):

   > *"Please link this architecture decision to the [agent name] fact sheet."*

3. The EA Assistant will link the standard agent to your ADR. Confirm the agent now appears in the **Affected Fact Sheets** section of the ADR.

> **Why this matters:** Linking an existing standard agent to the ADR demonstrates the policy applies retroactively — not just to new custom agents, but to the entire governed landscape.

## Summary

You have documented a governance policy as an ADR, seen what a fully governed agent looks like, and linked the standard agent to the policy. In Exercise 2, you will find the custom agent assigned to you in the Discovery Inbox and begin the review process.

[Back: Getting Started](../ex0/README.md) | [Next: Exercise 2 — From Discovery to Inventory](../ex2/README.md)
