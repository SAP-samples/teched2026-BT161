# Exercise 2 — Assess Against Governance Criteria

## Overview

Discovery tells you what exists. Assessment tells you what to do about it. In this exercise you will apply a governance framework to a set of agents, scoring them against criteria that determine whether they are safe to run in your organization.

**Duration:** 20 minutes

## Background

Not all shadow AI agents are equally risky. A low-impact internal summarization agent is very different from an agent with access to HR data or financial systems. Your governance framework helps you make consistent, defensible decisions about which agents to approve, flag for remediation, or decommission.

SAP AI Agent Hub provides a structured assessment view where you can evaluate each agent against defined governance criteria.

## Step 1 — Open the Governance Assessment View

1. In AI Agent Hub, navigate to the **Governance** section.
2. Select **Assessments** (or equivalent view in your tenant).
3. You will see agents queued for assessment. The workshop pre-selects a representative set of 5 agents for you to work through.

## Step 2 — Review the Governance Criteria

Before assessing, familiarize yourself with the criteria used in this workshop:

| Criterion | What it evaluates |
|-----------|-------------------|
| **Data Sensitivity** | Does the agent access personal, confidential, or regulated data? |
| **Business Criticality** | Would failure or misuse of this agent impact business operations? |
| **Compliance Alignment** | Does the agent's behavior align with applicable policies (GDPR, AI Act, internal policies)? |
| **Auditability** | Are the agent's decisions and actions logged and traceable? |
| **Authorization Scope** | Does the agent operate within its intended permission boundaries? |

## Step 3 — Assess Agent A (Guided)

1. Open the first agent in the assessment queue (your trainer will identify which one).
2. For each governance criterion, select a rating:
   - **Meets criteria** — no issues identified
   - **Needs remediation** — gaps exist but agent can continue with conditions
   - **Non-compliant** — agent should not run until issues are resolved
3. Add a comment explaining your rating for at least two criteria.
4. Save the assessment.

## Step 4 — Assess Agents B and C (Independent)

Repeat the assessment process for two more agents from the queue. Use your judgment based on the metadata available.

> **Tip:** For agents with missing metadata (no data access description, no owner), default to **Needs remediation** — you cannot assess what you cannot see.

## Summary

You have now assessed three agents against your governance framework. In Exercise 3, you will assign ownership and risk classification to follow up on your findings.

[Back: Exercise 1](../ex1/README.md) | [Next: Exercise 3 — Assign Ownership & Classify Risk](../ex3/README.md)