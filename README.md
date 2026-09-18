# From Discovery to Decommissioning: A Hands-On AI Governance Workshop

## Session Overview

Shadow AI is already in your organization. This workshop shows you what to do about it.

Working inside **SAP LeanIX**, you will use the AI Agent Hub capabilities to discover agents across SAP and third-party software environments, assess them against governance criteria, assign ownership and risk classification, verify them, and communicate governance outcomes to stakeholders.

## Business Scenario

**GlobalFlex AG** produces custom industrial components for the automotive and aerospace sectors. The company employs 8,000 people across 12 countries and runs a hybrid IT landscape with SAP S/4HANA as its ERP backbone, Microsoft 365 for collaboration, and a growing set of AI agents introduced by different lines of business — often without central visibility or governance.

The IT department recently received an audit finding: **no central inventory of AI systems exists**, and several business units are running AI agents that touch sensitive data without formal risk assessment. The CIO has tasked the EA team to establish AI governance within 90 days.

> You are a member of that EA team. You start your week by opening SAP LeanIX — your command center for everything AI in the organization. New agents have been discovered. One of them has never been reviewed. You need to understand what it does, who owns it, whether it meets your governance requirements, and ultimately decide whether to approve it.

## What You Will Learn

SAP LeanIX's AI Agent Hub gives you a single place to view and govern all AI agents, MCP servers, and LLMs deployed across your landscape — SAP-native, custom-built, and third-party. In this workshop you will experience the full governance lifecycle for a newly discovered agent:

- Use the **dashboard and inbox** to spot and triage new discoveries
- Use the **AI Governance Assistant** to find similar agents already in your landscape
- Manage **agent succession** by linking a phased-out agent as a predecessor
- Complete a **governance profile**: assign ownership, generate a description with LeanIX AI, and create an architecture decision record
- Send a **survey** to the agent's business owner to collect missing fields — and wait for the response before verifying
- **Verify** the agent once the full governance record is in place

## Session Structure

| # | Exercise | Description | Duration |
|---|----------|-------------|----------|
| GS | [Getting Started](exercises/ex0/README.md) | Log in to SAP LeanIX; orient in the AI Agent Hub interface | 10 min |
| 1 | [The Governance Dashboard](exercises/ex1/README.md) | Explore AI Agent Hub as your command center; find your pre-named agent in the Discovery Inbox | 15 min |
| 2 | [From Discovery to Inventory](exercises/ex2/README.md) | Review your agent's discovery details and analytics; add it to the governed inventory | 15 min |
| 3 | [Find Similar Agents & Set a Predecessor](exercises/ex3/README.md) | Use the AI Governance Assistant to find existing agents with similar capabilities; link the phased-out agent as a predecessor | 15 min |
| 4 | [Prepare the Fact Sheet](exercises/ex4/README.md) | Assign ownership, generate a description with LeanIX AI, and create an architecture decision record | 15 min |
| 5 | [Collect Missing Information via Survey](exercises/ex5/README.md) | Send a survey to the agent's business owner for AI Type, AI Risk, AI Model, and Owner; wait for the response | 15 min |
| 6 | [Verify the Agent](exercises/ex6/README.md) | Confirm the full governance checklist is complete and mark the agent as verified | 10 min |

**Total exercise time: 95 minutes** *(facilitators: exercise 3 can be shortened if the group runs behind)*

## Prerequisites

- Access to the shared **SAP LeanIX** workspace (credentials provided at the session)
- A modern web browser (Chrome or Edge recommended)
- No prior experience with SAP LeanIX or AI Agent Hub required

## System Access

| System | URL | Credentials |
|--------|-----|-------------|
| SAP LeanIX | *(provided at session)* | *(provided at session)* |

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
