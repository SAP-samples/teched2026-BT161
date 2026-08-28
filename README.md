# From Discovery to Decommissioning: A Hands-On AI Governance Workshop

## Session Overview

Shadow AI is already in your organization. This workshop shows you what to do about it.

Working inside the **SAP AI Agent Hub** solution, you will discover agents across SAP and third-party software environments, assess them against governance criteria, assign ownership and risk classification, and verify them to help enforce your organization's AI governance decisions at runtime.

## Business Scenario

> You are the **Head of AI Governance** at a mid-size enterprise running SAP. You start your week by checking the SAP AI Agent Hub dashboard — your command center for everything AI in the organization.
>
> Three new agents have been discovered in the landscape. One of them is unknown to you. You need to understand what it does, whether it duplicates something that already exists, who owns it, whether it meets your governance and regulatory requirements, and ultimately decide whether to approve it to run in production.

## What You Will Learn

SAP AI Agent Hub gives you a single place to view and govern all AI agents, MCP servers, and LLMs deployed across your landscape — SAP-native, custom-built, and third-party. In this workshop you will experience the full governance lifecycle for a newly discovered agent:

- Use the **dashboard and inbox** to spot and triage new discoveries
- Use the **AI Governance Assistant** to find similar agents already in your landscape
- Manage **agent succession** by linking a phased-out agent as a predecessor
- Complete a full **governance profile**: ownership, architecture alignment, and EU AI Act classification
- **Verify** the agent so it is approved to run in production
- **Test the agent in Joule Studio** — only verified agents are allowed to run

## Session Structure

| # | Exercise | Description | Duration |
|---|----------|-------------|----------|
| GS | [Getting Started](exercises/ex0/README.md) | Log in to AI Agent Hub and Joule Studio; orient in the environment | 10 min |
| 1 | [The Governance Dashboard](exercises/ex1/README.md) | Explore AAH as your AI command center; find the 3 newly discovered agents | 10 min |
| 2 | [From Discovery to Inventory](exercises/ex2/README.md) | Open the inbox, review the discovery item and analytics, add the agent to your inventory | 15 min |
| 3 | [Find Similar Agents & Set a Predecessor](exercises/ex3/README.md) | Use the AI Governance Assistant to find existing agents with similar capabilities; link the phased-out agent as a predecessor | 15 min |
| 4 | [Complete the Governance Profile](exercises/ex4/README.md) | Review ownership, architecture decision alignment, and EU AI Act classification; update the fact sheet via the AI Governance Assistant | 20 min |
| 5 | [Verify the Agent](exercises/ex5/README.md) | Mark the agent as verified and approved to run in production | 10 min |
| 6 | [Test in Joule Studio](exercises/ex6/README.md) | Switch to Joule Studio and confirm the verified agent runs; observe that unverified agents are blocked | 10 min |

**Total exercise time: 90 minutes**

## Prerequisites

- Access to the shared **SAP AI Agent Hub** tenant (credentials provided at the session)
- Access to your individual **Joule Studio** instance (provisioned before the session)
- A modern web browser (Chrome or Edge recommended)
- No prior experience with SAP AI Agent Hub required

## System Access

| System | URL | Credentials |
|--------|-----|-------------|
| SAP AI Agent Hub | *(provided at session)* | *(provided at session)* |
| Joule Studio | *(individual, provided at session)* | SAP Universal ID |

## Related Sessions

This workshop is the hands-on complement to the following sessions in the **Build Enterprise-Grade AI Governance as a Foundation** subtrack. Attending them before or after this workshop will deepen your understanding.

| Session | Type | Title | Why it's relevant to this workshop |
|---------|------|-------|-------------------------------------|
| ST127 | Strategy Talk | Scale AI with confidence with governance built for the agentic era | Frames the problem this workshop solves — AI spreading faster than organizations can govern it |
| BT102 | Deep Dive | From AI sprawl to AI governance with SAP AI Agent Hub | Deep-dive on the product you will use in this workshop; ideal preparation if you are new to SAP AI Agent Hub |
| BT116 | Deep Dive | How SAP SE governs AI sprawl with SAP AI Agent Hub | Real-world use case from SAP's own corporate IT team — the governance workflow in practice |
| BT115 | Deep Dive | Monitor your AI agents with the SAP Cloud ALM solution | Covers the observability layer that sits alongside governance — what happens after you verify an agent |
| BT800 | Road Map | SAP LeanIX solutions road map for AI-native enterprise architecture | What's coming next for the platform underlying this workshop |

Attending sessions in the **Accelerate and Derisk Your AI-Native Transformation** subtrack provides further context on how AI governance connects to the broader enterprise architecture practice:

| Session | Type | Title |
|---------|------|-------|
| BT100 | Deep Dive | Make architecture data collection faster, easier, and more reliable with AI |
| BT160 | Hands-on Workshop | Build AI-native tools and agents with MCP server for SAP LeanIX solutions |
| ST101 | Strategy Talk | Navigating AI-native enterprise architecture with SAP LeanIX solutions |

## Further Resources

- [SAP AI Agent Hub Documentation](https://help.sap.com)
- [SAP LeanIX — EA Context for AI Governance](https://www.leanix.net)
- [EU AI Act — Official Text](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX:32024R1689)