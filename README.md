# Career OS

Personal Career Operating System for a long-term Data Engineering career.

This repository is the **single source of truth** for the current state, history, roadmap, knowledge, decisions, and career evidence of this journey.

The goal is not to learn every technology.

The goal is to continuously become a stronger Data Engineer, Systems Engineer, and Architect while improving job readiness, resume evidence, and long-term career capital.

---

## Source of Truth

The canonical state of Career OS is the **latest commit on the `main` branch**.

Previous AI conversations are not required to continue this journey.

Git history preserves how the current state was reached.

---

## Start Here

### For a new AI / new conversation

Read these files in order:

1. [`AI_ENTRYPOINT.md`](./AI_ENTRYPOINT.md)
2. [`START_PROMPT.md`](./START_PROMPT.md)
3. [`CURRENT_STATE.md`](./CURRENT_STATE.md)
4. [`ROADMAP.md`](./ROADMAP.md)
5. [`BASELINE.md`](./BASELINE.md)
6. [`AI_HANDOFF.md`](./AI_HANDOFF.md)

The first two files explain **how to work with this repository**.

The remaining files explain **where the person is, where they are going, and what has already been learned**.

---

## Repository Structure

```text
career-os/
│
├── README.md
│
├── AI_ENTRYPOINT.md
├── START_PROMPT.md
├── CURRENT_STATE.md
├── ROADMAP.md
├── BASELINE.md
├── AI_HANDOFF.md
│
├── KNOWLEDGE_BASE/
│   ├── concepts/
│   ├── insights/
│   ├── problems/
│   ├── decisions/
│   └── experiments/
│
├── EVIDENCE/
│   ├── projects/
│   ├── benchmarks/
│   └── resume/
│
├── DECISIONS/
│
├── REVIEWS/
│
├── SNAPSHOTS/
│
└── CHANGELOG.md
```

Some directories may remain empty until they become useful.

Do not add structure merely for the sake of structure.

---

## File Responsibilities

| File               | Purpose                                                                      |
| ------------------ | ---------------------------------------------------------------------------- |
| `AI_ENTRYPOINT.md` | Rules and navigation for any AI entering the repository                      |
| `START_PROMPT.md`  | Reusable prompt for starting a new AI conversation                           |
| `CURRENT_STATE.md` | The person's current position, active focus, progress, gaps, and next action |
| `ROADMAP.md`       | Long-term direction and current priorities                                   |
| `BASELINE.md`      | Initial and later assessments of skills and capabilities                     |
| `AI_HANDOFF.md`    | Stable background about the person, goals, preferences, and working method   |
| `KNOWLEDGE_BASE/`  | Durable knowledge, insights, problems, decisions, and experiments            |
| `EVIDENCE/`        | Concrete evidence of professional growth and resume material                 |
| `DECISIONS/`       | Important roadmap or architecture decisions and their rationale              |
| `REVIEWS/`         | Periodic career and learning reviews                                         |
| `SNAPSHOTS/`       | Historical point-in-time versions of Career OS                               |
| `CHANGELOG.md`     | Important changes to Career OS itself                                        |

---

## Operating Principles

### 1. Progress over completion

The goal is continuous improvement, not finishing a giant curriculum.

### 2. Fundamentals before tool collecting

Technologies are learned as implementations of broader engineering concepts.

Examples:

* Kafka → distributed streaming and messaging
* Spark → distributed computation
* ClickHouse → analytical storage and query execution
* PostgreSQL → database fundamentals and OLTP
* Iceberg → lakehouse/table-format concepts
* Airflow → orchestration

### 3. Experience and knowledge are different

A person may have strong production experience while still having gaps in formal concepts.

Career OS tracks these separately.

### 4. Evidence matters

Learning should gradually produce:

* working systems
* experiments
* benchmarks
* architecture decisions
* problem-solving records
* portfolio material
* resume evidence

### 5. AI is an amplifier, not the source of truth

Primary sources are preferred:

* official documentation
* books
* academic material
* papers
* engineering case studies

AI is used for:

* explanation
* questioning
* review
* challenge
* brainstorming
* debugging
* practice
* synthesis

Important claims should be verified against appropriate primary sources.

### 6. Avoid unnecessary complexity

New tools, layers, frameworks, or technologies should be introduced only when they solve a real requirement or close an important skill gap.

### 7. The roadmap is adaptive

The roadmap may change when new evidence shows that:

* a skill is weaker than expected
* a skill is already strong enough
* market requirements changed
* a higher-priority gap was discovered
* a different specialization has become more valuable

### 8. Previous AI conversations are optional

Career OS must remain useful even when the original AI conversation is unavailable.

---

## Current Position

For the current position and immediate next action, see:

[`CURRENT_STATE.md`](./CURRENT_STATE.md)

Do not infer the current position from README history when `CURRENT_STATE.md` is available.

---

## Long-Term Direction

The current long-term direction is broadly:

```text
Production Data Engineer
        ↓
Senior / Advanced Data Engineer
        ↓
Distributed Data Systems / Platform Engineer
        ↓
Data Architect / Systems Architect
        ↓
Technical Leadership + Product / Business Building
```

This is a direction, not a rigid sequence.

The actual path should evolve according to evidence, capability, market demand, and personal goals.

---

## How Progress Is Evaluated

Career OS tracks progress across multiple dimensions rather than a single skill score.

Examples:

* technical depth
* breadth
* architecture ability
* problem solving
* production experience
* system design
* interview readiness
* resume evidence
* job readiness
* ability to learn independently
* effective use of AI

A person is considered to be progressing when they can increasingly:

1. understand deeper concepts,
2. solve harder problems,
3. design better systems,
4. explain and defend trade-offs,
5. produce stronger evidence,
6. target stronger roles.

---

## Change Policy

Do not treat every learning session as a roadmap change.

A temporary activity should not automatically change:

* skill level
* specialization
* roadmap priority
* career direction

Important changes should be supported by evidence and recorded appropriately.

The latest commit should leave the repository in a **self-consistent and understandable state**.

---

## Portability

Career OS is intentionally designed to be portable across:

* ChatGPT
* Claude
* Gemini
* local/open-source models
* human mentors
* future AI systems

A new AI should be able to reconstruct the current situation from the repository without access to previous conversations.

Start with:

[`AI_ENTRYPOINT.md`](./AI_ENTRYPOINT.md)

and:

[`START_PROMPT.md`](./START_PROMPT.md)
