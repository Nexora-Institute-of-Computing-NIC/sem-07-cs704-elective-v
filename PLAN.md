# CS704 — Elective V: Advanced System Design — PLAN

**Semester:** 7 · **Credits:** 3 · **Level:** Advanced
**Theory:** 45 hrs · **Lab:** 15 hrs · **Tools:** Whiteboard, Excalidraw, diagrams.net, load-testing tools

## Syllabus

### Unit 1 — Design Fundamentals (9 lectures)
1. What system design is — beyond coding
2. Requirements — functional and non-functional
3. Back-of-the-envelope estimation — QPS, storage, bandwidth
4. Latency numbers every engineer should know
5. Availability — nines and what they mean
6. Capacity planning
7. Trade-off thinking — no free lunch
8. Reading a system design problem — scope first
9. Communicating a design — the four-section framework

### Unit 2 — Building Blocks (9 lectures)
1. Load balancers — L4 vs L7
2. Caching — client, CDN, application, database
3. Databases — SQL vs NoSQL, choosing
4. Replication — leader-follower, multi-leader
5. Sharding — hash, range, directory
6. Message queues — Kafka, SQS, RabbitMQ
7. Search — inverted index, Elasticsearch
8. Object storage — S3-style design
9. CDNs — edge caching and invalidation

### Unit 3 — Classic Designs (9 lectures)
1. URL shortener — a first full design
2. Rate limiter — token bucket, leaky bucket, distributed
3. Key-value store — from memcached to Dynamo
4. Web crawler — politeness, deduplication, scheduling
5. Notification system — push, email, in-app
6. News feed — fan-out on write vs read
7. Chat system — WebSocket, delivery guarantees, presence
8. Search autocomplete — trie, ranking, latency budget
9. Ride-sharing — geospatial indexing, matching

### Unit 4 — Reliability and Operations (9 lectures)
1. SLOs and error budgets
2. Circuit breakers, bulkheads, timeouts
3. Retries with exponential backoff and jitter
4. Idempotency and exactly-once semantics
5. Distributed tracing and observability
6. Chaos engineering principles
7. Disaster recovery — RPO and RTO
8. Multi-region architectures
9. Cost optimisation at scale

### Unit 5 — Modern Patterns and Critique (9 lectures)
1. Microservices — pros, cons, when not to
2. Event-driven architecture
3. CQRS and event sourcing
4. API design — REST, GraphQL, gRPC trade-offs
5. Serverless — fit, limits, cold starts
6. Data pipelines — batch and streaming
7. ML systems — feature stores, training, serving
8. Design review — how to critique a design
9. Case studies — what real systems got wrong

## Practical Labs (15)

1. Estimate QPS, storage, bandwidth for a chosen product
2. Whiteboard a URL shortener — 45 minutes
3. Whiteboard a rate limiter — distributed version
4. Whiteboard a key-value store
5. Whiteboard a web crawler
6. Whiteboard a news feed — fan-out comparison
7. Whiteboard a chat system
8. Whiteboard a search autocomplete
9. Whiteboard a ride-sharing system
10. Implement a token-bucket rate limiter
11. Implement a simple load balancer with nginx
12. Add caching to an existing app and measure latency
13. Set up a retry-with-backoff client
14. Design a system with a real SLO and measure it
15. Final — a complete design document for a chosen system

## Assignments

1. Estimation exercise — three products sized
2. Classic design writeup — pick one from Unit 3
3. Reliability analysis — an existing system's failure modes
4. Design critique — review a classmate's design
5. Final — a system design document with diagrams and trade-offs
