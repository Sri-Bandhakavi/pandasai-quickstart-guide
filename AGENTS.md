# Agents

## Overview

This project explores how semantic layers and multi-dataset agent orchestration can improve natural language analytics workflows using PandasAI and PostgreSQL-backed datasets.

The notebook evolves from single-dataset querying toward a shared multi-dataset analytical agent capable of:

* semantic joins
* temporal aggregation
* derived metric handling
* business-context-aware querying
* analytical visualization generation

---

## Dataset-Level Semantic Layers

Each dataset is configured with semantic metadata including:

* column descriptions
* aliases
* grouping hints
* derived metrics
* cross-table relationships

These semantic layers improve natural language understanding and help map business terminology to underlying database structures.

Example semantic concepts used in the project:

* `region` → `country`
* `platform` → `device_type`
* `revenue` → `amount_usd`

---

## Multi-Dataset Agent

A shared multi-dataset `Agent` was introduced to support:

* cross-table reasoning
* semantic relationship traversal
* multi-hop joins
* analytical querying across related business entities

Example datasets included in the shared agent:

* users
* subscriptions
* sessions
* payments

This enabled queries such as:

* average payment amount by country
* churn analysis by subscription plan and region
* monthly revenue trends by subscription plan

---

## Key Learnings

* Semantic metadata improved analytical querying and business-language interpretation.
* Explicit semantic relationship configuration was required for reliable join traversal.
* Multi-dataset agent initialization significantly improved cross-table analytical reasoning.

---

## Future Directions

Potential future improvements include:

* improved semantic layer persistence
* more consistent query execution and visualization generation
* integration into broader conversational analytics systems
