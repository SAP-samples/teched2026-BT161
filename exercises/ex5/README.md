# Exercise 5 — Verify the Agent

## Overview

Verification is the governance decision point. When you mark an agent as verified in SAP LeanIX, you are formally approving it to run in your organization's production environment. Unverified agents cannot run in Joule Work.

**Duration:** 10 minutes

## Step 1 — Confirm the Governance Checklist

Before verifying, confirm that the agent's fact sheet is complete:

- [ ] Description — accurate and complete
- [ ] Owner — assigned as Responsible subscriber
- [ ] Architecture Decision — linked (created in Exercise 4)
- [ ] AI Governance and Adoption section — AI Agent Type, AI Agent Nature, and AI Risk all set
- [ ] Predecessor — linked (completed in Exercise 3)

If any item is missing, return to the relevant exercise to complete it.

## Step 2 — Mark as Verified

1. On the agent's fact sheet, locate the **Verification Badge** at the top of the fact sheet header.
2. Click the **Verification Badge**.
3. In the popup, select **Mark as Verified**.
4. Add a short verification note, for example:

   > *"Verified following BT161 governance review. Owner confirmed. AI Risk: Limited. ADR created. Predecessor linked. Approved for production use."*

5. Confirm.

The badge updates to **Agent Verified** and the **Approval State** is updated accordingly.

## Step 3 — Understand What Changes

When an agent is verified:

- It becomes eligible to appear and run in **Joule Work** for end users
- It is counted as a compliant agent in your governance dashboard
- Future changes to the agent — expanded data access, new permissions — may trigger a re-verification requirement
- The verification record (who verified it, when, and the note) is retained for audit purposes

> **Think about it:** What would happen in your organization if an agent's permissions were expanded after verification? Who should be notified, and how quickly?

## Summary

The agent is verified and approved for production. In Exercise 6, you will switch to Joule Work to confirm it runs — and see that the governance decision you just made is enforced automatically.

[Back: Exercise 4](../ex4/README.md) | [Next: Exercise 6 — Test in Joule Work](../ex6/README.md)
