# Exercise 4 — Verify a Compliant Agent

## Overview

Verification is the governance decision point. A verified agent is one your organization has formally reviewed and approved to operate. In this exercise you will mark a fully assessed and owned agent as verified, and understand what that status means at runtime.

**Duration:** 10 minutes

## Background

In SAP AI Agent Hub, **verification** is not just a label — it is an enforcement signal. Verified agents can be surfaced to users in Joule Studio. Unverified agents are blocked or hidden. This connects governance decisions made in AI Agent Hub directly to the user experience in Joule Studio.

## Step 1 — Identify a Verification-Ready Agent

An agent is ready for verification when it has:
- A completed governance assessment (all criteria rated)
- An assigned owner
- A risk classification

From your Agent Inventory, identify one agent that meets all three criteria (based on your work in Exercises 2 and 3).

## Step 2 — Verify the Agent

1. Open the agent's detail view.
2. Locate the **Verification Status** field or the **Verify** action.
3. Review the verification checklist — confirm that assessment, ownership, and risk classification are complete.
4. Click **Verify** (or set status to **Verified**).
5. Add a short verification note (e.g., "Assessed BT161 workshop — low risk, owner assigned, compliant with data handling policy").
6. Save.

The agent's status should now show as **Verified**.

## Step 3 — Understand What Verification Gates

Take a moment to review what changes after an agent is verified:

- The agent becomes eligible to appear in **Joule Studio** for end users
- It is included in governance reporting as a compliant agent
- Future changes to the agent (new data access, new permissions) may trigger a re-verification requirement

> **Think about it:** What would happen in your organization if an agent's permissions were expanded after verification? Who should be notified?

## Summary

You have made your first formal governance decision. In Exercise 5, you will switch to Joule Studio and see how this decision affects the user-facing experience.

[Back: Exercise 3](../ex3/README.md) | [Next: Exercise 5 — Experience Enforcement in Joule Studio](../ex5/README.md)