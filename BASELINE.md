# BASELINE ASSESSMENT — 2026-08-21

## Method

Adaptive assessment. Questions were asked one chunk at a time. The user answered from memory/experience without using external lookup for the baseline.

## Main finding

The user's practical engineering intuition and problem-solving ability are stronger than the formal structure/terminology of parts of their knowledge.

Recurring pattern:
Experience -> practical solution -> later discovers missing concept.

This creates:
- strong operational ability
- useful engineering intuition
- risk of tool/experience bias
- interview anxiety when formal concepts are probed
- fear that a known solution may not be globally optimal

## Detailed findings

### Problem solving / ownership — STRONG
Evidence:
- repeatedly owns problems without a local specialist
- searches documentation and uses AI until a solution is understood
- measures after implementation and revises if performance is not good enough
- willing to redesign after evidence contradicts initial assumptions

### Architecture — GOOD to STRONG
Evidence:
- thinks in layers and failure boundaries
- considers independent scaling
- considers replay, buffering, monitoring, retention and serving layers
- can simplify architecture when requirements are relaxed
- prefers replaceability and avoiding hard coupling to one tool feature

Risk:
- may add components too quickly; must justify each component with requirements and trade-offs.

### Distributed Systems — GOOD REASONING / WEAKER FORMAL THEORY
Understands intuitively:
- scale up/out
- partitioning/sharding
- replication
- failure
- buffering/backpressure
- skew/hot partitions
- concurrency/race conditions
- sync vs async replication
- quorum scenarios
- network partition / split-brain-like behavior
- graceful degradation

Needs formal depth in:
- CAP
- consistency models
- quorum semantics
- consensus
- leader election
- fencing/epochs
- formal fault-tolerance patterns

### Databases — MEDIUM to GOOD
Strong practical understanding around ClickHouse and query execution.
Need stronger general mental models for:
- transactions
- isolation levels
- MVCC
- indexes across engines
- data modeling
- warehouse/lakehouse taxonomy

### OLTP / OLAP — GOOD
Good practical mental model of transactional vs analytical workloads, ACID importance, large scans/aggregation, and not placing heavy analytics on transactional systems.

### Data Lake / Warehouse / Lakehouse — CLEAR GAP
User explicitly said practical exposure is low.
Current mental model mixes:
- storage tiering
- object storage
- warehouse
- lakehouse
- data age/hot/cold access

Need a clean model of:
Object Storage -> File Format -> Table Format -> Query Engine -> Lake/Lakehouse/Warehouse -> Serving.

### SQL — GOOD PRACTICAL REASONING
Strengths:
- query cost decomposition
- filter/pruning reasoning
- aggregation/cardinality
- order/limit reasoning
- parallelism intuition
- multiple solution patterns

Needs precision around:
- optimizer behavior
- database-specific index semantics
- top-k and execution strategies
- broader SQL interview competency model

### ClickHouse — STRONG
Evidence:
- partitions / TTL
- ORDER BY / primary key
- projections
- reverse domain
- IP representations
- granules/data skipping
- aggregation memory/performance
- serving/query design
- production tuning

### Spark — STRONG PRACTICAL / MEDIUM INTERNALS
Strong:
- spill
- GC
- shuffle
- skew
- group-by cardinality
- maxOffsetsPerTrigger
- resource tuning
- broadcast join risk
- Spark UI troubleshooting

Needs formal depth:
- lazy evaluation details
- logical vs physical plan
- stage/task model
- narrow/wide dependencies
- shuffle architecture
- AQE and execution internals

### Kafka — GOOD to STRONG OPERATIONS / MEDIUM INTERNALS
Strong:
- consumer groups
- offsets
- lag
- retention
- replay
- auto.offset.reset concepts
- at-least-once/at-most-once reasoning
- buffering under downstream slowness

Needs precision in:
- partition assignment
- producer partitioning
- ordering guarantees
- hot partition strategies
- quorum / replication relationship
- exactly-once boundaries and idempotent sinks

### Python — NO CURRENT MAJOR BLOCKER FOUND
One initial question showed correct intuition around list materialization vs streaming/generators and resource behavior. No evidence yet that Python should displace higher priorities.

### Career / Interviews — IMPORTANT GAP
User is confident in performing once hired, but less confident in:
- what "advanced SQL/Python" means in job descriptions
- how to map real experience to interview evaluation
- how to explain experience and architecture decisions under time pressure
- how to distinguish mandatory competency from optional tool exposure

This requires a dedicated interviewability track.

## Assessment philosophy going forward

Do not over-test. At the start of a new roadmap topic, use 1–5 targeted questions only if they can change the plan. Otherwise start learning and assess during the topic.
