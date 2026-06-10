# Agent-X

Multi-Agent Workflow Orchestration Platform for Intelligent Sales Automation

Agent-X is a modular multi-agent orchestration system designed to automate the complete outbound sales workflow, from lead acquisition to CRM synchronization. The platform combines event-driven workflows, LLM-powered decision making, and backend automation infrastructure to reduce manual effort in sales operations.

---

## Overview

Agent-X was developed as part of AZOX Automations to explore how AI agents can collaborate across a shared memory and workflow infrastructure.

The platform automates:

- Lead ingestion
- Company enrichment
- Prospect scoring
- Personalized outreach generation
- Email response classification
- Meeting scheduling
- CRM synchronization
- Internal notifications

All workflows are orchestrated through event-driven pipelines with persistent memory, retry handling, and distributed coordination.

---

## Core Features

### Multi-Agent Architecture

Specialized AI workers collaborate through a shared backend infrastructure:

- Lead Intelligence Agent
- Enrichment Agent
- Outreach Agent
- Response Analysis Agent
- CRM Sync Agent
- Scheduling Agent

---

### Workflow Orchestration

- 11 event-driven workflows
- Token-authenticated webhook endpoints
- Idempotent event processing
- Automated retry queues
- Failure recovery mechanisms

---

### Backend Infrastructure

#### PostgreSQL

- 17-table relational schema
- UUID-based primary keys
- JSONB document storage
- Indexed query paths
- Workflow state persistence

#### Redis

- Distributed locking
- Conversation memory
- Email deduplication
- API response caching
- Rate-limit counters
- Temporary workflow state storage

---

### AI Layer

- OpenAI API integration
- Context-aware outreach generation
- Conversation summarization
- Reply intent classification
- Automated lead qualification

---

### Third-Party Integrations

Current integrations include:

- Gmail
- HubSpot
- Salesforce
- Calendly
- Apollo
- Clearbit
- Crunchbase
- Slack
- OpenAI

---

## Technology Stack

### Languages

- Python
- SQL

### Infrastructure

- PostgreSQL
- Redis
- Docker

### Automation

- n8n

### AI

- OpenAI API

### Development Tools

- Git
- Linux
- VS Code

---

## System Architecture

Architecture diagrams and workflow screenshots will be added in future updates.

---

## Current Status

Active Development

The platform is continuously evolving with improvements in:

- Workflow reliability
- Agent memory
- CRM integrations
- Observability
- Multi-tenant support

---

## Future Roadmap

- Multi-tenant deployment
- Agent monitoring dashboard
- Workflow analytics
- Role-based access control
- Additional CRM integrations
- Advanced memory architecture

---

## Author

Yash Dev Kumar Sahni

Founder & Technical Lead  
AZOX Automations

Website: https://azox.in

---

## Disclaimer

This repository contains selected project artifacts, documentation, and implementation details intended for portfolio and educational purposes.
