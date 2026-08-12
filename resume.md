# Akhilesh Maloo

<div class="contact-bar">

San Francisco, CA | akhileshmalu@gmail.com | (803) 636-1363 | [LinkedIn](https://linkedin.com/in/akhileshmaloo)

</div>

## Summary

Staff software engineer with 13+ years of experience designing and operating high-scale distributed systems across platform infrastructure, real-time messaging, and payments. Deep expertise in Java/Spring Boot, Kafka, gRPC, and Kubernetes with a consistent focus on reliability, scalability, and developer experience. Strong track record of owning Tier-0 services end-to-end — from architecture through production operations — while driving org-wide improvements in deployment safety, observability, and operational efficiency. Actively leveraging AI-powered automation to accelerate incident response and developer productivity.

## Experience

<div class="company">Salesforce, San Francisco</div>

**Lead Member of Technical Staff — Platform Engineering**
<span class="dates">December 2023 — Present</span>

- Designed and built an AI agent, integrated with Slack and PagerDuty, that automatically investigates production incidents using RAG-grounded runbook knowledge, Splunk logs, and internal time-series metrics, then drafts pre-validated remediation actions for human approval — resolves ~80% of incidents correctly in ~20 seconds, runs across the team's full 5-service on-call rotation, and has since been adopted by other teams for their own runbooks.
- Led a year-long Spring Boot 3.4 / JDK 17 migration unblocking 75+ downstream services — root-caused multiple critical production regressions along the way and built the automated deployment-safety process (rollback triggers, staged rollouts) that's since become the team's standard for risky redeployments.
- Led redesign of the platform's Kafka partitioning and persistence layer (spanning the durable key-value store, the shared client library, and the singleton key-distribution service) to eliminate lease-based partition management and Kafka write magnification for scaling to 100K+ concurrent conversations per org; cut aggregated query latency from 2-10s to a 1-18ms p95 and reduced service-to-service polling chatter ~87x (21.6M/hr to 247K/hr), now rolling out to production via a zero-downtime staged migration.
- Built a net-new disaster recovery cell — writing to a dedicated Kafka cluster — isolating premium-tier customers into a separate availability zone, contributing to the org-wide replication effort; resolved cluster/broker assignment via a heuristic built into the shared library, so all 75+ services adopted it transparently through a routine upgrade with zero disruption.
- Root-caused an undocumented runtime divergence between BouncyCastle and its FIPS-compliant variant — traced to custom EC curve handling, with no existing fix publicly available — and repackaged the library in Docker to exclude the problematic curves, closing a GovCloud compliance gap that was blocking a government customer's go-live.
- Diagnosed unary event-publish failures caused by JWT auth tokens expiring in transit before reaching the eventing backend; converted the API to bi-directional streaming with cached auth validation and added batch event processing, cutting per-call latency from ~7s to ~200ms and raising throughput from 20 to 1,000 events/sec.
- Piloted Salesforce's org-wide Argo Rollout addon on my team's services, then advised 20+ other platform teams (spanning 70+ services) on rollout configuration and pre-deployment validation strategy as they migrated off standard deployment objects — canary rollouts are now the org's default deployment path.
- Hold end-to-end ownership of 3 Tier-0 and 2 Tier-1 platform services powering the real-time conversation platform — including a durable key-value store, an SSE-based event routing service, and a singleton key-distribution service — deployed on Kubernetes.

**Lead Member of Technical Staff — Full Stack Engineering**
<span class="dates">November 2021 — March 2023</span>

- Led design and delivery of Transfer and Conference — two real-time messaging features built from scratch, front-end through backend gRPC integration — running it as a cross-team program with other teams' leads and architects; also delivered feature upgrades to the platform's existing Send Message, Typing Indicators, and Read/Delivery Receipts services (Kafka, gRPC, SSE).
- Instrumented client-side SLO availability signaling per feature via Salesforce's o11y library — each API call reports a feature-availability metric from the client's perspective — closing a blind spot server-side-only metrics miss; used for internal benchmarking, measuring 99.95% client-perceived availability across component features.

<div class="company">Bill.com, San Jose</div>

**Staff Software Engineer**
<span class="dates">March 2023 — December 2023</span>

- Led design and backend integration for Bank Search — building the ability to search and update bank records — as part of Bill.com's international payment workflows.

<div class="company">eBay, San Jose</div>

**Software Engineer**
<span class="dates">March 2018 — November 2021</span>

- Developed and scaled the checkout platform handling 200M+ API calls/day, 10M+ checkouts/day, and 36 client integrations.
- Integrated external payment providers (Adyen, PayPal, Klarna, Apple Pay, Google Pay, Afterpay) into the checkout pipeline.
- Spearheaded cache integration that reduced response time by 30% and database load by 20% — awarded Spot Award for initiative.
- Built automated deployment pipelines (ECD) improving continuous integration practices across the team.

<div class="company">Infosys, Pune, India</div>

**Sr. Associate Consultant**
<span class="dates">January 2015 — August 2016</span>

- Designed and developed Java web applications; owned testing cycle with automation tooling.

<div class="company">ING / ICICI Bank, Mumbai</div>

**System Analyst**
<span class="dates">April 2011 — January 2015</span>

- Business and systems analysis: requirements modeling, process mapping, UAT administration.

## Skills

**Languages & Frameworks:** Java, Spring Boot, Project Reactor, J2EE, JavaScript, Angular, HTML/CSS, PHP, Node.js

**Data & Messaging:** Kafka, MySQL, MongoDB, Cassandra, Oracle SQL

**APIs & Protocols:** gRPC, REST, SOAP, SSE

**Reliability & Resilience:** Rate Limiting (Envoy External RLS), Backpressure / Flow Control (Bounded Blocking Queues)

**Infrastructure & CI/CD:** Kubernetes, Helm, Argo Rollouts, AWS (S3), Docker, Jenkins, Maven

**Observability:** Splunk, Datadog, Grafana

**AI & Automation:** Multi-Agent Orchestration, Claude Code Skills, AI-Assisted DevOps, LLM-Driven Incident Response

**Testing:** JUnit, TestNG, Mockito, Selenium, Test Automation Frameworks

## Education

### Master of Software Engineering — University of South Carolina, Columbia, SC
<span class="dates">August 2016 — December 2017</span>
