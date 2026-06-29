 # Open Questions

**Project:** RecriVio – AI-Powered Recruitment Intelligence Platform

**Document Type:** Research Assumptions & Validation Framework

**Purpose**

This document is **not** a project backlog.

It is a strategic research artifact that identifies every critical unknown, assumption, dependency, uncertainty, and validation point that may influence the future evolution of RecriVio.

The objective is to minimize engineering risk before scaling the platform.

---

# Research Philosophy

```text
                     CURRENT KNOWLEDGE
                             │
                             ▼
                    Existing Assumptions
                             │
                             ▼
                  Evidence Collection Phase
                             │
                             ▼
                    Technical Validation
                             │
                             ▼
                    Business Validation
                             │
                             ▼
                    User Validation
                             │
                             ▼
                  Decision & Prioritization
                             │
                             ▼
                     Product Roadmap
```

---

# Complete Assumption Hierarchy

```text
                               RECRIVIO

                                   │

     ┌──────────────┬──────────────┬──────────────┬──────────────┐

     │              │              │              │

 Business      Technical        AI          Product

     │              │              │              │

 Market      Scalability     Accuracy     User Value

 Revenue     Security        Bias         Adoption

 Pricing     Performance     Explainability UX

 Hiring      Architecture    LLM Usage    Features

```

---

# Master Validation Pipeline

```text
Question

↓

Assumption

↓

Supporting Evidence

↓

Industry Research

↓

Prototype

↓

Internal Validation

↓

External Validation

↓

Business Decision

↓

Implementation

↓

Continuous Monitoring
```

---

# Validation Classification Matrix

| Level | Meaning               | Decision              |
| ----- | --------------------- | --------------------- |
| V0    | Unknown               | Research Required     |
| V1    | Hypothesis            | Prototype             |
| V2    | Internal Validation   | Small Scale Testing   |
| V3    | Industry Validation   | Compare with Market   |
| V4    | Production Validation | Enterprise Deployment |
| V5    | Continuous Monitoring | Product Evolution     |

---

# Open Questions Framework

```
Research Domain

↓

Unknown

↓

Risk

↓

Evidence Required

↓

Validation Method

↓

Success Criteria

↓

Decision
```

---

# SECTION A

# Business Questions

---

## BQ-01

### Is another recruitment platform actually needed?

Current Assumption

Existing ATS platforms solve workflow management better than recruitment intelligence.

Unknown

Do organizations prioritize intelligence over workflow?

Validation Sources

* Enterprise HR Teams
* Recruiters
* Hiring Managers
* CHRO Interviews

Evidence Required

* User Interviews
* Product Comparison
* Gartner Reports
* G2 Reviews
* Customer Feedback

Decision Impact

★★★★★

---

## BQ-02

Can executive dashboards influence hiring strategy?

Unknown

Do executives regularly consume hiring analytics?

Possible Validation

```
Executive Interview

↓

Current Dashboard Usage

↓

Decision Frequency

↓

Information Gap

↓

Dashboard Prototype

↓

Feedback
```

Priority

★★★★★

---

## BQ-03

Would organizations pay separately for Recruitment Intelligence?

Possible Models

```
ATS Included

ATS Plugin

Standalone SaaS

Enterprise License

API Platform

Consulting Product
```

Unknown

Most viable pricing strategy.

Risk

Revenue Model Failure

---

# SECTION B

# Market Questions

---

## MQ-01

Which company segment benefits most?

```
Startups

↓

SMBs

↓

Mid Enterprise

↓

Large Enterprise

↓

Government

↓

Staffing Agencies
```

Unknown

Initial Product Market Fit

---

## MQ-02

Which geography should be prioritized?

```
India

↓

United States

↓

Europe

↓

Middle East

↓

APAC
```

Unknown

Different recruitment maturity.

---

## MQ-03

Which industries experience the greatest hiring complexity?

Candidate Industries

Technology

Healthcare

Finance

Manufacturing

Retail

Consulting

Government

Priority

Research Required

---

# SECTION C

# Technical Questions

---

## TQ-01

Should RecriVio become a standalone ATS?

OR

An intelligence layer over existing ATS?

```
Standalone ATS

Advantages

Disadvantages

──────────────

ATS Intelligence Layer

Advantages

Disadvantages
```

Current Observation

Intelligence layer appears lower risk.

Needs Validation.

---

## TQ-02

Can architecture scale?

```
10 Users

↓

100

↓

1,000

↓

10,000

↓

100,000

↓

1 Million
```

Unknown

Performance bottlenecks.

Required Tests

Load Testing

Database Benchmark

API Benchmark

Caching Strategy

---

## TQ-03

Which database architecture scales better?

```
Only PostgreSQL

PostgreSQL + Redis

MongoDB + PostgreSQL

Event Driven

Warehouse Architecture

Lakehouse
```

Decision

Future Research

---

# SECTION D

# Artificial Intelligence Questions

---

## AIQ-01

Should Resume Ranking use LLMs?

Alternative

Traditional ML

Embedding Models

Fine Tuned Models

LLM

Hybrid

Unknown

Cost

Latency

Accuracy

Explainability

---

## AIQ-02

Can AI explain WHY a candidate ranked first?

Current Challenge

```
Prediction

↓

Explanation

↓

Recruiter Trust

↓

Adoption
```

Explainability becomes more important than accuracy in enterprise hiring.

---

## AIQ-03

Can hallucinations influence hiring?

Risk Level

Critical

Validation

```
AI Output

↓

Human Review

↓

Correction

↓

Learning

↓

Improved Model
```

---

# SECTION E

# Product Questions

---

## PQ-01

Which feature creates the highest business value?

Current Candidates

Executive Dashboard

Resume Intelligence

Hiring Analytics

Skill Intelligence

Recruiter Productivity

Interview Intelligence

Unknown

Highest ROI

---

## PQ-02

Which feature should never be built?

Research Rule

```
Popular

≠

Valuable
```

Need

Customer Interviews

---

# SECTION F

# User Questions

```
Recruiter

↓

Hiring Manager

↓

CHRO

↓

CEO

↓

Candidate

↓

Administrator
```

Every user should answer

What problem does RecriVio solve better than current tools?

If answer unclear

↓

Feature reconsideration.

---

# SECTION G

# Competitive Landscape

Questions

Can Microsoft build this?

Can LinkedIn build this?

Can Greenhouse replicate this?

Can Workday integrate this?

Can Lever launch similar analytics?

Can Ashby outperform this?

If YES

↓

Where is differentiation?

---

# SECTION H

# Research Risks

```
Research Bias

↓

Confirmation Bias

↓

Selection Bias

↓

Technology Bias

↓

Market Bias

↓

Data Bias
```

Mitigation

Cross Verification

Independent Validation

Industry Interviews

---

# SECTION I

# Product Kill Criteria

RecriVio should stop development if

```
No Market Need

OR

No Competitive Advantage

OR

No Revenue Potential

OR

No Measurable Business Value

OR

AI adds no meaningful improvement

OR

Recruiters reject workflow
```

---

# SECTION J

# Success Validation

```
Research

↓

Prototype

↓

Internal Testing

↓

Recruiter Feedback

↓

HR Feedback

↓

Executive Feedback

↓

Enterprise Pilot

↓

Commercial Product
```

---

# Critical Unknown Dashboard

```
Business

██████████████░░░░░ 72%

Technology

████████████████░░░ 81%

AI

████████████░░░░░░░ 64%

Market

███████████░░░░░░░░ 58%

Legal

████████░░░░░░░░░░░ 43%

Product

███████████████░░░░ 78%
```

---

# Research Heatmap

```
HIGH PRIORITY

■ Enterprise Validation

■ Recruiter Interviews

■ Product Market Fit

■ AI Explainability

■ Pricing Strategy

■ ATS Integration

────────────────────────

MEDIUM PRIORITY

■ Dashboard Adoption

■ Candidate Behaviour

■ Analytics Accuracy

■ Feature Usage

────────────────────────

LOW PRIORITY

■ UI Personalization

■ Themes

■ Export Formats

■ Localization
```

---

# Executive Decision Matrix

```text
                HIGH IMPACT

                      ▲

 Validate Now      Build Immediately

                      │

──────────────────────┼──────────────────────

 Research Later    Ignore / Eliminate

                      ▼

                 LOW IMPACT
```

---

# Closing Principle

```
Every unanswered question is not a weakness.

It is a research opportunity.

The objective of RecriVio is not to prove every assumption correct.

The objective is to identify incorrect assumptions as early as possible, reduce uncertainty through evidence, and allow product decisions to be guided by validated learning rather than intuition.
```
