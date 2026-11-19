# Tarik Riley · BMI2 — AI Engineering Portfolio

**Four AI products, built solo with an AI-native workflow: governed AI agents, evidence-first diagnostics, and the
monitoring and governance layer that watches them.**

[bmi2.com](https://www.bmi2.com/) ·
[Recorded demos](https://www.bmi2.com/demos/) ·
[Engineering approach](https://www.bmi2.com/engineering/) ·
[Background](https://www.bmi2.com/work-with-tarik/) ·
[Contact](mailto:triley@bmi2.com?subject=Portfolio%20review)

> **This is a public, sanitized showcase.** The four products' source repositories are private because they hold
> proprietary code, lab configuration and private history. This repository describes what was built, how, and with
> what evidence. It contains no source code, prompts, credentials, customer data or deployment assets. A live
> walkthrough or a time-limited private code review is available on request.

## The products

| Product | What it is | Status, Nov 2026 | Read more |
|---|---|---|---|
| **Fiduciary** | A governed AI coworker for capital-investment lending: AI agents gather permitted evidence, cite it, and draft each next step from prospect intake to payoff, while a person signs every step that moves money. | Private preview, running in the BMI2 lab on synthetic data | [products/fiduciary.md](products/fiduciary.md) |
| **TestPulse** | Evidence-first AI diagnostics for failed network logins (802.1X, RADIUS, TACACS+). It names the cause, cites the packets and log lines behind it, and trains small vendor-specific models from human-certified results. | Available now; deployed on Kubernetes in the BMI2 lab | [products/testpulse.md](products/testpulse.md) |
| **AIM** | Agentic Integrated Management: monitoring, business assurance and governance for the AI applications themselves, applying the telecom FCAPS discipline to AI. | Running in the BMI2 lab | [products/aim.md](products/aim.md) |
| **A&R** | A governed AI workflow for music artist development: roster Q&A with a confidence gate, and AI-drafted actions (Slack posts, schedule and spreadsheet changes) that a person approves. | Design-partner stage | [products/ar.md](products/ar.md) |

All four share one engine and one rule: **the AI reads only what the user is permitted to see, cites its evidence,
and never acts without a person's approval.**

## Velocity, measured from git

Counted from GitHub on 2026-11-17, across the four private repositories:

| Measure | Figure |
|---|---|
| Merged pull requests built with Claude Code | **1,150**, April to November 2026, all authored by me |
| AIM, from design decision to production-shaped service | **100 merged PRs in 41 days** (Oct 7 to Nov 17) |
| Fiduciary | **842 merged PRs in 16 weeks**, 162 of them in the last 30 days |
| Automated test functions (Python and TypeScript) | **about 29,000** |
| Architecture Decision Records (Fiduciary alone) | **78** |
| TestPulse MCP server | **155** tool functions |

These count tests *written*, not a pass rate. Per-repository breakdowns are in [ENGINEERING.md](ENGINEERING.md).

## How I work

Speed only matters if the code is right. Every change goes through the same loop: a short decision record, a branch
written with Claude Code, tests that must fail without the change and pass with it, an independent AI review, a merge
pinned to the exact reviewed commit, and a check that it works live in a real browser. Details, and an example of a
real defect the process caught, are in [ENGINEERING.md](ENGINEERING.md).

## Stack across the portfolio

Python 3.12 · FastAPI · Postgres with row-level security and pgvector · Keycloak · React and TypeScript (Vite) ·
MCP servers · AWS Bedrock (Claude, DeepSeek-R1, Titan embeddings) · Amazon SageMaker (QLoRA training) ·
Kubernetes, KubeVirt and Argo CD · NATS JetStream · OPA · Prometheus and Grafana · Langfuse · Playwright ·
garak and PyRIT for red-team scanning

## Background

Twenty years in telecom automation and test engineering at AT&T, Verizon, Spirent, Viasat and DISH, before founding
BMI2 in Round Rock, Texas.

## Intellectual property

Copyright © 2025–2026 Tarik Riley / BMI2. All rights reserved. This repository is provided for portfolio review. No
license is granted to copy, modify, redistribute, reverse engineer, or use the products, branding, designs, or
documentation except as permitted in writing by BMI2. See [NOTICE.md](NOTICE.md).
