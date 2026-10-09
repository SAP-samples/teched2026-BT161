# From Discovery to Decommissioning: A Hands-On AI Governance Workshop

## Session Overview

Shadow AI is already in your organization. This workshop shows you what to do about it.

Working inside **SAP LeanIX**, you will use the AI Agent Hub capabilities to discover agents across SAP and third-party software environments, assess them against governance criteria, assign ownership and risk classification, verify them, and communicate governance outcomes to stakeholders.

## About SAP LeanIX and AI Agent Hub

**SAP LeanIX** is SAP's enterprise architecture management platform. It gives EA and IT governance teams a single place to maintain the inventory of all applications, technologies, and AI agents running in their organization, track their lifecycles, and connect the architecture landscape to business capabilities and strategy.

The **AI Agent Hub** is LeanIX's dedicated module for AI governance. It connects to SAP and third-party platforms to automatically discover AI agents, and provides structured workflows to assess, verify, and manage them across their full lifecycle. In this workshop, you take the role of an enterprise architect working in the LeanIX workspace.

> A short introduction to SAP LeanIX and the AI Agent Hub will also be presented at the start of the session.

## Business Scenario

**GlobalFlex AG** produces custom industrial components for the automotive and aerospace sectors. The company employs 8,000 people across 12 countries and runs a hybrid IT landscape with SAP S/4HANA as its ERP backbone, Microsoft 365 for collaboration, and a growing set of AI agents introduced by different lines of business — often without central visibility or governance.

The IT department recently received an audit finding: **no central inventory of AI systems exists**, and several business units are running AI agents that touch sensitive data without formal risk assessment. The CIO has tasked the EA team to establish AI governance within 90 days.

> You are a member of that EA team — part of the AI Governance Center of Excellence that GlobalFlex AG has just established. You start your week by opening SAP LeanIX — your central entry point for everything AI in the organization. New agents have been discovered. One of them has never been reviewed. You need to understand what it does, who owns it, whether it meets your governance requirements, and ultimately decide whether to approve it.

## What You Will Learn

SAP LeanIX's AI Agent Hub gives you a single place to view and govern all AI agents, MCP servers, and LLMs deployed across your landscape — SAP-native, custom-built, and third-party. In this workshop you will experience the full governance lifecycle for a newly discovered agent:

- Create an **Architecture Decision Record** to document a governance policy your committee just adopted
- Use the **dashboard and inbox** to spot and triage new discoveries
- Complete a **governance profile**: assign yourself as observer, and link the agent to the architecture decision
- Send a **survey** to the agent's business owner to collect missing fields — and wait for the response before verifying
- **Verify** the agent once the full governance record is in place
- **Decommission** a legacy agent by documenting its successor, closing the lifecycle, and removing its production approval

## Session Structure

| # | Exercise | Description | Duration |
|---|----------|-------------|----------|
| GS | [Getting Started](exercises/ex0/README.md) | Log in to SAP LeanIX; orient in the AI Agent Hub interface | 10 min |
| 1 | [The AI Agent Hub Dashboard](exercises/ex1/README.md) | Create an architecture decision; explore the dashboard and inventory | 20 min |
| 2 | [From Discovery to Inventory](exercises/ex2/README.md) | Review your agent's discovery details and analytics; add it to the governed inventory | 15 min |
| 3 | [Complete the Governance Profile](exercises/ex3/README.md) | Assign yourself as observer; link the architecture decision; note what goes to the survey | 15 min |
| 4 | [Collect Missing Information via Survey](exercises/ex4/README.md) | Send a survey to the agent's business owner for AI Type, AI Risk, AI Model, and Owner; wait for the response | 15 min |
| 5 | [Verify the Agent](exercises/ex5/README.md) | Confirm the full governance checklist is complete, set the lifecycle to Active, and mark the agent as verified | 15 min |
| 6 | [Decommission a Legacy Agent](exercises/ex6/README.md) | Link successor, close the lifecycle, and unverify a Phase Out agent to complete the governance cycle | 10 min |

**Total exercise time: 100 minutes**

## Prerequisites

- Access to the shared **SAP LeanIX** workspace at [https://url.sap/u5vhev](https://url.sap/u5vhev) — credentials shared during the live session
- A modern web browser (Chrome or Edge recommended)
- No prior experience with SAP LeanIX or AI Agent Hub required

## System Access

| System | URL | Credentials |
|--------|-----|-------------|
| SAP LeanIX | [https://url.sap/u5vhev](https://url.sap/u5vhev) | Shared during the live session |

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
