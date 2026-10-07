# Exercise 6 — Decommission a Legacy Agent

## Overview

Governance is not only about approving new agents — it also means formally closing out agents that are no longer needed. In this exercise you will decommission a legacy finance agent that has been replaced by the one you just verified, documenting the lineage and removing its production approval.

**Duration:** 10 minutes

## Background

The custom agent you governed in Exercises 2–5 was introduced to replace an older agent that had been running in GlobalFlex AG's landscape. That legacy agent is already in **Phase Out** lifecycle — but the governance record has not been closed out. Without formal decommissioning, it could still be discovered, reactivated, or mistaken for an active agent.

Your job is to complete the record: link the successor relationship, update the lifecycle to End of Life, and remove the verification.

## Step 1 — Find the Legacy Agent

Use the Enterprise Architecture Assistant to locate the legacy agent assigned to you.

1. Navigate to **More** (top header) → **EA Assistant**.
2. Use the following prompt. Replace `[PXX]` with your participant number:

   > *"Find agents with [PXX] in the name that have a Phase Out lifecycle."*

3. Open the fact sheet returned by the assistant.

## Step 2 — Set the Successor

Document that your newly verified agent replaces this one.

1. On the legacy agent's fact sheet, navigate to the **Relations** section.
2. Find the **Successor** relation and add your verified custom agent (search for your participant number).

> **Why this matters:** Setting the successor creates a formal lineage record. Anyone looking at this legacy agent in the future will see exactly what replaced it — and when. The successor agent's fact sheet will show the legacy agent as its **Predecessor**.

## Step 3 — Update the Lifecycle to End of Life

1. In the fact sheet header, open the **Lifecycle** field.
2. Set the current phase to **End of Life**.

> This signals that the agent is no longer in use. The change is recorded in the Change Log with a timestamp.

## Step 4 — Remove the Verification

An End of Life agent should not carry a production-approved verification badge.

1. Locate the **Verification Badge** at the top of the fact sheet header.
2. Click the badge and select **Unverify**.

The badge reverts — the agent is no longer marked as approved for production use.

## Summary

You have completed the full governance lifecycle — from discovering a new agent all the way to formally decommissioning a legacy one. The decommissioning record is preserved in the Change Log and the successor link connects the two agents as a documented lineage. The legacy agent remains in the inventory as a historical record; it is not deleted.

> This is what the session title means by "From Discovery to Decommissioning" — governance is a continuous cycle, not a one-time event.

[Back: Exercise 5](../ex5/README.md) | [Return to Overview](../../README.md)
