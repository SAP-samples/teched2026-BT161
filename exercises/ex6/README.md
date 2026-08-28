# Exercise 6 — Test in Joule Studio

## Overview

Governance decisions made in AI Agent Hub are enforced at runtime in Joule Studio. In this final exercise you will switch to your individual Joule Studio instance, confirm that your verified agent is available and runs, and observe that an unverified agent is blocked.

**Duration:** 10 minutes

## Background

SAP AI Agent Hub and Joule Studio are connected. Verification in AI Agent Hub is not just a label — it is an enforcement signal. Only agents that have been formally reviewed and approved by the governance team are allowed to run in Joule Studio. This is what "AI governance at runtime" means: policy decisions made by governance teams are enforced automatically in the tools that employees use every day.

## Step 1 — Switch to Joule Studio

1. Switch to the browser tab with your individual **Joule Studio** instance.
2. Log in if your session has expired.

## Step 2 — Find and Run the Verified Agent

1. In Joule Studio, navigate to the agent or assistant discovery view.
2. Search for the agent you verified in Exercise 5 by name.
3. Confirm it appears and is available.
4. Invoke the agent with a simple test prompt provided by your trainer.
5. Confirm you receive a response — the agent is running in production.

## Step 3 — Attempt to Use an Unverified Agent

1. Return to AI Agent Hub and note the name of one of the other newly discovered agents — one that you did **not** verify in this workshop.
2. Switch back to Joule Studio and search for that agent by name.
3. Observe the result: the agent should be absent, hidden, or shown with a blocked/restricted status.

> **What you are seeing:** Joule Studio enforces the governance state set in AI Agent Hub. End users cannot access agents that have not been reviewed and approved. The governance decision you made as Head of AI Governance is enforced automatically — without any manual intervention in Joule Studio itself.

## Step 4 — Reflect

Consider the following before the session wrap-up:

- How does this change the role of the AI governance team in your organization?
- What process would you put in place to keep up with the pace of new agent discovery?
- Who in your organization should receive a weekly governance posture report?

## Summary

You have completed the full governance lifecycle for a newly discovered AI agent — from discovery to verification and runtime enforcement. You experienced SAP AI Agent Hub as the command center for AI governance: one place to view, assess, and control every agent, MCP server, and LLM in your landscape.

[Back: Exercise 5](../ex5/README.md) | [Return to Overview](../../README.md)