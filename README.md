# PULSE - Keeta User Operations Intelligence Proposal

This repository contains a product strategy and PRD-style case study for PULSE, an AI-assisted User Operations Intelligence Platform concept for Keeta.

PULSE is designed to help User Operations, Growth, and Product teams:
- unify user lifecycle data across markets,
- predict churn and reactivation opportunities early,
- execute targeted campaigns with human approval,
- measure true incremental impact through built-in experimentation.

## Important Disclaimer

This is an independent case study prepared for internship application purposes.
- It is not an official Meituan or Keeta internal document.
- It is based on public information and industry references.
- Any numerical targets, model outputs, and financial impact figures are illustrative assumptions for demonstration.

## Repository Contents

- PULSE-Keeta-PRD-Krishna-Nagpal.html
	- Full interactive PRD document with navigation, diagrams, wireframes, and concept demos.
- README.md
	- High-level summary of the same proposal.

## Product Vision

PULSE proposes one shared intelligence layer across Keeta markets so teams can move from reactive retention to predictive, precise, and measurable intervention.

Core design principles:
1. Human-approved, not human-replaced
2. Predict early, act precisely
3. One platform for all markets with local calibration
4. Incrementality-first experimentation
5. Privacy and governance by design

## Problem PULSE Addresses

The proposal highlights four structural gaps:
1. Fragmented market-level data and definitions
2. Reactive churn handling instead of early prediction
3. Blunt discount-heavy retention spend
4. Operational velocity that does not scale with expansion

## Scope and Feature Set

The proposal defines a phased feature stack:

### P0 (Foundation / MVP-critical)
- Unified User 360 Profile
- Predictive Intelligence Engine (churn, reactivation, LTV, next-best-action)
- Real-Time Ops Dashboard and Alerting
- Governance, Privacy, and Approval Guardrails

### P1 (Execution and Scale)
- Smart Segmentation and Audience Builder
- Campaign Orchestration and Personalization
- Experimentation and Optimization Hub
- Insights and Reporting Layer

### P2 (Advanced)
- PULSE Copilot (natural-language ops assistant)

## Core Workflow

System loop:
1. Ingest multi-market behavioral data
2. Build User 360 features
3. Score users with predictive models
4. Recommend next best action and segment
5. Require human review and approval
6. Deliver campaigns and track outcomes
7. Feed outcomes back into model retraining

## User and Journey Focus

The PRD distinguishes:
- Platform users (regional ops managers, growth analytics leads, leadership)
- Customer behavioral archetypes (for example habitual users, deal-chasers, onboarding users, quietly slipping users)

A key thesis is that the Waver stage (declining frequency before full dormancy) is the highest-leverage intervention point.

## KPIs and Measurement

North Star Metric:
- D90 Retained-User Rate

Supporting metric groups:
- Retention and engagement (D30, D60, reactivation, churn, waver recovery)
- Commercial efficiency (cost per retained user, incremental GMV, discount dependency)
- Model health (precision, recall, AI-assisted lift vs holdout)
- Operational velocity (time to launch, AI-brief adoption)
- Customer guardrails (post-intervention CSAT/NPS, message fatigue)

## Experimentation Framework

The proposal uses a strict incrementality approach:
- Holdout group by default
- Pre-registered primary metric
- Power and sample-size planning
- Continuous guardrail monitoring
- Scale/iterate/kill decisions based on predefined criteria

## Implementation Roadmap

Planned progression:
- Phase 0 (Month 0-3): Discovery and data foundation
- Phase 1 (Month 3-6): MVP and first holdout-based campaigns
- Phase 2 (Month 6-9): Orchestration and multi-market rollout
- Phase 3 (Month 9-12+): Copilot and advanced optimization at scale

## Risks Covered in the PRD

The document includes mitigations for:
- privacy and regulatory compliance,
- model bias and cross-market transfer issues,
- discount overuse,
- adoption and change management,
- localization constraints,
- generative assistant reliability,
- message fatigue,
- competitive response,
- expansion pacing risk.

## How to View the Proposal

Open PULSE-Keeta-PRD-Krishna-Nagpal.html in a browser to view the full interactive PRD.

## Author

Krishna Nagpal
- BITS Pilani, Dubai Campus
- LinkedIn: https://linkedin.com/in/krishnanagpal