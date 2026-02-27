# Glossary

This glossary defines the formal terminology of Panorama Engine.

The terms describe architectural constructs and system states.  

---

# 1. Identity & Versioning

## Engine ID

The unique identifier of a Panorama Engine instance.

---

## Kernel Cycle ID

The unique identifier assigned to each Cycle execution.

It provides referential traceability across time.

---

## Super Cycle ID

A higher-order identifier grouping related Cycles under a shared contextual scope.

---

## Snapshot Version

The formal version identifier of the Snapshot structure.

---

## Schema Version

The version identifier governing structural data definitions.

---

## Policy Version

The version identifier of the active Decision Policy.

---

## Policy Hash

A cryptographic reference representing the structural state of a Decision Policy.

---

## Freeze Hash

A verifiable fingerprint sealing a Snapshot at a specific execution point.

---

# 2. Core Cycle & Snapshot

## Kernel Cycle

The canonical deterministic execution unit of Panorama Engine.

Each Kernel Cycle produces a Global Snapshot.

---

## Global Snapshot

The formally sealed representation of system state at the conclusion of a Kernel Cycle.

It contains:

- Decision Artifact  
- Integrity classification  
- Context references  
- Version identifiers  

---

## Snapshot Status

The formal execution classification assigned to a Global Snapshot.

It reflects structural validity and governance compliance.

---

## Snapshot Contract

The structural agreement defining what a Snapshot must contain in order to be considered valid.

---

## Snapshot Timeline

The ordered historical sequence of Snapshots.

---

## Snapshot Diff

A structural comparison between two Snapshots within the Timeline.

---

## System State

The formalized condition of the engine at a given Snapshot.

---

## State Transition

A governed change between System States.

All transitions must comply with governance constraints.

---

# 3. Governance & Integrity

## Governance Layer

The architectural layer enforcing structural constraints and admissible state transitions.

---

## Governance Policy Mode

The active governance configuration under which the system operates.

---

## Execution Gate

A structural control mechanism determining whether execution may proceed under current conditions.

---

## Contract Gate

A structural validation mechanism ensuring Snapshot compliance with the Snapshot Contract.

---

## Decision Policy

The formal rule set governing decision logic within a Kernel Cycle.

---

## Integrity Flag

A categorical indicator reflecting structural coherence or deviation.

---

## Invariants

Structural conditions that must hold true across Cycles and Snapshots.

---

## Fail Hard

A governance mode in which structural violations prevent further execution.

---

## Read-Only Mode

An operational state in which execution is suspended and only observation is permitted.

---

## Limited Mode

A restricted execution state activated under predefined governance conditions.

---

# 4. Analytical & Regime Layer

## Regime Engine

The analytical component responsible for structural classification of market conditions.

---

## Global Regime

The system-wide classification of prevailing analytical conditions.

---

## Regime Transition

A formally recognized shift between Regime classifications.

---

## Threshold Profile

The structured configuration defining sensitivity parameters for analytical evaluation.

---

## Calibration Profile

A formally defined adjustment configuration used to align analytical outputs with governance standards.

---

## Confidence Score

A structural indicator expressing the internal consistency of a Decision Artifact within its context.

---

## Market Pressure

A structured analytical metric reflecting directional aggregation across asset classes.

---

## Risk Score

A categorical indicator representing structural exposure within the analytical model.

---

# 5. Operational Context

## Execution Status

The formal runtime classification of the engine (e.g., active, restricted, halted).

---

## Tenant Scope

The bounded operational domain of a specific Panorama Engine deployment.

---

## Enterprise Mode

An operational configuration enabling full governance enforcement and audit traceability.

---

## Self-Hosted Instance

A deployment configuration in which Panorama Engine operates within a controlled institutional environment.
