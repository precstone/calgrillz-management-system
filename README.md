# CalGrillz Business & Financial Management System

> AI-integrated operational and financial management platform for a food service business, combining day-to-day operations with conversational business analytics. In active production use.

## Overview

A business management system built specifically for a food service operation in Nigeria, combining operational tracking (sales, inventory, staff activity) with financial reporting (revenue, expenses, profitability) in a single platform — and extended with a **Claude API integration** that turns operational data into conversational insights.

## The problem

Food service businesses generate a constant stream of data — sales transactions, inventory movements, daily expenses — but most small operators have no way to turn that data into decisions. Spreadsheets grow unmanageable; dashboards require technical skill; staff spend hours on paperwork that never becomes insight.

## The solution

A single platform capturing every operational and financial event, with an AI layer on top that lets the business owner interact with their own data conversationally. Questions like "How did sales compare to last week?" or "Which items are underperforming?" return plain-language answers with context, not raw numbers.

## Key features

- **Sales and transaction recording** — real-time capture of every sale
- **Inventory and stock management** — ingredient and stock tracking with consumption logs
- **Expense tracking** — categorised expense recording
- **Financial summaries and reporting** — revenue, costs, and profitability views
- **Daily, weekly, and monthly operational views** — period-over-period comparisons

## AI features (Claude API integration)

- **Natural language querying** — the owner asks questions about the business in plain English
- **Automated summaries** — daily, weekly, and monthly performance summaries generated automatically
- **Analysis and insights** — proactive identification of trends, anomalies, and opportunities
- **Recommendations** — AI-generated suggestions on pricing, inventory, and operational adjustments

## Tech stack

- **Backend:** PHP
- **Frontend:** JavaScript, HTML, CSS
- **Database:** MySQL
- **AI layer:** Claude API (Anthropic)
- **Deployment:** Standard LAMP stack hosting

## Architecture highlights

- **Unified operational-financial data model** — sales, inventory, and expenses share a consistent transactional schema, allowing the AI layer to reason across operational and financial dimensions together
- **Role-based access control** — owner, manager, and staff views with appropriate permissions
- **AI orchestration layer** — structured business data is passed to Claude with carefully designed prompts for consistent, business-relevant output
- **Pre-generated summaries** — common analytical queries are cached to reduce latency and API cost

## My role

Sole developer. Requirements gathering with the business owner, system design, full-stack development, Claude API integration, deployment, and ongoing support.

## Status

🟢 **Live and in daily use** for day-to-day operations and decision-making. The AI layer is actively used by the business owner.

## Note on source code

The source code is not publicly available as it runs on the client's production infrastructure and handles business-confidential financial data. This repository documents the system's design and technical decisions.

---

**Built by [Precstone Iroroh](https://www.linkedin.com/in/iroroh-precstone/) — Founder, Unearth Tech Ltd**
