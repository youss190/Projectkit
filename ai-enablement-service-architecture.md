# AI Enablement Service Architecture

Oct 18, 2026

## Value proposition

We make AI use safe and productive across the whole company. Every team learns where AI helps, which tools it may use, what rules apply, and how to run AI projects that deliver measurable value.

The problem we solve: most companies are stuck between banning AI (staff use it anyway, as shadow AI) and allowing it without rules (data leaks, compliance gaps). We replace both with a clear, professional middle path.

**Service principles**

- **Enable by default.** Classify the data, not the tool. Most work can use AI today; rules apply only where the data or the use requires them.
- **Three environments, one rule.** The most sensitive data in a task decides whether it runs on open tools, EU cloud services or local models.
- **Governance in proportion to risk.** Light rules for low-risk work, strict controls for high-risk uses under the EU AI Act and GDPR.
- **Value you can measure.** Every use case has a baseline, a target and a tracked result.
- **Built to hand over.** The customer owns the toolkit and can run it without us.

## Customer pathway

Customers move through six phases, each closed by a gate decision, so value starts early and governance is in place before scale.

![Customer pathway: 6 phases, 5 gates](img/customer-pathway.png)

Classify is the pivot: once tiers are signed off, Tier 1 quick wins can go live while governance and pilots continue.

## AI opportunity mapping

Each business function gets a ranked list of AI use cases, built from its real tasks rather than from a vendor catalogue.

1. **Function workshops (90 min each).** Team leads list recurring tasks, time spent and pain points.
2. **Task inventory.** Tasks are tagged by AI pattern: draft, summarise, search and answer, classify, extract, analyse, automate, or agent.
3. **Score each use case** on value and feasibility (table below).
4. **Place it in the portfolio** and pick the next actions per quadrant.

| Dimension | Criterion | Scored 1 to 5 on |
| --- | --- | --- |
| Value | Time saved | Hours per month across all users |
| Value | Business impact | Revenue, quality, customer or employee experience |
| Value | Reach | Number of people or processes affected |
| Feasibility | Data readiness | Data exists, is accessible and is clean enough |
| Feasibility | Tool maturity | Off-the-shelf tool vs. custom build |
| Feasibility | Risk and tier | Environment tier and EU AI Act risk class (higher risk scores lower) |

| Quadrant | Value | Feasibility | Action |
| --- | --- | --- | --- |
| Quick wins | High | High | Launch now with approved tools and training |
| Strategic bets | High | Low | Run as a governed pilot project |
| Fill-ins | Low | High | Allow self-service under the AI policy |
| Park | Low | Low | Revisit at the quarterly review |

## AI environment tiers

The most sensitive data in a task decides its tier. The EU AI Act risk class of the use then adds controls on top, whatever the tier.

![Tier decision: 2 questions, 3 tiers, 1 AI Act check](img/tier-decision.png)

| Tier | Data allowed | Typical environment | Minimum conditions |
| --- | --- | --- | --- |
| 1. Open | Public or non-sensitive internal data | Mainstream SaaS AI assistants on business plans | Business licence, training on inputs switched off, no personal or confidential data |
| 2. EU cloud | Personal data (GDPR), customer and confidential business data | EU-hosted models or EU-region cloud AI services | EU data residency, signed DPA, no training on inputs, sub-processor list checked, logging |
| 3. Local | Special-category data, trade secrets, privileged legal matters, regulated or classified information | Open-weight models on own servers or a private cloud | No data leaves the company network, access control, model and prompt logging |

Open decision for each customer: whether US-owned providers running in EU regions count as Tier 2. Their legal exposure to US law differs from EU-owned providers, so the customer's legal team signs this off.

**Default tier by function**

| Function | Typical AI uses | Default tier | Moves up a tier when |
| --- | --- | --- | --- |
| Marketing and comms | Content drafts, SEO, campaign ideas, translation | 1. Open | Customer lists or unreleased launches are involved (2) |
| Sales | Proposals, CRM summaries, account research | 2. EU cloud | Pricing strategy or bid secrets are involved (3) |
| Customer service | Reply drafts, ticket triage, knowledge-base assistant | 2. EU cloud | Health or financial customer data is involved (3) |
| HR | Job ads, policy Q&A, onboarding material | 1. Open | Candidate or employee data (2); health or disciplinary data (3); screening and ranking candidates is high-risk under the AI Act |
| Finance | Reporting, forecasting, invoice processing | 2. EU cloud | Unreleased results, M&A or banking credentials (3) |
| Legal and compliance | Contract review, regulatory research | 2. EU cloud | Privileged or litigation matters (3) |
| IT and software | Coding assistants, documentation, support scripts | 2. EU cloud | Security configurations or core proprietary code (3) |
| R&D and product | Ideation, research summaries | 1. Open | Proprietary designs, formulas or patents pending (3) |
| Operations and supply chain | Demand forecasts, SOPs, supplier analysis | 2. EU cloud | Production secrets or critical infrastructure (3) |
| Leadership and strategy | Market analysis, briefings | 1. Open | Board papers, strategy or deal work (3) |

## Governance toolkit

The customer gets ten ready-to-adapt templates that cover the full lifecycle of an AI use case: intake, classify, approve, operate, review.

| # | Component | What it does | Format |
| --- | --- | --- | --- |
| 1 | AI acceptable-use policy | States what staff may and may not do, in two pages | Policy document |
| 2 | Data and tier matrix | Maps data types to the three environment tiers | One-page matrix |
| 3 | Approved tool catalogue | Lists approved tools per tier, with owner and licence | Living register |
| 4 | Use-case intake and risk form | Captures purpose, data, tier, AI Act risk class and DPIA trigger | Form, 15 minutes to fill |
| 5 | Vendor due-diligence checklist | Checks data residency, DPA, training opt-out, sub-processors and security | Checklist |
| 6 | Roles and RACI | Names the AI owner, the governance board and the champion network | RACI chart |
| 7 | AI literacy programme | Meets the AI Act duty for staff AI literacy; role-based modules | Training plan and materials |
| 8 | Human oversight rules | Defines when a person must check, approve or sign AI output | Rule card per tier |
| 9 | Incident and issue log | Records data leaks, wrong outputs and misuse, with response steps | Register and playbook |
| 10 | Review cadence | Quarterly review of the register, tools and regulation changes | Calendar and agenda template |

## AI-native project management toolkit

AI projects fail differently from IT projects: output quality varies, models change, and value depends on adoption. The toolkit runs every use case through five short stages with a clear go or stop decision at each.

1. **Ideate.** Fill in the use-case canvas.
2. **Validate (about 2 weeks).** Test with real data against a small golden test set.
3. **Pilot (4 to 6 weeks).** A small user group, with success and kill criteria set in advance.
4. **Scale.** Rollout, training, and entry into the tool catalogue.
5. **Operate.** Owner, monitoring and quarterly re-evaluation.

| Tool | Purpose |
| --- | --- |
| Use-case canvas | One page: problem, users, data, tier, value hypothesis, KPI, owner |
| Pilot charter | Scope, timebox, success criteria and kill criteria |
| Evaluation kit | Golden test set, quality rubric and acceptance threshold; re-run when a model changes |
| Prompt and workflow library | Versioned, owned and reviewed prompts, assistants and automations |
| Human-in-the-loop map | Marks where people check, approve or escalate in each workflow |
| Value tracker | Baseline vs. actual: hours saved, cost, quality, adoption |
| Adoption dashboard | Active users and usage per function and per tool |
| AI-assisted PM routines | AI-drafted status reports, meeting notes to action items, risk-log updates |

The project team uses AI for its own project work, so the method itself demonstrates the gains.

## Service packages and success metrics

Three packages let customers start small and grow. Each one builds on the one before.

| Package | Phases covered | Indicative length | Deliverables |
| --- | --- | --- | --- |
| AI Readiness Scan | Align, Discover, Classify | 3 to 4 weeks | Opportunity map, function tier matrix, quick-win list, leadership briefing |
| AI Enablement Programme | All phases up to Pilot | 10 to 12 weeks | Scan deliverables, full governance toolkit, AI literacy training, 2 to 3 governed pilots |
| AI Partner retainer | Scale and Sustain | Ongoing, quarterly | Quarterly reviews, new use-case intake, tool vetting, regulation updates, champion coaching |

| Metric | Measures |
| --- | --- |
| Approved-tool adoption | Share of staff active on approved AI tools |
| Shadow AI | Unapproved AI tools in use, from survey or network data |
| Time saved | Hours saved per employee per month, against the baseline |
| Use cases live | Use cases in production per function |
| Idea to pilot | Days from intake form to pilot start |
| AI incidents | Logged incidents and their time to resolution |

Open questions: pricing per package, and which partner vendors to recommend for Tier 2 and Tier 3.

Living version: [Claude Doc](https://claude.ai/code/artifact/eecd7289-81de-48ea-9de7-8fcbca559577)
