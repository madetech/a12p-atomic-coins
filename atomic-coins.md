# DevOps Apprenticeship Coins (Level 4)
## How this works

Coins are **self-contained, atomic goals** that provide evidence towards one or more apprenticeship Duties. Each coin stands on its own — there are no sub-milestones to work through, and no coin depends on a specific scheduled event (training day, cohort activity, etc.). If a coin references a technique or tool, any suitable real example from your own project work counts as evidence.

Coins are a menu for variety and stretch, not a checklist for EPA sign-off. Full KSB coverage is expected to emerge from the sum of your day-to-day work and reflection over the apprenticeship — most of which will never become a coin. We map coins to Duties/KSBs so you can see what kind of skill each one builds, and so your mentors can point you at a specific coin if they spot a KSB that isn't otherwise showing up in your evidence. That's the tags' only job.

Coins are grouped into **10 themes**, each mapping to a cluster of related Duties. You are not expected to complete every coin. As a guideline, aim for **at least 1-2 coins per theme** over the course of your apprenticeship, choosing the ones most relevant to your project and interests. Coins marked **(advanced)** assume you've already built some familiarity with the theme (via a base coin in that theme, or equivalent experience) — they're optional deeper dives, not a requirement.

Each coin lists:
- **Duties** it evidences (D1-D13, per the apprenticeship standard)
- **KSBs** it evidences (Knowledge, Skill, and Behaviour references)
- **Evidence** — what you need to produce or demonstrate to claim the coin

## Evidence format

Every coin's primary evidence is an **artefact** — a pipeline, a diagram, a test suite, a tuned alert, a retro output, a mentee's written reflection. This should stand on its own; you don't need a witness sign-off to claim most coins.

Separately, your apprenticeship also requires **3 formal Employer Witness Testimonies** across the whole programme, each completed by a senior delivery stakeholder and covering two dated, real examples of you demonstrating competency.

These 3 testimonies aren't tied to individual coins — each one should map holistically across whichever coins/duties the observed examples naturally cover, per the standard's own guidance ("one example could cover criteria from multiple modules across the standard"). In practice:
- Most coins only ever need the artefact — no witness required.
- Aim to line up your 3 testimonies with moments that naturally span several coins at once, especially ones evidencing interpersonal/cultural duties (D2, D3, D4, D13), where a stakeholder's outside perspective adds something an artefact alone can't.
- Space the 3 testimonies out across the apprenticeship (e.g. roughly one every 2-3 months, once you've finished bootcamp and joined a delivery) rather than leaving them all to the end — talk to your point of contact/people manager about timing.

See `witness-testimony-template.md` in this directory for the testimony format itself.

---

## Theme 1: Code & Test Craft
*Duties: D1*

### Giraffe Badge
**Duties:** D1 · **KSBs:** K14, S14, S17

Earn the TDD Giraffe Badge by TDD-ing a kata or small feature: write failing tests before production code, watch each one fail for the right reason before making it pass, and write only the minimum code needed to pass it. Refactor both your tests and your production code as you go, structure tests around Arrange-Act-Assert(-Teardown), and name them from the user's perspective. Be able to explain triangulation — what goes wrong without it — and show a moment where you used it to force out more general code.

### Test-Driven
**Duties:** D1 · **KSBs:** K14, S14, S17

Write integration and/or end-to-end tests for a real feature, deliberately deciding where they add confidence your unit tests can't, rather than duplicating protection those tests already give you more cheaply. Explain the trade-offs you made across the test pyramid — confidence vs speed vs reliability — for this specific feature.

### Second Tongue
**Duties:** D1 · **KSBs:** K7, S17

Write and ship working code in a second general-purpose programming language, different from the one you use day-to-day. Explain what transferred from your primary language, what didn't, and one thing the new language does differently that changed how you approached a problem.

### Infrastructure Fluent
**Duties:** D1, D7 · **KSBs:** K7, S18

Write infrastructure-as-code in a domain-specific language (e.g. Terraform) to provision real infrastructure for a genuine project need. The code should be reviewed, version-controlled, and actually applied to create or modify infrastructure.

### Find the Blind Spots
**Duties:** D1 · **KSBs:** K14, S14

Find a part of the codebase that's under-tested and carries real risk — complex logic, a history of bugs, or a critical user path. Add tests that directly address that risk, and explain how you decided what was worth testing and what wasn't, rather than chasing a coverage percentage.

### Refactor Under Cover *(advanced)*
**Duties:** D1 · **KSBs:** K14, S14

Identify a piece of legacy or poorly-structured code. Incrementally refactor it via a series of small, behaviour-preserving changes, backed by a test suite that supports safe refactoring. Document the sequence of changes and how the tests gave you confidence at each step.

---

## Theme 2: Collaboration & Mentoring
*Duties: D2, D3*

### Pair Programmer
**Duties:** D3 · **KSBs:** K20, S13

Complete a structured run of pair or mob programming sessions (e.g. across a sprint or a specific piece of work). Reflect on which pairing technique(s) you used (driver/navigator, ping-pong, strong-style, mobbing) and when/why, plus what you personally learned and taught.

### Teach to Learn
**Duties:** D2 · **KSBs:** K19, S1, S4

Deliver a knowledge-sharing session (talk, workshop, lunch-and-learn, or written guide) to your team or a wider community of practice on a technical topic. Show how you tailored the format/channel to your audience.

### Grow a Colleague *(advanced)*
**Duties:** D2 · **KSBs:** S4, S16, B1

Provide sustained support to a specific team member's development over multiple weeks (e.g. regular structured pairing, mentoring check-ins, code review guidance). Gather their perspective on what changed for them as a result.

### Bring in the Non-Coder *(advanced)*
**Duties:** D2, D3 · **KSBs:** K20, S4, S13

Introduce someone without a coding background (e.g. a non-technical colleague) to pairing and/or TDD on a real or representative task. Reflect on how you adapted the practice to be accessible to them, and what they took away.

---

## Theme 3: Ways of Working
*Duties: D4, D13*

### Own It
**Duties:** D13 · **KSBs:** S11, B3

Take end-to-end ownership of a change you deployed to production — including responding to a real issue, alert, or incident related to it after release. Document what happened, how you diagnosed it, and what you'd do differently next time.

### Blameless Retro
**Duties:** D4 · **KSBs:** K23, B4

Facilitate, or take a visibly active role in, a blameless retrospective or post-incident review. Show how the process avoided blame, focused on systemic causes, and produced concrete improvement actions.

### Agile in Practice
**Duties:** D4 · **KSBs:** K9, K10, S3, S8

Demonstrate adapting your team's way of working in direct response to changing user needs (e.g. re-prioritising a backlog, changing a ceremony). Show the before state, the trigger for change, and the after state, with reasoning tied to user impact.

### Solve It Systematically
**Duties:** D4 · **KSBs:** K6

Apply a structured problem-solving technique (affinity mapping, impact mapping, Plan-Do-Check-Act, 5 Whys, etc.) to a real team problem. Document the process you followed and the outcome/decision it led to.

---

## Theme 4: CI & Version Control
*Duties: D5*

### Branch Smart
**Duties:** D5 · **KSBs:** K2, S20

Demonstrate effective use of a branching strategy (trunk-based development, short-lived feature branches, or feature toggling/branching by abstraction) that keeps merges frequent and low-risk. Explain the strategy chosen and why it suits your team's context.

### Green Pipeline
**Duties:** D5 · **KSBs:** K1, S15

Build or operate a CI pipeline that automatically runs the test suite and produces a build artefact on every commit/PR. Show an example of a failing build being caught before merge, explain what went wrong and how you resolved the issue.

### Everything In Its Right Place *(advanced)*
**Duties:** D5 · **KSBs:** K2

Bring a previously untracked or inconsistently-tracked category of project artefact (config, infra definitions, docs, pipeline definitions) under version control, and get your team to actually adopt a documented workflow for it — not just propose one. Show evidence that people other than you are using it.

---

## Theme 5: Release & Deployment Automation
*Duties: D6, D12*

### Ship It Automatically
**Duties:** D6 · **KSBs:** K15, K17, S15

Implement release/deployment orchestration (using an API where relevant) as part of a continuous delivery or continuous deployment pipeline, enabling the team to ship a real change to users through it.

### Kill the Toil
**Duties:** D12 · **KSBs:** K13, S12

Identify a manual task that is repeated regularly and automate it (via scripting or an API). Quantify or clearly describe the time/effort saved, and weigh this against the cost of building the automation.

### Zero Downtime
**Duties:** D6 · **KSBs:** K15, S15

Implement a deployment strategy (blue/green, canary, or rolling) that allows your team to release a real change without user-facing downtime. Show what would have happened under the old approach vs the new one.

### Pipeline, Your Way *(advanced)*
**Duties:** D5, D6 · **KSBs:** K15, K24, S15

Rebuild an existing deployment pipeline's capability using an alternate CI/CD tool or stack to the one your team normally uses. Compare the tradeoffs (SaaS vs bespoke vs enterprise tooling, ease of use, cost, lock-in) between the two.

### Ephemeral Test Environments *(advanced)*
**Duties:** D5, D6 · **KSBs:** K1, K15, S15

Automate the creation and teardown of a temporary test/preview environment, triggered automatically by opening a pull request and torn down automatically when it's closed or merged. Show a real PR triggering the environment and its automatic teardown.

---

## Theme 6: Cloud Infrastructure & IaC
*Duties: D7*

### Go Immutable
**Duties:** D7 · **KSBs:** K8, S5

Deploy infrastructure using an immutable pattern (rebuild rather than in-place patch) — e.g. a new AMI or container image per deploy. Explain how this supports safe, continual refreshing (OS updates, container updates, security patching).

### Right-Size the Cloud
**Duties:** D7 · **KSBs:** K4, K21

Provision or refactor a piece of infrastructure with explicit cost/performance tradeoffs considered (instance sizing, autoscaling policy, storage tier). Show the reasoning and, where possible, the measured before/after impact.

### Try the New Thing *(advanced)*
**Duties:** D7 · **KSBs:** K21, K24

Evaluate and adopt an infrastructure technology new to your project or team (e.g. serverless, containers) for a genuinely suitable use case. Justify the choice against the alternative(s) you considered.

---

## Theme 7: Architecture & Design
*Duties: D8*

### Whiteboard It
**Duties:** D8 · **KSBs:** K21, S21

Use a lightweight modelling technique (whiteboarding, sketching, C4 diagrams, etc.) with collaborators to reach consensus on an architecture decision. Capture the artefact produced and the decision it led to.

### Design for the User
**Duties:** D8 · **KSBs:** K10, K21

Propose and justify an architecture or design change driven primarily by user experience, scalability, security, high availability, or performance considerations. Show the user need behind it, not just the technical motivation.

### Data Decisions
**Duties:** D8 · **KSBs:** K12

Choose and justify a persistence/storage technology for a specific functional or non-functional need (e.g. read-heavy vs write-heavy workload, recovery/backup requirements, monolith vs microservice context).

### A Shade Beyond Engineering
**Duties:** D8 · **KSBs:** K10, K18, S2

Shadow and support a non-engineer (e.g. user researcher, designer, business analyst) with a piece of work. Document what associate-level responsibilities look like for the role, how their role contributes to decisions, and one specific way their perspective affected a decision you were involved in.

### Built to Bend *(advanced)*
**Duties:** D8 · **KSBs:** K21, S22

Redesign or refactor a component specifically to improve its scalability or high availability. Show the before/after architecture and the tradeoffs involved in the change.

---

## Theme 8: Security
*Duties: D9*

### Threat Model It
**Duties:** D9 · **KSBs:** K5, S9, S10

Perform a threat model and security audit on part of your project. Identify risks, prioritise them by likelihood vs impact, and recommend solutions.

### Shift Security Left
**Duties:** D9 · **KSBs:** K5, S9

Integrate an automated security or compliance tool (e.g. dependency checking, SAST/DAST vulnerability scanning, or infrastructure compliance/drift scanning) into a CI/CD pipeline so it runs on every relevant change, reducing reliance on manual, late-stage review.

### Lock the Data Down
**Duties:** D9 · **KSBs:** K16

Apply appropriate data security controls to a part of your project — e.g. encryption in transit, encryption at rest, or access control lists — and justify the choices made relative to the sensitivity of the data involved.

### Handle Data Responsibly
**Duties:** D9 · **KSBs:** K3

Look at a place in your project where data is collected, processed, or used to drive automated decisions (including via AI/ML). Check it against relevant data protection legislation (e.g. UK GDPR) and think through the wider ethical and societal implications of how that data is being used. Document what you found, and any change you recommended or made as a result.

### Close the Loop *(advanced)*
**Duties:** D9 · **KSBs:** K5, S10

Implement a security fix or improvement that was recommended by an audit or threat modelling session (yours or someone else's) and demonstrate its impact — ideally by showing the vulnerability/risk before and the mitigation after.

---

## Theme 9: Observability
*Duties: D10*

### Follow the Trail
**Duties:** D10 · **KSBs:** S7, S11, S19

Use logs and/or metrics to diagnose and resolve a real issue in a distributed or stateful system, navigating across the end-to-end service to locate the root cause.

### Compare a Tool
**Duties:** D10 · **KSBs:** K11, K24

Evaluate two monitoring/observability tools against your project's actual needs (cost, integration effort, features) and recommend one with clear reasoning.

### See Inside It
**Duties:** D10 · **KSBs:** K11, S6

Implement monitoring (metrics and/or logs) for a system or component that previously had little or no coverage. Install/configure the tooling yourself and show what became visible that wasn't before.

### Alert, Don't Annoy *(advanced)*
**Duties:** D10 · **KSBs:** K11, S19

Tune the alert thresholds/configuration on an existing monitor — ideally aligned to a Service Level Objective (SLO) for the service — so that alerts remain actionable and noise is reduced. Show the before state (e.g. noisy/ignored alerts) and after state (fewer, more meaningful alerts).

---

## Theme 10: Continuous Learning
*Duties: D11*

### Cert It
**Duties:** D11 · **KSBs:** K25

Earn an entry-level cloud certification — AWS Certified Cloud Practitioner, Microsoft Azure Fundamentals (AZ-900), or a Databricks Fundamentals/Associate-level accreditation.

### Green Software Practitioner
**Duties:** D11 · **KSBs:** K22, S16

Complete the Green Software Foundation's [Green Software Practitioner](https://movement.greensoftware.foundation/spaces/19525645/page) course, and identify one specific way its principles could reduce the environmental impact of your project's software or infrastructure.

### Horizon Scan
**Duties:** D11 · **KSBs:** K22, S16, B2

Keep a running log of external learning over a set period (e.g. a term of the apprenticeship) — articles, publications, talks, or active participation in a professional community (meetup, forum, conference). Reflect on how at least one item influenced a decision or approach in your actual work.

### Teach Your Cert *(advanced)*
**Duties:** D11, D2 · **KSBs:** S4, S16

Create a short, accessible guide ("101") to a topic you've learned or certified in, and teach it to a colleague. Show the guide and evidence the teaching happened (feedback, follow-up questions, etc.).

---

## Duty coverage map

| Duty | Theme(s) |
|---|---|
| D1 | Code & Test Craft |
| D2 | Collaboration & Mentoring, Continuous Learning |
| D3 | Collaboration & Mentoring |
| D4 | Ways of Working |
| D5 | CI & Version Control, Release & Deployment Automation |
| D6 | Release & Deployment Automation |
| D7 | Code & Test Craft, Cloud Infrastructure & IaC, Release & Deployment Automation |
| D8 | Architecture & Design |
| D9 | Security |
| D10 | Observability |
| D11 | Continuous Learning |
| D12 | Release & Deployment Automation |
| D13 | Ways of Working |
