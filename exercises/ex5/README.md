# Exercise 5 — Verify the Agent

## Overview

Verification is the governance decision point. When you mark an agent as verified in SAP LeanIX, you are formally approving it for production use in your organization.

**Duration:** 15 minutes

> **Before you start:** Confirm with your trainer that the survey responses from Exercise 4 have been submitted. Your fact sheet must show values for AI Risk, AI Model, Business Criticality, Functional Fit, AI Agent Business Value, and Technical Fit before you proceed.

## Step 1 — Confirm the Governance Checklist

Open your agent's fact sheet and verify that every item below is complete:

- [ ] **Description** — confirmed in Exercise 3
- [ ] **Responsible** — auto-assigned from deployment (Exercise 2); you are Observer (Exercise 3)
- [ ] **Architecture Decision** — linked in Exercise 1 and Exercise 3
- [ ] **AI Risk** — received via survey (Exercise 4)
- [ ] **AI Model** — received via survey (Exercise 4)
- [ ] **Business Criticality** — received via survey (Exercise 4)
- [ ] **Functional Fit** — received via survey (Exercise 4)
- [ ] **AI Agent Business Value** — received via survey (Exercise 4)
- [ ] **Technical Fit** — received via survey (Exercise 4)

If any item is still missing, address it before clicking Verify.

## Step 2 — Mark as Verified

1. On the agent's fact sheet, locate the **Verification Badge** at the top of the fact sheet header.
2. Click the **Verification Badge**.
3. In the popup, select **Mark as Verified**.
4. Confirm.

The badge updates to **Agent Verified**.

## Step 3 — Set the Approval State

The **Verification Badge** and the **Approval State** are two separate governance signals — understanding the difference matters:

- **Verification Badge** (*Mark as Verified / Agent Verified*) — specific to AI agents, MCP servers, and LLMs. It means this agent has been reviewed and is approved to run productively. This is the AI governance signal.
- **Approval State** (*Quality Seal*) — applies to all fact sheets in SAP LeanIX, not just agents. It signals that the data on this fact sheet has been reviewed and meets your organization's data quality standard.

Both are meaningful — and both should be set.

1. Locate the **Approval State** field on the fact sheet header (also called the Quality Seal).
2. Set it to **Approved**.

## Summary

You have completed the full AI governance lifecycle for a newly discovered agent: discovery, inventory, governance profile, data collection from the business owner, and formal verification.

Your agent is now verified. This means that from a governance perspective, you have confirmed this agent is approved to be used within your organization — and end users can interact with it for the tasks it was designed for. The full governance record — who reviewed it, what policies apply, what the business owner confirmed — is captured in SAP LeanIX as an auditable history.

> **Note on the AI Governance checklist:** Workspace administrators can configure a custom governance checklist in **Administration → AI Governance**. In this shared workshop workspace you can view it but not modify it. In your own organization, you would use this to define exactly which fields must be completed before an agent can be verified.

[Back: Exercise 4](../ex4/README.md) | [Return to Overview](../../README.md)
