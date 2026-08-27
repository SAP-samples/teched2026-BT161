# Exercise 6 — Decommission a Non-Compliant Agent

## Overview

Not every governance story ends with approval. Some agents need to be taken out of service — either because they are non-compliant, redundant, or replaced by a better-governed alternative. In this exercise you will formally decommission an agent and manage its succession.

**Duration:** 5 minutes

## Background

Decommissioning in AI Agent Hub is a structured process, not just deletion. You remove the agent's verification status, mark it as phased out, and — where applicable — point to a successor agent. This creates a clean audit trail and ensures users are redirected to the approved alternative rather than simply losing access without explanation.

## Step 1 — Identify the Agent to Decommission

From the Agent Inventory, select the agent your trainer has pre-identified for decommissioning in this exercise. It should be an agent that:
- Failed its governance assessment (Non-compliant rating in Exercise 2)
- Has no clear path to remediation within the governance window

## Step 2 — Remove Verification

1. Open the agent's detail view.
2. If the agent is currently verified, locate the verification status and remove it (set to **Unverified** or **Revoked**).
3. Add a note explaining why verification is being removed (e.g., "Non-compliant — unresolvable data access scope issue").

## Step 3 — Mark as Phased Out

1. Locate the **Lifecycle Status** or equivalent field.
2. Set the status to **Phased Out** (or equivalent in your tenant).
3. Set a **Phase-Out Date** — use today's date for this workshop.

## Step 4 — Assign a Predecessor (Successor Reference)

1. If a replacement agent exists in the inventory, locate the **Predecessor** or **Successor** field on the agent detail view.
2. Link the decommissioned agent to its replacement — this tells users and other systems where to go instead.
3. Save all changes.

## Step 5 — Confirm Enforcement

1. Switch to Joule Studio.
2. Search for the decommissioned agent.
3. Confirm it is no longer available or is marked as unavailable.

## Summary

The agent is formally decommissioned: unverified, phased out, and with a successor defined. The governance record is complete.

If you have time remaining, continue to the optional Exercise 7 to explore governance reporting.

[Back: Exercise 5](../ex5/README.md) | [Optional: Exercise 7 — Governance Posture & Reporting](../ex7/README.md)