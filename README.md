# Claude Skills Pack

A pack of 26 custom Claude skills that work together as a virtual AI team. Each one is a specialist that auto-triggers based on what you ask, no need to name it explicitly.

## Business & Marketing

AI Research Analyst: executive-level market research and competitive intelligence.
AI Workflow Architect: designs AI systems and automation workflows.
Business Growth Consultant: diagnoses growth constraints and prioritizes fixes.
CEO Advisor: founder coaching and decision pressure-testing.
Chief Content Officer: content strategy and platform-specific growth plans.
Landing Page CRO Expert: landing page audits and conversion rewrites.
Marketing Campaign Planner: multi-channel campaign and launch planning.
Newsletter Writer: newsletters and marketing emails that people open.
Prompt Optimizer: turns rough prompts into production-quality prompts.
SaaS Idea Validator: brutally honest startup idea evaluation.
UX & Product Auditor: UX and product-strategy audits tied to business outcomes.
YouTube Producer: video planning, scripting, and packaging.

## QA

Test Plan & Case Architect: turns requirements into a structured test plan and coverage matrix.
Bug Report & Triage Analyst: writes reproducible bug reports and triages severity/priority.
Test Automation Strategist: decides what's worth automating and picks the framework.
Regression Risk Analyzer: reads a diff/PR and flags what's actually at risk of breaking.

## Security & DevOps

AppSec Code Reviewer: OWASP-grounded security review tied to severity and a fix.
CI/CD & IaC Pipeline Auditor: reviews pipelines and Terraform/Kubernetes manifests for security.
Threat Modeler: STRIDE-style threat modeling for a system or feature.
Incident Postmortem Advisor: blameless postmortems and root-cause writeups.
Grafana Dashboard & Monitoring Designer: dashboards, SLOs, and alerting rules.

## Crypto

Crypto Due-Diligence Analyst: researches a token's tokenomics, team, and on-chain activity. Not financial advice.
DeFi/Smart Contract Risk Auditor: assesses protocol risk before you interact with it. Not a formal audit or financial advice.
Crypto Trading Journal & Discipline Coach: logs trades and surfaces behavioral patterns. Never gives trading signals.
Portfolio Risk & Allocation Reviewer: checks concentration and correlation against your own risk tolerance. Not financial advice.
Crypto Trading Strategy Analyst: formalizes and stress-tests a rules-based strategy. Does not execute trades or give live signals.

See SKILLS.md for a worked trigger-example prompt for each skill.

## Adding a new skill

This pack is meant to grow. See CONTRIBUTING.md for the file format and a copy-paste template for writing a new skill and adding it here.

## Format

Each skill is a single markdown file with YAML frontmatter (name and description) followed by the skill's instructions. The description is what determines when the skill auto-triggers, so it should be specific about what the skill does and what kind of request should activate it.

## A note on the crypto and financial skills

The crypto skills in this pack are research, risk-assessment, and discipline tools. None of them execute trades, connect to an exchange or wallet, or give personalized buy/sell recommendations, and each one says so explicitly. They are built to give you the information and structure to make your own decisions, not to make decisions for you.
