# Dynamic Market Value Insurance (DMVI)

## Overview

Dynamic Market Value Insurance (DMVI) is a proposed insurance framework for high-value collectible assets in which:

* A **Deposit Premium** is calculated using the Scheduled Value at policy inception.
* The **Market Value** of insured property is periodically determined throughout the policy period using insurer-approved valuation methodologies.
* The **Final Earned Premium** is calculated using the **Time-Weighted Average Market Value** during the policy period.
* Covered losses are settled using the **Market Value on the Date of Loss**, regardless of the Scheduled Value.
* The insured has access to a transparent and auditable explanation of the valuation used to determine claim payments.

The objective of this repository is to develop the intellectual property, technical architecture, insurance policy language, and business documentation required to evaluate and commercialize the concept.

---

# Project Objectives

## Intellectual Property

* Develop a comprehensive invention disclosure.
* Prepare a self-filed provisional patent application.
* Document alternative embodiments and implementations.
* Record design decisions and invention history.

## Insurance Product

Develop complete policy language for:

* Definitions
* Insuring Agreement
* Deposit Premium
* Market Valuation
* Premium Calculation
* Claim Settlement
* Valuation Transparency
* Examples and illustrations

## Technical Design

Design a technology platform including:

* Policy Engine
* Valuation Engine
* Premium Engine
* Claims Engine
* Audit Engine
* Reporting Services

Produce:

* System architecture
* Database design
* API specifications
* Business rules
* UML and workflow diagrams

## Business Development

Develop:

* Executive Summary
* White Paper
* Business Model
* Competitive Analysis
* Licensing Strategy
* Prototype Roadmap

---

# Repository Structure

```text
DMVI/
│
├── README.md
├── CHANGELOG.md
├── DESIGN_DECISIONS.md
├── OPEN_QUESTIONS.md
│
├── patent/
├── policy/
├── business/
├── technical/
└── prototype/
```

---

# Core Business Concept

1. The **Scheduled Value** is used only to calculate the **Deposit Premium** at policy inception.

2. During the policy period, the insurer periodically determines the **Market Value** of each insured item using one or more approved valuation methodologies.

3. At the end of the policy period, the **Final Earned Premium** is calculated using the **Time-Weighted Average Market Value**.

4. Upon a covered loss, the claim payment is based upon the **Market Value immediately preceding the Date of Loss**, rather than the Scheduled Value.

5. The insured may obtain an auditable explanation of the valuation used to determine the claim payment.

---

# Guiding Principles

* Fairness to the insured
* Fairness to the insurer
* Transparency
* Auditability
* Consistent valuation methodology
* Flexible valuation sources
* Scalability
* Regulatory compliance
* Technology independence

---

# Current Project Phase

**Phase 1 – Invention Disclosure**

Initial deliverables include:

* Patent disclosure outline
* Definitions
* Background
* Problems with existing insurance methods
* Summary of the invention
* Detailed description
* Example policy workflow

---

# Long-Term Deliverables

* Provisional patent application
* Complete insurance policy language
* White paper
* Executive presentation
* Technical architecture
* REST API design
* Java prototype
* Licensing package
* Business plan

---

# Project Status

**Version:** 0.1

Status: Initial repository created.

This repository serves as the master source for all documentation related to the Dynamic Market Value Insurance (DMVI) project.

---

## Revision History

### Version 0.1

* Initial repository created.
* Defined project objectives.
* Established repository structure.
* Documented the core business concept.
* Defined long-term project roadmap.
