# Exercise 5 — Experience Enforcement in Joule Studio

## Overview

Governance decisions made in AI Agent Hub have real consequences for users. In this exercise you will switch to your individual Joule Studio instance and observe how verified and unverified agents behave differently at runtime.

**Duration:** 10 minutes

## Background

SAP AI Agent Hub and Joule Studio are connected. When you verify an agent in AI Agent Hub, that decision propagates to Joule Studio — the agent becomes available to users. When an agent is unverified or decommissioned, it is blocked from appearing in Joule Studio sessions.

This is what "governance at runtime" means: policy decisions made by governance teams are enforced automatically in the tools employees use every day.

## Step 1 — Open Joule Studio

1. Switch to the browser tab with your individual **Joule Studio** instance.
2. Log in if your session has expired.

## Step 2 — Find Your Verified Agent

1. In Joule Studio, navigate to the agent or tool discovery view.
2. Search for the agent you verified in Exercise 4 by name.
3. Confirm it appears and is available for use.

## Step 3 — Attempt to Use an Unverified Agent

1. Return to AI Agent Hub and note the name of an agent that is still **unverified**.
2. Switch back to Joule Studio and search for that agent by name.
3. Observe the result — the agent should be absent, hidden, or shown with a restricted/blocked status.

> **What you are seeing:** Joule Studio respects the governance state set in AI Agent Hub. End users cannot access agents that have not been reviewed and approved by the governance team.

## Step 4 — Reflect

Consider the following questions (discuss with your neighbor or note them for the wrap-up):

- How does this change the role of the AI governance team in your organization?
- What would a good governance process look like to keep up with the pace of new agent deployment?
- Who should be notified when a new agent is blocked?

## Summary

You have seen governance enforcement in action. In Exercise 6, you will take the opposite action — decommissioning an agent that should no longer be running.

[Back: Exercise 4](../ex4/README.md) | [Next: Exercise 6 — Decommission a Non-Compliant Agent](../ex6/README.md)
