---
title: "HCOS™ AI Action and Authority Continuum"
subtitle: "A human-centered method for distinguishing AI assistance from delegated action in healthcare"
classification: "HCOS™ Stewardship Method"
discipline: "D-002 — Human-Centered AI"
architectural_pillar: "Identity, Authority, and Delegation Stewardship"
status: "Draft"
version: "1.0"
---

# HCOS™ AI Action and Authority Continuum

## Purpose

Healthcare discussions about AI often collapse very different capabilities into one category: **AI use**.

However, asking an AI system to summarize a chart is not equivalent to allowing an AI system to submit a prior authorization, modify an order, communicate a clinical recommendation, or complete a workflow step on behalf of a healthcare professional.

HCOS™ therefore separates **assistance** from **action**.

> **The closer AI moves toward consequential action, the stronger the requirements for identity, context, authority, review, reliability, and accountability become.**

---

## Continuum

### 1. Retrieve

The AI locates information without changing the underlying workflow.

**Examples:**

- locating an approved policy;
- finding a laboratory result;
- retrieving payer criteria;
- identifying prior documentation.

**Primary stewardship concern:** correct source and correct context.

### 2. Summarize

The AI condenses existing information.

**Examples:**

- summarizing a chart;
- summarizing prior treatment history;
- summarizing a payer policy.

**Primary stewardship concern:** accuracy, omission, provenance, and context preservation.

### 3. Organize or Identify

The AI structures information or highlights possible gaps.

**Examples:**

- identifying missing documentation;
- grouping messages;
- prioritizing a work queue;
- identifying possible discrepancies.

**Primary stewardship concern:** false prioritization, missing information, and hidden assumptions.

### 4. Draft

The AI prepares content that is not yet acted upon.

**Examples:**

- drafting a patient message;
- drafting a prior authorization narrative;
- drafting documentation;
- drafting an appeal.

**Primary stewardship concern:** meaningful human review before use.

### 5. Recommend

The AI proposes a course of action.

**Examples:**

- identifying a potential therapy option;
- recommending follow-up;
- suggesting that a case requires escalation.

**Primary stewardship concern:** professional judgment, evidence quality, uncertainty, and decision ownership.

### 6. Communicate

The AI sends information to another person or system.

**Examples:**

- sending a patient message;
- transmitting information to another care team;
- notifying a payer or pharmacy.

**Primary stewardship concern:** representation, consent, message accuracy, and communication authority.

### 7. Submit

The AI performs a formal workflow transaction.

**Examples:**

- submitting a prior authorization;
- submitting documentation to a payer;
- completing a structured external request.

**Primary stewardship concern:** delegated authority, auditability, and workflow ownership.

### 8. Modify

The AI changes a record, status, or workflow state.

**Examples:**

- changing a task status;
- updating structured data;
- modifying an order-related field;
- altering a workflow queue.

**Primary stewardship concern:** consequence, reversibility, authorization, and review.

### 9. Initiate or Order

The AI initiates a consequential process.

**Examples:**

- initiating a treatment-related workflow;
- placing or changing an order when permitted by law and policy;
- starting a clinical escalation pathway.

**Primary stewardship concern:** explicit authority, professional accountability, and safety controls.

### 10. Complete

The AI closes a workflow or represents that an intended outcome has been achieved.

**Examples:**

- closing a care coordination task;
- marking a requirement complete;
- finalizing a transaction.

**Primary stewardship concern:** whether completion is actually true and whether unresolved work has been hidden.

---

## Stewardship Principle

Authority should not be granted simply because the AI is technically capable of performing the next step.

Instead, authority should reflect:

- the identity being represented;
- the active context;
- the purpose of the task;
- the information required;
- the consequence of error;
- the reversibility of the action;
- the uncertainty involved;
- the professional responsibility attached to the task;
- and the reliability of the surrounding system.

## Practical Healthcare Rule

A healthcare organization should be able to distinguish clearly between:

> **The AI prepared the work.**

and

> **The AI performed the work.**

Those are not the same governance state.

## Relationship to Human Review

Human review should increase as consequence and delegated authority increase.

A useful progression is:

**Retrieve → Summarize → Organize → Draft → Recommend → Communicate → Submit → Modify → Initiate → Complete**

The continuum is not intended to establish universal permission levels. It is a discussion method for identifying when AI crosses from support into delegated action.

