# Exercise 5 — Collect Missing Information via Survey

## Overview

Not every governance gap can be filled by the EA team alone. Fields like AI Agent Type, AI Risk, AI Model, and the business-side Owner require input from the team that built or runs the agent. Chasing this information over email is slow and leaves no audit trail. LeanIX surveys let you request exactly the fields you need from exactly the right person — and the answers flow directly into the fact sheet.

In this exercise you will create a survey targeting the open fields on your agent's fact sheet and send it to the agent's business owner. Your trainer plays the role of the business owner and will answer the survey during the session. Only once the survey response arrives will your fact sheet be complete enough to verify.

**Duration:** 15 minutes

## Step 1 — Identify the Fields to Survey

Open your agent's fact sheet and confirm the following fields are still empty (they should be, based on Exercise 4):

| Field | Why it needs the business owner |
|---|---|
| AI Agent Type | Only the team running the agent knows how it is invoked — conversational, automated, embedded, etc. |
| AI Risk | The EU AI Act risk category requires the owner to assess impact on their domain. |
| AI Model | Which underlying LLM or foundation model is used — often not visible to the EA team. |
| Business Owner | The person or team accountable for the agent on the business side. |

## Step 2 — Create the Survey

1. Open your agent's fact sheet.
2. In the fact sheet header, open the **More** menu.
3. Select **Create Survey** (or **Request Update**, depending on your workspace configuration).
4. A survey composer opens. You will see the available fields for this fact sheet type.

## Step 3 — Configure the Survey

1. **Select the fields** to include:
   - AI Agent Type
   - AI Risk
   - AI Model
   - Responsible subscriber / Business Owner

2. Add a **survey title**, for example:
   > *"AI Governance Data Request — [Your Agent Name]"*

3. Add a short **message to the respondent**, for example:
   > *"As part of GlobalFlex AG's AI governance process, we need your input on the agent you are responsible for. Please complete the fields below so we can complete the governance review."*

4. Set the **respondent** to the dummy user provided by your trainer — the email address is on your session card.

## Step 4 — Send the Survey

1. Review the survey preview.
2. Click **Send**.
3. The respondent receives an email with a direct link to fill in the fields. The answers write back into the fact sheet automatically when submitted.

> **What happens next:** Your trainer, acting as the agent's business owner, will fill in the survey response during the session and submit it. Watch your fact sheet — the fields will update in real time once the response comes in.

## Step 5 — Apply the Survey Response

When you see the fields update on your fact sheet (your trainer will signal when responses have been submitted):

1. Refresh the fact sheet if needed.
2. Review the values that arrived from the survey:
   - **AI Agent Type** — does the classification match what you expected based on the agent's description?
   - **AI Risk** — is the EU AI Act risk level appropriate for what this agent does?
   - **AI Model** — note the underlying model. Does it affect your governance decision?
3. If any value looks incorrect, discuss it with your group before proceeding to verification.

## Summary

The fact sheet now has all required fields populated — partly by you (description, ADR, owner subscription) and partly by the business owner via survey. This combination of self-service and structured data collection is how AI governance scales across an organization without becoming a bottleneck.

Move on to Exercise 6 when your trainer confirms that survey responses have been submitted for all groups.

[Back: Exercise 4](../ex4/README.md) | [Next: Exercise 6 — Verify the Agent](../ex6/README.md)
