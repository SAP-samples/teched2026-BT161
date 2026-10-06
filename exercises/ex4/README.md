# Exercise 4 — Collect Missing Information via Survey

## Overview

Not every governance gap can be filled by the EA team alone. Fields like AI Risk, AI Model, and the business-side context require input from the team that built or runs the agent. Chasing this information over email is slow and leaves no audit trail. LeanIX surveys let you request exactly the fields you need from exactly the right person — and the answers flow directly into the fact sheet.

In this exercise you will use the **Next Generation Survey** feature to create a targeted survey with AI, send it to the agent's business owner, and then watch the fact sheet update — and the change log record — as the responses arrive.

**Duration:** 15 minutes

## Step 1 — Identify the Fields to Survey

Open your agent's fact sheet and confirm the following fields are still empty (they should be, based on Exercise 3):

| Field | Why it needs the business owner |
|---|---|
| **AI Risk** | The EU AI Act risk category requires the owner to assess impact on their domain. |
| **AI Model** | Which underlying LLM or foundation model is used — often not visible to the EA team. |
| **Business Criticality** | How critical this agent is to business operations — only the business side can assess this. |
| **Functional Fit** | How well the agent meets the business need it was built for. |
| **AI Agent Business Value** | The business value this agent delivers — requires the owner's perspective. |
| **Technical Fit** | How well the agent fits the technical landscape — input from the deploying team. |

## Step 2 — Create a Survey Using AI

LeanIX's **Next Generation Survey** feature lets you generate a targeted survey from a plain-language description.

1. In the top navigation, go to **More → Surveys**.
2. Click **New Survey**.
3. Use the following prompt. Replace `[PXX]` with your participant number (e.g., P07):

   > *"Create a survey for an AI agent governance review for the custom agent [PXX]. The respondent is the agent's business owner. The survey should collect: AI Risk classification per the EU AI Act, the AI Model or foundation model used, Business Criticality, Functional Fit, AI Agent Business Value, and Technical Fit."*

   After submitting the prompt, the EA Assistant opens again and generates the survey. You can see the first draft of the survey on the left side of the display.

4. Review the generated survey. Adjust the question wording if needed to fit the GlobalFlex AG context, then click **Next**.
5. Under **Distribution mode**, select **One-off Survey**.
6. Verify that the **Survey scope** shows only your agent (PXX). If it includes other fact sheets, click **Edit** or use **Change with AI** to correct it so the survey is scoped to your agent only.
7. One respondent should be automatically selected based on the agent's responsible subscriber. Confirm the pre-selected user is correct.
8. Open the **Invitation Email** section and add a short message to the respondent, for example:

   > *"As part of GlobalFlex AG's AI governance process, we need your input on the agent you are responsible for. Please complete the fields below so we can complete the governance review."*

9. Click **Next** to configure how responses are saved to fact sheets. Two options are available:
   - **Save Directly** — responses are written to the fact sheet automatically on submission.
   - **Review Before Saving** — responses are held for review before any fact sheet values are updated.

   For this training, select **Save Directly**.

10. Click **Send Survey**. The respondent receives an email with a direct link to fill in the fields. Answers write back into the fact sheet automatically on submission.

11. You can review the status of your survey in the survey overview. Filter by **Created By** to show only surveys created by your user. Once the results are in, click **Results** to review the responses.

> **What happens next:** Your trainer, acting as the agent's business owner, will fill in the survey response during the session and submit it. Watch your fact sheet — the fields will update once the response comes in.

## Step 3 — Apply the Survey Response

When your trainer signals that responses have been submitted:

1. Refresh the fact sheet if needed.
2. Review the values that arrived from the survey:
   - **AI Risk** — is the EU AI Act risk level appropriate for what this agent does?
   - **AI Model** — note the underlying model. Does it affect your governance decision?
   - **Business Criticality** — does the business side's assessment match your expectation?
   - **Functional Fit** and **Technical Fit** — do these align with what you observed during discovery?
3. If any value looks incorrect, discuss it with your workshop partner before proceeding. If you have questions, raise your hand and ask your trainer.

## Step 4 — Review the Change Log

1. Navigate to the **Change Log** tab on your agent's fact sheet.
2. Confirm that the survey-driven field updates appear as individual entries in the log.

> **Why this matters:** The change log gives you an auditable trail — not just *what* the fields contain now, but *when* the information arrived, *who* provided it, and *how* it was collected (survey response vs. direct edit). This is what AI governance accountability looks like in practice.

## Summary

The fact sheet now has all required fields populated — partly by you (description, ADR link, observer subscription) and partly by the business owner via survey. This combination of structured self-service and targeted data collection is how AI governance scales without becoming a bottleneck.

Move on to Exercise 5 when your trainer confirms that survey responses have been submitted for all groups.

[Back: Exercise 3](../ex3/README.md) | [Next: Exercise 5 — Verify the Agent](../ex5/README.md)
