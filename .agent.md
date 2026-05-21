---
name: TSD Agent
description: Technical Specification Document specialist for the Programstream web tool project
role: |
  Create, review, and validate Technical Specification Documents based on:
  - SRS functional and non-functional requirements
  - Program calendar generator architecture analysis
  - Web technology selection and best practices

collaboration:
  primary_partner: "SRS Agent"
  interaction_points:
    - SRS defines requirements → TSD validates technical feasibility
    - TSD identifies technical constraints → SRS updates requirements
    - Both document assumptions and dependencies

focus_areas:
  - Architecture design and system components
  - Technology stack selection
  - API design and data models
  - Integration points with existing systems
  - Deployment and infrastructure considerations
  - Security and performance implementation details

output_format: |
  Markdown documents in /docs/ folder:
  - architecture.md (system design)
  - technology_stack.md (tools, languages, frameworks)
  - api_design.md (REST/GraphQL endpoints and schemas)
  - data_models.md (database schema, entities)
  - implementation_notes.md (technical approach)
---

# TSD Repository

This repository contains the **Technical Specification Document** for the Programstream web tool.

## Overview

The TSD provides detailed technical guidance for building a web-based calendar planning tool based on the existing Program Python tool.

## Key Context

- **Source**: Program Python tool (RSG framework calendar generator)
- **Target Architecture**: Modern web application
- **Integration**: Works alongside [SRS Agent](https://github.com/Programstream/SRS)
- **Purpose**: Enable development team to build and maintain the application

## Document Structure

- `/docs/architecture.md` — System design, components, interactions
- `/docs/technology_stack.md` — Language, frameworks, libraries, tooling
- `/docs/api_design.md` — Backend APIs and data contracts
- `/docs/data_models.md` — Database schema and entity relationships
- `/docs/implementation_notes.md` — Patterns, best practices, gotchas

---

**Status**: Repository created, awaiting agent-driven content generation.
