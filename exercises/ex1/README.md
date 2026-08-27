# Exercise 1 — Discover the Shadow AI Landscape

## Overview

Before you can govern AI agents, you need to know they exist. In this exercise you will use SAP AI Agent Hub's discovery capabilities to surface agents running across SAP and third-party environments — including ones no one officially approved.

**Duration:** 15 minutes

## Background

Your organization has dozens of agents in operation. Some were procured through official channels. Others were built by individual teams. A few are running entirely under the radar — consuming data, calling APIs, and making decisions with no documented owner or risk assessment. These are your shadow AI agents.

AI Agent Hub aggregates agent metadata from connected source systems automatically, giving you a single inventory to work from.

## Step 1 — Open the Agent Inventory

1. In AI Agent Hub, navigate to the **Agent Inventory**.
2. You will see a list of agents with the following columns:
   - **Name** — agent identifier
   - **Source Environment** — where the agent is running (SAP BTP, S/4HANA, third-party, etc.)
   - **Type** — the agent category
   - **Owner** — responsible person or team (many will be empty)
   - **Risk Classification** — governance status
   - **Verification Status** — whether the agent has been reviewed and approved

## Step 2 — Explore Filters

1. Use the **Source Environment** filter to view only agents from third-party environments.
   - How many do you find? Note the number.
2. Clear the filter and apply **Verification Status = Unverified**.
   - These are all agents currently operating without governance sign-off.
3. Apply **Owner = None** on top of the previous filter.
   - This is your shadow AI shortlist — agents with no owner and no verification.

## Step 3 — Inspect an Agent

1. Click on any unverified, ownerless agent to open its detail view.
2. Review the available metadata:
   - What system is it connected to?
   - What data does it access?
   - When was it last active?
3. Note any fields that are empty or incomplete — these are governance gaps.

## Step 4 — Save a View (optional)

If the interface supports saved filters, save your "shadow AI shortlist" view (unverified + no owner) for use in later exercises.

## Summary

You now have a clear picture of the agent landscape — including the agents operating without oversight. In Exercise 2, you will assess a subset of these agents against your organization's governance criteria.

[Back: Getting Started](../ex0/README.md) | [Next: Exercise 2 — Assess Against Governance Criteria](../ex2/README.md)