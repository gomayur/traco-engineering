
# Traco
### Engineering an AI-powered coordination platform

Traco is a mobile and web platform designed to simplify how individuals, families, groups and organisations coordinate schedules, commitments and events.

The platform combines structured workflows with conversational AI, allowing users to coordinate activities through natural-language interactions.

**Live product:** https://traco.app

---

## My Role

Independent Product & Engineering Lead

I designed and built Traco, taking the product from concept through architecture, implementation, AI integration and real-world deployment.

My work spans product strategy, application architecture, agent orchestration, context engineering, AI evaluation, security and production reliability.

---

## The Engineering Challenge

Coordinating commitments across multiple people involves fragmented communication, repeated follow-ups, scheduling conflicts and manual administrative work.

Traco explores how structured application workflows and conversational AI can work together to reduce these coordination overheads.

The engineering challenge extends beyond generating natural-language responses.

An AI-powered coordination platform must understand user intent, collect missing information, maintain state across interactions, execute actions reliably and protect user information.

---

## Technical Architecture

The platform combines:

- Mobile and web application interfaces
- Conversational AI and model orchestration
- Context retrieval and construction
- Stateful agent procedures
- Structured tool execution
- Persistent application data
- Authentication and access controls
- Evaluation, usage accounting and observability

The architecture separates probabilistic AI reasoning from deterministic application execution.

This separation allows the system to use AI for understanding and planning while retaining application-level control over data access and state-changing operations.

---

## Engineering Focus Areas

### 1. Agent Architecture

Designed an agent architecture incorporating intent routing, planning, response composition and structured tool execution.

Implemented stateful procedures for multistep interactions, including collecting missing information, presenting a summary and requesting confirmation before executing actions.

### 2. Context Engineering

Developed context retrieval and construction mechanisms to provide AI components with task-relevant information.

Introduced context measurement and retrieval planning to support more efficient context utilisation and improve the relevance of information supplied to models.

### 3. AI Evaluation and Reliability

Built an evaluation harness to assess intent classification, information extraction, unexpected fallbacks and context consumption.

Established a repeatable testing approach to support regression analysis and iterative improvements.

### 4. Production Engineering

Implemented application-level mechanisms for authentication, access control, rate limiting, usage accounting and reliable workflow execution.

Worked on retry and timeout handling, execution state management and operational observability.

### 5. Real-World Deployment

Developed public-event registration and coordination capabilities supporting account-less registration, QR-code access, SMS confirmations and operational reporting.

The platform was used to support a large community event with more than 2,600 attendees.

---

## Technology Stack

- TypeScript and React
- Supabase and PostgreSQL
- Conversational AI and LLM APIs
- Structured tool calling
- Mobile and web application development
- Cloud-based application infrastructure

---

## Engineering Documentation

This repository will contain selected technical case studies, architecture diagrams, evaluation methodologies and engineering learnings from building Traco.

The commercial application's production source code is maintained separately and is not included in this repository.

All examples and demonstrations published here use sanitised or synthetic information.

---

## Product

Visit Traco: https://traco.app

*Less Coordination. More Living.*
  
