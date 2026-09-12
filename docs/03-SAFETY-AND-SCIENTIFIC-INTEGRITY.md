# EAI4S Safety and Scientific Integrity

> Status: Concept / Discussion Draft

## Non-negotiable Rules

```text
raw evidence is append-only
negative and inconclusive results are first-class
calibration and environment state are part of a run
analysis and evaluator versions are frozen per evaluation
claims expose uncertainty and falsification criteria
replication state is explicit
physical execution is governed, bounded and interruptible
```

## Initial Exclusions

No autonomous human-subject, clinical, unsafe biological, explosive/highly toxic, unbounded robotic or production-facility experiment. Regulated or secret data requires an approved data boundary.

## Physical Gate

```text
hazard classification → simulation/digital-twin preflight
→ independent safety review → explicit approval
→ bounded lease + interlocks + emergency stop
→ evidence capture → safe-state cleanup + recovery
```

No candidate may modify its own Authority, Evaluation or Provenance roots.

