# Exercise 4 — Collect Missing Information via Survey

## Overview

Not every governance gap can be filled by the EA team alone. Fields like AI Agent Type, AI Risk, AI Model, and the business-side Owner require input from the team that built or runs the agent. Chasing this information over email is slow and leaves no audit trail. LeanIX surveys let you request exactly the fields you need from exactly the right person — and the answers flow directly into the fact sheet.

In this exercise you will use the **Next Generation Survey** feature to create a targeted survey with AI, send it to the agent's business owner, and then watch the fact sheet update — and the change log record — as the responses arrive.

**Duration:** 15 minutes

## Step 1 — Identify the Fields to Survey

Open your agent's fact sheet and confirm the following fields are still empty (they should be, based on Exercise 3):

| Field | Why it needs the business owner |
|---|---|
| AI Agent Type | Only the team running the agent knows how it is invoked — conversational, automated, embedded, etc. |
| AI Risk | The EU AI Act risk category requires the owner to assess impact on their domain. |
| AI Model | Which underlying LLM or foundation model is used — often not visible to the EA team. |
| Business Owner | The person or team accountable for the agent on the business side. |

## Step 2 — Create a Survey Using AI

LeanIX's **Next Generation Survey** feature lets you generate a targeted survey from a plain-language description.

1. In the top navigation, go to **More → Surveys**.
2. Click **Create with AI**.
3. Use the following prompt:

   > *"Create a survey for an AI agent governance review. The respondent is the agent's business owner. The survey should collect the following fields: AI Agent Type (how the agent interacts with users), AI Risk classification per the EU AI Act, the AI Model or foundation model used, and the name and email of the accountable business owner."*

4. Review the generated survey. Adjust the question wording if needed to fit the GlobalFlex AG context.
5. Set the **fact sheet** the survey is linked to: your agent's fact sheet.
6. Set the **respondent** to the dummy user provided by your trainer — the email address is on your session card.
7. Add a short message to the respondent, for example:

   > *"As part of GlobalFlex AG's AI governance process, we need your input on the agent you are responsible for. Please complete the fields below so we can complete the governance review."*

## Step 3 — Send the Survey

1. Review the survey preview.
2. Click **Send**.
3. The respondent receives an email with a direct link to fill in the fields. The answers write back into the fact sheet automatically when submitted.

> **What happens next:** Your trainer, acting as the agent's business owner, will fill in the survey response during the session and submit it. Watch your fact sheet — the fields will update once the response comes in.

## Step 4 — Apply the Survey Response

When your trainer signals that responses have been submitted:

1. Refresh the fact sheet if needed.
2. Review the values that arrived from the survey:
   - **AI Agent Type** — does the classification match what you expected based on the agent's description?
   - **AI Risk** — is the EU AI Act risk level appropriate for what this agent does?
   - **AI Model** — note the underlying model. Does it affect your governance decision?
3. If any value looks incorrect, discuss it with your group before proceeding.

## Step 5 — Review the Change Log

1. Navigate to the **Change Log** tab on your agent's fact sheet.
2. Confirm that the survey-driven field updates appear as individual entries in the log.

> **Why this matters:** The change log gives you an auditable trail — not just *what* the fields contain now, but *when* the information arrived, *who* provided it, and *how* it was collected (survey response vs. direct edit). This is what AI governance accountability looks like in practice.

## Summary

The fact sheet now has all required fields populated — partly by you (description, ADR link, observer subscription) and partly by the business owner via survey. This combination of structured self-service and targeted data collection is how AI governance scales without becoming a bottleneck.

Move on to Exercise 5 when your trainer confirms that survey responses have been submitted for all groups.

[Back: Exercise 3](../ex3/README.md) | [Next: Exercise 5 — Verify the Agent](../ex5/README.md)
