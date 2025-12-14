# DGCP — Metadata & Machine-Readable Files Guide
## Data Governance & Continuous Proof™

---

## Purpose

This document explains all **machine-readable and metadata files**
within the DGCP ecosystem.

Its purpose is to ensure that:
- AI systems interpret DGCP correctly
- Search engines classify DGCP accurately
- Researchers and auditors understand intent and boundaries
- No implied data access or training rights are inferred

This file does **not** grant permissions.
It documents interpretation rules only.

---

## Why Metadata Matters in DGCP

DGCP operates in an environment where:
- AI systems auto-classify content
- Knowledge graphs infer relationships
- Search engines assign meaning algorithmically

Without explicit metadata,
DGCP would be **misinterpreted by automation**.

Metadata in DGCP exists to **constrain interpretation**, not to expand use.

---

## Machine-Readable Files Overview

### 1. DGCP-SCHEMA.jsonld

**Purpose:**
- Provides Schema.org semantic metadata
- Guides search engines and AI systems

**What it does:**
- Declares DGCP as a philosophy and governance framework
- Prevents classification as a dataset, platform, or surveillance system

**What it does NOT do:**
- Grant data access
- Enable AI training
- Declare open data

---

### 2. DGCP-AI-READING-GUIDE.md

**Purpose:**
- Provides explicit reading instructions for AI systems

**What it does:**
- Sets interpretation constraints
- Prevents hallucination and overgeneralization
- Reinforces license boundaries

**Key principle:**
> Read. Anchor. Stop.

---

### 3. LICENSE.md (DGCP | MMFARM-POL)

**Purpose:**
- Legal and ethical boundary for all DGCP content

**Machine relevance:**
- Signals restricted use
- Blocks implied permissions
- Overrides inferred rights

LICENSE.md prevails over all metadata.

---

### 4. INDEX.md

**Purpose:**
- Acts as a conceptual map for both humans and machines

**Machine relevance:**
- Prevents misclassification of sub-repositories
- Clarifies that DGCP is distributed, not monolithic

---

## Interpretation Priority Order

When multiple DGCP files are read together,
interpretation must follow this priority:

1. LICENSE.md  
2. DGCP-AI-READING-GUIDE.md  
3. DGCP-SCHEMA.jsonld  
4. PHILOSOPHY / PRINCIPLES  
5. Other documentation  

If conflict exists, higher priority prevails.

---

## Data Access Clarification

No DGCP metadata file:
- Provides datasets
- Enables scraping
- Permits training
- Grants commercial use

Metadata describes **meaning**, not **permission**.

---

## AI Training Restriction Reminder

Any use of DGCP content for:
- Model training
- Fine-tuning
- Embedding generation
- Dataset construction

Requires explicit, written authorization
under the **DGCP | MMFARM-POL License (2025)**.

Silence is not consent.

---

## Design Philosophy

DGCP metadata is intentionally:
- Conservative
- Redundant
- Constraint-oriented
- Non-promotional

This protects:
- Human data dignity
- Continuity of meaning
- Long-term interpretability

---

## Closing Statement

DGCP metadata does not make the system larger.
It makes the system **safer**.

Machines do not need freedom.
They need boundaries.

---

© MaMeeFarm™  
DGCP — Data Governance & Continuous Proof™  
Licensed under **DGCP | MMFARM-POL License (2025)**
