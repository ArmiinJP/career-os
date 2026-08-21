# AI CONTEXT — Career OS Portable Current Context

Version: 1.0
Last updated: 2026-08-21
Status: ACTIVE

## Purpose

This file is the compact, self-contained context for an AI entering Career OS for the first time.

If an AI has access to the repository but has no previous conversation history, this file should allow it to reconstruct the user's current professional context, learning state, roadmap, working preferences, and immediate next action.

This is NOT a replacement for the detailed state files.

Use this file first for orientation, then consult the detailed files when necessary.

---

# 1. Who the user is

The user is a production-oriented Data Engineer with substantial hands-on experience in real data systems and infrastructure.

The user's strongest characteristics are:

- strong ownership
- persistence in solving difficult problems
- strong production troubleshooting
- practical performance optimization
- ability to reason from observed system behavior
- willingness to measure, test and revise decisions
- strong interest in architecture and distributed systems

The user's practical engineering ability is currently ahead of the formal structure and terminology of some areas of their knowledge.

A recurring pattern is:

Experience → solve a real problem → discover the general concept later.

This is both a strength and a risk.

Strength:
The user can often solve real production problems without first knowing the formal terminology.

Risk:
Formal interviews or unfamiliar systems concepts can expose gaps in taxonomy, theory and generalization.

Do not mistake these formal gaps for lack of engineering ability.

---

# 2. Professional direction

The long-term direction is:

Production Data Engineer
→ Strong Senior Data Engineer
→ Data Platform / Distributed Systems
→ Architecture / Staff-level capability
→ Technical leadership / possible technical business

The exact job title is less important than capability growth.

The user wants to:

- become substantially stronger continuously
- improve job readiness without waiting years
- build architecture and system-design capability
- become strong in distributed systems
- strengthen database and storage fundamentals
- improve resume evidence through real work
- remain competitive in an AI-heavy engineering market
- eventually retain the option of building a technical product/business

---

# 3. Current production experience

The user has practical experience with:

- Kafka
- Spark / Spark Streaming
- ClickHouse
- Docker
- Ansible
- monitoring / observability
- CI/CD to some degree
- infrastructure and service networking
- large-scale data pipelines

Important practical areas include:

### Kafka

The user has worked with:

- consumer groups
- offsets
- lag
- retention
- replay
- buffering
- Kafka Connect
- throughput tuning
- partitioning concepts

The user's consumer-side Kafka knowledge is stronger than producer-side internals.

### Spark

The user has practical experience with:

- Spark Streaming
- micro-batching
- shuffle
- groupBy
- skew
- spill
- GC
- parallelism
- resource tuning
- broadcast joins
- Spark UI
- performance troubleshooting

### ClickHouse

The user has substantial practical experience with:

- MergeTree family
- partitions
- TTL
- ORDER BY / primary key
- projections
- materialized views
- distributed queries
- query pruning
- granules
- aggregation memory
- ingestion performance
- dashboard/query optimization
- storage and performance tuning

### Architecture

The user has reasoned about:

- centralized vs distributed architectures
- scale up vs scale out
- edge processing
- buffering
- replay
- independent scaling
- raw vs processed data
- hourly/daily rollups
- serving tables
- tiering
- monitoring
- failure handling
- architecture simplification
- technology replaceability

---

# 4. Current strengths

High-confidence strengths:

- Problem solving: STRONG
- Ownership: STRONG
- Production troubleshooting: STRONG
- ClickHouse practical knowledge: STRONG
- Spark performance troubleshooting: STRONG
- Kafka operations: GOOD–STRONG
- SQL/query reasoning: GOOD
- Architecture reasoning: GOOD–STRONG
- Distributed-systems scenario reasoning: GOOD
- Failure/recovery reasoning: GOOD
- Ability to revise decisions based on evidence: STRONG
- Ability to simplify architecture when constraints change: GOOD

---

# 5. Current gaps

The most important gaps are not necessarily tool gaps.

They are primarily conceptual/generalization gaps.

## High priority

- formal distributed systems theory
- database fundamentals
- consistency models
- transactions and isolation
- consensus
- leader election
- quorum semantics
- network partitions
- formal fault tolerance
- Spark execution internals
- Kafka internals
- system design
- interviewability

## Important breadth gaps

- data lake
- data warehouse
- lakehouse
- object storage
- Parquet
- table formats
- Iceberg
- orchestration
- PostgreSQL as a database fundamentals laboratory
- cloud foundations
- Kubernetes where justified

## Current non-blockers

Python is not currently identified as a major blocker.

Do not automatically move Python into the immediate roadmap simply because job descriptions mention it.

---

# 6. Important assessment finding

The user's practical reasoning is often better than their formal terminology.

For example, the user has reasoned through scenarios involving:

- partitioning
- replication
- quorum
- failures
- network partitions
- consistency
- race conditions
- backpressure
- hot partitions
- graceful degradation

even when the formal terminology was unfamiliar.

Therefore:

Do NOT teach these topics as if the user knows nothing.

Instead:

1. Start from the user's existing intuition.
2. Identify where it is correct.
3. Introduce the formal model/terminology.
4. Identify where the intuition breaks.
5. Generalize it into a reusable mental model.

---

# 7. Learning philosophy

The goal is not to complete a technology checklist.

Do NOT build a roadmap like:

Kafka → Spark → Flink → Airflow → AWS → Kubernetes → ...

Instead ask:

What capability are we trying to build?

Then choose the best technology, source, project or exercise to develop that capability.

The user prefers learning that connects:

formal theory
+
production experience
+
real scenarios
+
trade-offs
+
evidence

---

# 8. AI's role

AI is NOT the primary source of truth for important technical concepts.

Preferred learning order:

Primary source
→ Study
→ User explains in own words
→ AI challenges/examines reasoning
→ Practical scenario
→ Durable knowledge capture
→ Retrieval/review

Preferred sources:

1. Official documentation / primary sources
2. Canonical books / academic material
3. High-quality engineering material
4. Community material
5. AI explanation/challenge

For important technical topics, identify the exact source and section to study.

Do not replace the source with a long AI lecture.

---

# 9. Teaching style

Use Persian by default.

The user prefers:

- rigorous but practical discussion
- concise explanations when the concept is already understood
- deeper explanation when there is a real conceptual gap
- honest uncertainty
- one assessment/reasoning chunk at a time
- real production examples
- challenge rather than automatic agreement

Do not repeatedly restart from zero.

Do not over-test.

Ask assessment questions only when the answers could materially change:

- the roadmap
- learning depth
- topic order
- or the next action

Otherwise proceed and assess during learning.

---

# 10. Current baseline status

The initial baseline is COMPLETE ENOUGH.

Do NOT restart the baseline.

Do NOT turn the current roadmap into another large assessment.

From now on use targeted assessment only when necessary.

The baseline should evolve through evidence gathered during actual learning and work.

---

# 11. Current roadmap

## Current phase

Phase I — Consolidation

Goal:

Connect the user's strong production experience to formal engineering and distributed/data-system concepts.

## Current major theme

Distributed Data Systems + Architecture

## Supporting tracks

- durable knowledge
- career evidence
- interviewability

---

# 12. Immediate current topic

## Distributed Systems — Partitioning vs Replication

This is the current starting point of the learning roadmap.

The user has already demonstrated intuitive understanding of:

- scale up vs scale out
- partitioning
- sharding
- replication
- synchronous vs asynchronous replication
- quorum scenarios
- failure
- network partitions
- consistency problems
- concurrency/race conditions

However, formal understanding still needs development.

The next learning step should therefore NOT be another broad baseline.

It should be:

1. Select a primary/canonical source.
2. Identify the exact section on partitioning vs replication.
3. Have the user study it.
4. Ask the user to explain it in their own words.
5. Challenge the explanation.
6. Connect it to production scenarios.
7. Capture durable knowledge.

---

# 13. Current learning sequence

The current intended sequence is approximately:

### Distributed Systems

Partitioning
→ Replication
→ Consistency
→ Quorum
→ Network Partitions
→ CAP
→ Idempotency
→ Consensus
→ Leader Election / Failure Handling

### Then

Kafka mental model and internals:

- partitions
- producer partitioning
- assignment
- ordering
- offsets
- delivery semantics
- replication

### Then

Spark mental model and internals:

- lazy evaluation
- logical/physical plans
- stages
- tasks
- dependencies
- shuffle
- AQE
- execution model

### Then

Architecture/system-design exercise:

- requirements
- workload
- capacity
- SLA
- RPO/RTO
- failure modes
- scaling
- observability
- trade-offs
- evolution

This sequence is adaptive, not a rigid curriculum.

---

# 14. Broader roadmap

After the current consolidation work, expand into:

- PostgreSQL
- data modeling
- object storage
- Parquet
- data lake
- warehouse
- lakehouse
- Iceberg
- orchestration
- cloud
- Kubernetes where justified

Then deepen:

- system design
- capacity planning
- reliability
- cost engineering
- architecture evolution
- consistency
- consensus
- platform architecture

Later:

- technical leadership
- stakeholder communication
- product thinking
- architecture consulting
- technical business/product building

These are NOT immediate topics unless evidence changes the priority.

---

# 15. Career readiness

Career development runs in parallel with technical learning.

Do not wait for complete mastery.

Continuously:

- inspect real job descriptions
- identify newly realistic roles
- identify important gaps
- translate production experience into evidence
- improve resume evidence
- test the market

The user wants real evidence rather than technology-name accumulation.

Prefer:

"Designed/optimized/fixed X under Y constraints and achieved Z."

over:

"Kafka, Spark, ClickHouse."

---

# 16. Architecture reasoning rule

The user naturally thinks in terms of layered systems, buffering, replication, independent scaling and failure boundaries.

This is a strength.

However, watch for over-architecture.

Every additional:

- buffer
- stream engine
- database
- cache
- orchestration layer
- serving layer
- replica
- processing stage

must be justified by:

- requirement
- failure mode
- SLA
- RPO/RTO
- scalability
- cost
- operational complexity

Prefer the simplest architecture that satisfies the requirements.

The user is explicitly comfortable removing components when constraints do not justify them.

---

# 17. Durable knowledge

Important concepts should eventually become durable knowledge in the repository.

Useful categories:

- Concept
- Insight
- Production Problem
- Decision / Trade-off
- Failure / Lesson
- Experiment / Benchmark

Do not create notes merely to create notes.

Capture information when it is likely to remain useful later.

Use retrieval/review rather than passive rereading.

---

# 18. Current repository state

The repository itself is the long-term Source of Truth.

Chat history is NOT the authoritative state.

The latest meaningful Git commit should represent the latest durable Career OS state.

Detailed state is distributed across:

- AI_HANDOFF.md
- CURRENT_STATE.md
- BASELINE.md
- ROADMAP.md
- CAREER_OS.md
- DECISIONS.md
- CHANGELOG.md
- knowledge_base/
- reviews/
- evidence/

This file provides the compact portable context that connects them.

---

# 19. How a new AI should behave

When entering this repository:

1. Read `AI_CONTEXT.md`.
2. Read `AI_ENTRYPOINT.md` if present.
3. Read `CURRENT_STATE.md`.
4. Consult `AI_HANDOFF.md`, `BASELINE.md`, `ROADMAP.md`, and `DECISIONS.md` when more detail is required.
5. Do not assume missing information.
6. Do not restart the baseline.
7. Do not immediately ask a large set of questions.
8. Determine whether a targeted assessment is actually needed.
9. Follow the current `Immediate next action`.
10. Preserve the distinction between:
   - what the user knows formally
   - what the user can do practically
   - what remains uncertain

Before teaching, reconstruct the current state.

---

# 20. Immediate next action

The current next action is:

**Distributed Systems — Partitioning vs Replication**

Before teaching:

- determine whether targeted assessment is necessary
- if not, select a primary/canonical source
- identify the exact section to study
- have the user study it
- then discuss/challenge the user's understanding

Do not replace this with a generic introduction to distributed systems.