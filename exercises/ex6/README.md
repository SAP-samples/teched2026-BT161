# Exercise 6 — Test in Joule Work

## Overview

Governance decisions made in SAP LeanIX are enforced at runtime in Joule Work. In this final exercise you will switch to Joule Work, confirm that your verified agent is available and runs, and observe that an unverified agent is blocked.

**Duration:** 5 minutes

## Background

SAP LeanIX and Joule Work are connected. Verification is not just a label — it is an enforcement signal. Only agents that have been formally reviewed and approved in AI Agent Hub are allowed to run in Joule Work. This is what "AI governance at runtime" means: policy decisions made by the EA team are enforced automatically in the tool employees use every day.

## Step 1 — Switch to Joule Work

1. Switch to the **Joule Work** browser tab.
2. Log in again if your session has expired.

## Step 2 — Find and Run Your Verified Agent

1. In Joule Work, navigate to the agent or assistant discovery view.
2. Search for the agent you verified in Exercise 5 — use your 3-digit participant code to find it quickly.
3. Confirm it appears and is available.
4. Invoke the agent with the test prompt provided by your trainer.
5. Confirm you receive a response — your agent is running in production.

## Step 3 — Attempt to Use an Unverified Agent

1. Return to SAP LeanIX and note the name of one of the other agents in the inbox — one that was **not** verified in this workshop.
2. Switch back to Joule Work and search for that agent by name.
3. Observe the result: the agent should be absent, hidden, or shown with a blocked/restricted status.

> **What you are seeing:** Joule Work enforces the governance state set in SAP LeanIX. End users cannot access agents that have not been reviewed and approved. The decision you made as an EA team member at GlobalFlex AG is enforced automatically — without any manual intervention in Joule Work itself.

## Step 4 — Reflect

Consider the following before the session wrap-up:

- How does this change the role of the EA or AI governance team in your organization?
- What process would you put in place to keep up with the pace of new agent discovery?
- Who in your organization should receive a weekly AI governance posture report?

## Summary

You have completed the full governance lifecycle for a newly discovered AI agent — from deploying it in Joule Work, through discovery, assessment, and verification in SAP LeanIX, to confirming it runs in production. This is what end-to-end AI governance looks like in practice.

[Back: Exercise 5](../ex5/README.md) | [Return to Overview](../../README.md)
