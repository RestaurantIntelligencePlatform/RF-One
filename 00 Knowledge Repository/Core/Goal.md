# Goal

**Version:** 2.0
**Status:** Approved
**Module:** Core

---

# Purpose

A **Goal** defines the desired outcome that the system intends to achieve.

A Goal defines **what** must be achieved.

It never defines **how**, **who**, or **with which resources** the outcome is obtained.

---

# Definition

A Goal represents a business outcome independently from its implementation.

A Goal exists only when at least one Process has been defined to pursue it.

A desired outcome without an associated Process is a **Desire**, not a Goal.

---

# Principles

## 1. Outcome First

Every Goal defines only the expected outcome.

Execution belongs to the Process.

## 2. Independence from Execution

A Goal never defines:

- execution strategy
- execution order
- actors
- resources
- triggers
- technologies

These belong to the Process or to the runtime system.

## 3. Atomicity

A Goal represents exactly one business outcome.

Complex business objectives are achieved through multiple Processes, each owning its own Goal.

## 4. Identity

A Goal has its own immutable identity.

Changing parameters does not create a new Goal unless the business meaning changes.

## 5. Parameters

Thresholds, targets and tolerances are parameters.

Changing a target changes the Goal configuration, not the Goal identity.

## 6. Verification

Every Goal must be objectively verifiable through:

- a measurable value, or
- a logical condition.

## 7. Relationship with Process

Every Process exists to achieve exactly one Goal.

A Goal may be achievable through different Processes over time.

The system selects the most appropriate Process according to available capabilities and resources.

## 8. Independence from AI

Artificial Intelligence may optimize or generate Processes.

AI never changes the meaning of a Goal.

---

# Summary

A Goal defines **what** must be achieved.

A Process defines **how** it is achieved.

The runtime system decides **who or what** executes the Process.

This separation preserves the stability of the Core while allowing continuous evolution of execution strategies.
