# RKHP Safety Principles

RKHP develops systems that interact with the physical world.

Safety is therefore a core engineering requirement.

---

## Fundamental Principle

No experimental intelligence should have unrestricted authority over
physical systems.

---

## Early Development

Physical actions should remain:

- bounded
- observable
- logged
- reversible where possible
- subject to manual intervention

---

## Human-in-the-Loop

Early autonomous experiments should follow:

AI Recommendation
↓
Safety Validation
↓
Human Approval
↓
Action
↓
Verification

---

## Physical Safety

Experiments should use appropriate:

- emergency stops
- speed limits
- actuator limits
- testing areas
- power protections
- manual overrides
- protective equipment where appropriate

---

## Software Safety

Software should include:

- input validation
- command validation
- safe defaults
- action limits
- logging
- failure handling

---

## Communication

The system must distinguish between:

- measured facts
- model predictions
- estimates
- hypotheses
- recommendations

Uncertainty should be communicated rather than hidden.

---

## Testing

New autonomous behaviors should first be tested in:

1. Simulation
2. Controlled environment
3. Limited physical testing
4. Expanded testing after validation

Testing around people requires appropriate safeguards.

---

## Responsibility

Every contributor is responsible for raising safety concerns.

No deadline overrides a legitimate safety concern.
