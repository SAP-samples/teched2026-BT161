# Exercise 5 — Verify the Agent

## Overview

Verification is the governance decision point. When you verify an agent in SAP AI Agent Hub, you are formally approving it to run in your organization's production environment. Unverified agents are blocked from running in Joule Studio.

**Duration:** 10 minutes

## Step 1 — Confirm the Governance Checklist

Before verifying, confirm that the agent's fact sheet is complete. A verification-ready agent should have:

- [ ] Description — accurate and complete
- [ ] Owner — assigned
- [ ] Architecture decision — linked or documented
- [ ] Data access — documented
- [ ] EU AI Act classification — set
- [ ] Predecessor — linked (completed in Exercise 3)

If any item is missing, return to Exercise 4 to complete it before proceeding.

## Step 2 — Verify the Agent

1. On the agent's fact sheet, locate the **Verify** action or the **Verification Status** field.
2. Review the verification summary — AI Agent Hub surfaces a checklist or completeness indicator at this point.
3. Click **Verify** (or set status to **Verified**).
4. Add a short verification note, for example:

   > *"Verified following BT161 governance review. Owner confirmed, EU AI Act classification: Limited risk. Predecessor linked. Approved for production use."*

5. Save.

The agent's status is now **Verified**.

## Step 3 — Understand What Changes

When an agent is verified:

- It becomes eligible to appear and run in **Joule Studio** for end users
- It is counted as a compliant agent in your governance dashboard
- Future changes to the agent — expanded data access, new permissions — may trigger a re-verification requirement
- The verification record (who verified it, when, and the note) is retained for audit purposes

> **Think about it:** What would happen in your organization if an agent's permissions were expanded after verification? Who should be notified, and how quickly?

## Summary

The agent is verified and approved for production. In Exercise 6, you will switch to Joule Studio to confirm it runs — and observe that unverified agents are blocked.

[Back: Exercise 4](../ex4/README.md) | [Next: Exercise 6 — Test in Joule Studio](../ex6/README.md)