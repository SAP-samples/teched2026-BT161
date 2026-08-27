# Exercise 3 — Assign Ownership & Classify Risk

## Overview

Assessment surfaces the gaps. Ownership closes them. In this exercise you will assign responsible owners to agents and apply risk classifications — the two actions that move an agent from "shadow AI" to "governed AI."

**Duration:** 15 minutes

## Background

An unowned agent is an unaccountable agent. Until someone is named responsible for an AI agent's behavior, data usage, and compliance, governance is aspirational rather than enforceable. Risk classification adds a second layer: it signals to the organization how much scrutiny this agent requires and helps prioritize remediation effort.

## Step 1 — Assign an Owner

1. From the Agent Inventory, open the detail view of an agent you assessed in Exercise 2.
2. Locate the **Owner** field.
3. Assign yourself as the owner (use your session credentials).
4. Save the change.

Repeat for at least one more agent.

> **Note:** In a real-world scenario, ownership would typically be assigned to a business owner or accountable team — not the governance lead. For this workshop, you are playing both roles.

## Step 2 — Set Risk Classification

1. On the same agent detail view, locate the **Risk Classification** field.
2. Choose the appropriate classification based on your assessment from Exercise 2:

| Classification | When to use |
|----------------|-------------|
| **Low** | Minimal data access, low business impact, fully auditable |
| **Medium** | Moderate sensitivity or criticality; requires periodic review |
| **High** | Accesses sensitive data or has significant business impact; requires active monitoring |
| **Critical** | Regulatory exposure, mission-critical operations, or uncontained access scope |

3. Save the classification.

## Step 3 — Document Data Sensitivity

1. If the agent detail view includes a **Data Sensitivity** or **Notes** field, add a short description of what data the agent accesses and why.
2. This creates an audit trail for future reviews.

## Step 4 — Repeat for Two More Agents

Apply ownership and risk classification to two additional agents. You should now have at least three agents with:
- An assigned owner
- A risk classification
- A saved assessment from Exercise 2

## Summary

Your agents are no longer ownerless. In Exercise 4, you will verify the agents that meet your governance criteria — formally approving them to run in your organization.

[Back: Exercise 2](../ex2/README.md) | [Next: Exercise 4 — Verify a Compliant Agent](../ex4/README.md)