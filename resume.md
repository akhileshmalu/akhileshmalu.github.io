# Akhilesh Maloo

<div class="contact-bar">

San Francisco, CA | akhileshmalu@gmail.com | (803) 636-1363 | [GitHub](https://github.com/akhileshmalu) | [LinkedIn](https://linkedin.com/in/akhileshmaloo)

</div>

## Summary

Staff software engineer with 13+ years of experience designing and operating high-scale distributed systems across platform infrastructure, real-time messaging, and payments. Deep expertise in Java/Spring Boot, Kafka, gRPC, and Kubernetes with a consistent focus on reliability, scalability, and developer experience. Strong track record of owning Tier-0 services end-to-end — from architecture through production operations — while driving org-wide improvements in deployment safety, observability, and operational efficiency. Actively leveraging AI-powered automation to accelerate incident response and developer productivity.

## Experience

<div class="company">Salesforce, San Francisco</div>

**Lead Member of Technical Staff — Platform Engineering**
<span class="dates">December 2023 — Present</span>

- Own and operate 3 Tier-0 and 2 Tier-1 platform services powering the real-time conversation platform — including a durable key-value store, an SSE-based event routing service, and a singleton key-distribution service — deployed on Kubernetes.
- Maintain a core shared library (app starter) adopted by 75+ services across the service stack, serving as the foundational dependency for the organization's microservice ecosystem.
- Enhanced the Event Bus Starter library with bi-directional streaming and batch event processing, reducing latency from ~7s to ~200ms and increasing throughput from 20 to 1,000 events/sec.
- Led Spring Boot 3.4 / JDK 17 upgrade across platform services and shared libraries, achieving security compliance and unblocking 75+ downstream services from modernizing their stack.
- Drove migration of all platform services to Helm add-on and Argo Rollout, enabling canary deployments that reduced blast radius for production releases; now advising other teams on safe adoption.
- Architected bucket-snapshot handoff mechanism for the persistence layer, enabling seamless state transfers during restarts and rebalancing to support 100K concurrent conversations.
- Built automated Grafana dashboards integrated with SLO exporters, enabling self-service onboarding for new services and improving pager-duty investigation and resolution times.
- Resolved critical GovCloud deployment blockers (BouncyCastle/OpenSAML incompatibilities) and patched time-sensitive 3PP vulnerabilities across production services.
- Led production buildouts, moratorium exit criteria, and incremental rollout configuration with performance testing for safe, phased deployments.
- Built AI-powered automation (50+ multi-agent skills) for incident triage, deployment monitoring, and oncall diagnostics — reducing routine operational toil and enabling faster resolution across the team.

**Lead Member of Technical Staff — Messaging**
<span class="dates">November 2021 — March 2023</span>

- Architected and built gRPC microservices for the conversation messaging platform — Send Message, Transfer, Conference, Typing Indicators, Read/Delivery Receipts — on a distributed, multi-tier system using Kafka, gRPC, and SSE.
- Delivered full-stack real-time messaging UI in the Salesforce Lightning framework, achieving sub-millisecond push communications.
- Developed an availability framework for front-end and back-end services, maintaining 99.95% uptime across component features.
- Built and maintained 90% code coverage through unit, functional, integration, and disruptive testing.

<div class="company">Bill.com, San Jose</div>

**Staff Software Engineer**
<span class="dates">March 2023 — December 2023</span>

- Led cross-functional delivery of Bank Search and FX Payment Processing features, driving international payments expansion for the platform.
- Designed and built well-documented APIs for international payment workflows, serving both internal teams and external integrators.
- Implemented comprehensive monitoring and alerting on Splunk and Datadog, enabling proactive detection of performance degradation and critical incidents.

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

**Languages & Frameworks:** Java, Spring Boot, J2EE, JavaScript, Angular, HTML/CSS, PHP, Node.js

**Data & Messaging:** Kafka, MySQL, MongoDB, Cassandra, Oracle SQL

**APIs & Protocols:** gRPC, REST, SOAP, SSE

**Infrastructure & CI/CD:** Kubernetes, Helm, Argo Rollouts, AWS (S3), Docker, Jenkins, Maven

**Observability:** Splunk, Datadog, Grafana

**AI & Automation:** Multi-Agent Orchestration, Claude Code Skills, AI-Assisted DevOps, LLM-Driven Incident Response

**Testing:** JUnit, TestNG, Mockito, Selenium, Test Automation Frameworks

## Education

### Master of Software Engineering — University of South Carolina, Columbia, SC
<span class="dates">August 2016 — December 2017</span>
