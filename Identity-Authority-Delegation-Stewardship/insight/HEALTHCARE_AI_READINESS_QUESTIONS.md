---
title: "HCOS™ Healthcare AI Readiness Questions"
subtitle: "Practical questions for evaluating AI-enabled healthcare workflows before deeper coordination"
classification: "HCOS™ Discussion and Stewardship Guide"
discipline: "D-002 — Human-Centered AI"
architectural_pillar: "Identity, Authority, and Delegation Stewardship"
status: "Draft"
version: "1.0"
---

# HCOS™ Healthcare AI Readiness Questions

## Purpose

Healthcare teams do not need to understand every technical component of an AI system in order to ask meaningful governance questions.

They do need enough visibility to understand whether an AI-enabled workflow is operating within boundaries the organization can explain, supervise, correct, and remain accountable for.

This guide can be used before implementation, during pilot design, in governance review, or when evaluating an existing AI-enabled workflow.

> **The goal is not to ask whether AI can complete the task. The goal is to ask whether the surrounding system can safely support how the task is completed.**

---

## 1. Human Purpose

- What human or healthcare need is this AI-enabled workflow intended to address?
- Is the goal primarily clinical, operational, administrative, financial, educational, or supportive?
- Does the workflow reduce meaningful burden, or does it create new work elsewhere?
- Is AI being introduced because it improves the human outcome, or because the capability is available?

## 2. Identity

- Who is the AI representing at this moment?
- Is it acting for the patient, clinician, pharmacist, health system, payer, caregiver, or another participant?
- Can the system distinguish among these identities?
- Could one participant reasonably mistake the AI as representing someone else?

## 3. Context

- What role, encounter, patient relationship, workflow, and purpose are active?
- Is information from another context being carried forward?
- Could a preference or decision from a previous encounter be incorrectly treated as current?
- Can the system recognize when context has changed?

## 4. Information Access

- What information does the AI need for this task?
- What information does it not need?
- Is access limited to the minimum information required for the defined purpose?
- Does the workflow cross clinical, payer, pharmacy, scheduling, family, or organizational boundaries?
- Can the organization identify what information crossed those boundaries?

## 5. Memory

- What information is allowed to persist over time?
- What is the source of the remembered information?
- Was it true only in a specific context?
- Can the patient or healthcare professional correct it?
- Should it expire or require reconfirmation?
- Can the organization determine when remembered information influenced an action?

## 6. Delegated Authority

- What may the AI retrieve?
- What may it summarize?
- What may it draft?
- What may it communicate?
- What may it submit?
- What may it modify?
- What may it recommend?
- What may it complete?

Authority should be defined at the task level rather than granted broadly to an entire workflow.

## 7. Human Review

- What requires human review before the AI proceeds?
- What can be reviewed after the fact?
- Which actions are too consequential to occur without prior approval?
- Is the review requirement realistic within the actual healthcare workflow?
- Does the reviewing professional have enough information to meaningfully evaluate the AI output?

## 8. Accountability

- Who remains responsible for the final action?
- Can responsibility be identified when several AI systems or services participate?
- Is there a named human or organizational owner for the workflow?
- Could automation make responsibility less visible?

## 9. Interoperability

- Which systems must exchange information?
- Are they using the same patient identity, terminology, status definitions, and workflow state?
- What happens when records conflict?
- What happens when an external system is unavailable?
- Can the AI detect missing or incomplete information rather than silently proceeding?

## 10. Explainability and Auditability

- Can the organization reconstruct what happened?
- Can it identify which systems participated?
- Can it determine what information was used?
- Can it identify what authority was exercised?
- Can it see where human review occurred?
- Can an incorrect action be corrected?

## 11. Failure Conditions

Ask what happens when:

- the patient identity is incorrect;
- the medication list is outdated;
- the payer rule changes;
- the AI uses information from the wrong encounter;
- the patient changes a preference;
- an external system is unavailable;
- a human reviewer disagrees with the AI;
- two systems return conflicting information;
- or an action occurs before expected review.

A workflow should be evaluated not only when everything works, but also when the surrounding system is incomplete, contradictory, or under stress.

## 12. Human Load

- Does the AI actually reduce unnecessary burden?
- Does it create additional verification work?
- Are healthcare professionals expected to supervise automation without receiving additional time or capacity?
- Does the system shift hidden work onto patients, caregivers, pharmacists, nurses, or other teams?

## Practical Readiness Question

Before deeper AI coordination is introduced, healthcare teams should be able to answer:

> **Can we explain who acted, in what context, using what information, under what authority, with what review, and who remains accountable?**

If the answer is unclear, the workflow may not yet be ready for deeper AI coordination.
