# Claude Skills Pack - Trigger Examples

This repo documents 26 custom Claude skills that turn Claude into a virtual AI team of specialists. Each skill auto-triggers based on what you ask, no need to name it explicitly.

Below is one worked example prompt per skill.

## Business & Marketing

## AI Research Analyst
Executive-level market research, competitor analysis, and strategic business intelligence.
Example: "Is the AI note-taking app market worth entering in 2026? Map the competitors and tell me if there's a real opening."

## AI Workflow Architect
Designs AI systems, automations, and agent workflows for businesses.
Example: "My team manually copies support tickets into a spreadsheet every day. Can this be automated?"

## Business Growth Consultant
Diagnoses the real constraint on a business's growth and prioritizes the highest-leverage fixes.
Example: "My SaaS has been stuck at $40k MRR for six months. How do I get growth moving again?"

## CEO Advisor
Founder coaching and strategic decision pressure-testing.
Example: "We're deciding whether to raise a $2M seed round or stay bootstrapped. What should I be weighing?"

## Chief Content Officer
Builds content strategy, calendars, and platform-specific growth plans.
Example: "Give me a content strategy for growing our B2B SaaS on LinkedIn this quarter."

## Landing Page CRO Expert
Audits and rewrites landing pages for conversion.
Example: "Here's my product page URL, why isn't it converting?"

## Marketing Campaign Planner
Designs multi-channel marketing campaigns and product launches.
Example: "I'm launching a new feature next month. Help me plan the announcement across channels."

## Newsletter Writer
Writes newsletters and marketing emails people actually want to open.
Example: "Write this week's newsletter about our new pricing model."

## Prompt Optimizer
Turns rough prompts into production-quality prompts for any AI model.
Example: "This prompt keeps giving me generic output: 'write me a blog post about productivity.' Make it better."

## SaaS Idea Validator
Brutally honest evaluation of startup/SaaS ideas.
Example: "Is a SaaS tool for freelancer invoicing a good idea? Be honest."

## UX & Product Auditor
Senior-level UX and product-strategy audits tied to business outcomes.
Example: "Here's a screenshot of our onboarding flow. What's causing drop-off?"

## YouTube Producer
Plans, scripts, and packages long-form YouTube videos for retention and growth.
Example: "I want to make a video about why AI still struggles with hands. Help me package and script it."

## QA

## Test Plan & Case Architect
Turns requirements or user stories into a structured test plan and coverage matrix.
Example: "Here's the user story for our new checkout flow. What should I test?"

## Bug Report & Triage Analyst
Writes clear, reproducible bug reports and triages severity and priority.
Example: "The app crashed when I hit submit twice fast. Here's the error log, write this up."

## Test Automation Strategist
Decides what's worth automating and recommends the framework and suite structure.
Example: "We have no automated tests and QA is drowning in manual regression. Where do we start?"

## Regression Risk Analyzer
Reads a diff or PR and flags what's actually at risk of breaking.
Example: "Here's my PR that touches the payment service. What should I regression test before merging?"

## Security & DevOps

## AppSec Code Reviewer
OWASP-grounded security review of code, tied to severity and a concrete fix.
Example: "Here's my login endpoint code. Is it safe?"

## CI/CD & IaC Pipeline Auditor
Reviews pipelines, Terraform, and Kubernetes manifests for security and best practice.
Example: "Here's our GitHub Actions workflow and Terraform file for the prod deploy. Does this look right?"

## Threat Modeler
Builds a STRIDE-style threat model for a system or feature before it's built.
Example: "We're adding a file-upload feature that stores user documents in S3. What could go wrong?"

## Incident Postmortem Advisor
Structures blameless incident postmortems and root-cause writeups.
Example: "Our API was down for 40 minutes last night. Here are my raw notes, help me write the postmortem."

## Grafana Dashboard & Monitoring Designer
Designs Grafana dashboards, SLOs, and alerting rules for a service.
Example: "What should I be monitoring for our new checkout microservice, and how should the dashboard be laid out?"

## Crypto

## Crypto Due-Diligence Analyst
Researches a token's tokenomics, team, on-chain activity, and competition. Not financial advice.
Example: "Can you research this token's tokenomics and team before I look into it further?"

## DeFi/Smart Contract Risk Auditor
Assesses a DeFi protocol's audit history, admin permissions, and exploit history. Not a formal audit or financial advice.
Example: "I'm considering providing liquidity on this protocol. What's the risk picture on their contracts?"

## Crypto Trading Journal & Discipline Coach
Logs trades and surfaces behavioral patterns like sizing inconsistency or stop discipline. Never gives trading signals.
Example: "I just closed a trade that hit my stop. Log it and tell me if you see a pattern with my last few trades."

## Portfolio Risk & Allocation Reviewer
Reviews concentration, correlation, and volatility risk in a portfolio against your own stated risk tolerance. Not financial advice.
Example: "Here's my current portfolio allocation. Am I too concentrated given that I'm risk-averse with a long time horizon?"

## Crypto Trading Strategy Analyst
Helps formalize and stress-test a rules-based trading strategy. Does not execute trades or give live signals.
Example: "I have a moving-average crossover strategy idea. Help me define the exact rules and find where it would fail."

---

Each skill lives as a SKILL.md file with its own identity, workflow rules, scoring rubrics, and worked examples. Ask Claude naturally and the right one activates.
