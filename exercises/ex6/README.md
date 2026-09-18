# Exercise 6 — Verify the Agent

## Overview

Verification is the governance decision point. When you mark an agent as verified in SAP LeanIX, you are formally approving it for production use in your organization.

**Duration:** 10 minutes

> **Before you start:** Confirm with your trainer that the survey responses from Exercise 5 have been submitted. Your fact sheet must show values for AI Agent Type, AI Risk, and AI Model before you proceed.

## Step 1 — Confirm the Governance Checklist

Open your agent's fact sheet and verify that every item below is complete:

- [ ] **Description** — generated and reviewed in Exercise 4
- [ ] **Owner** — you are assigned as Responsible subscriber (Exercise 4)
- [ ] **Architecture Decision** — linked to the ADR created in Exercise 4
- [ ] **Predecessor** — linked to the phased-out agent (Exercise 3)
- [ ] **AI Agent Type** — received via survey (Exercise 5)
- [ ] **AI Risk** — received via survey (Exercise 5)
- [ ] **AI Model** — received via survey (Exercise 5)

If any item is still missing, address it before clicking Verify.

## Step 2 — Mark as Verified

1. On the agent's fact sheet, locate the **Verification Badge** at the top of the fact sheet header.
2. Click the **Verification Badge**.
3. In the popup, select **Mark as Verified**.
4. Add a short verification note, for example:

   > *"Verified following BT161 governance review. Owner confirmed. AI Risk assessed. ADR created. Survey response received from business owner. Approved."*

5. Confirm.

The badge updates to **Agent Verified** and the **Approval State** is updated accordingly.

## Step 3 — Understand What Changes

When an agent is verified:

- It is counted as a compliant agent in your governance dashboard
- Future changes to the agent — expanded data access, new permissions — may trigger a re-verification requirement
- The verification record (who verified it, when, and the note) is retained for audit purposes

> **Think about it:** The survey you sent in Exercise 5 created an auditable trail — you can show when data was requested and when it was provided. How would you use that trail if an agent was later found to be non-compliant?

## Summary

You have completed the full AI governance lifecycle for a newly discovered agent: discovery, inventory, duplicate check, fact sheet preparation, data collection from the business owner, and formal verification. This is what structured AI governance looks like in practice at GlobalFlex AG.

[Back: Exercise 5](../ex5/README.md) | [Return to Overview](../../README.md)
