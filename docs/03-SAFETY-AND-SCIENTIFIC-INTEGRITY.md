# EAI4S Safety and Scientific Integrity

> Status: Concept / Discussion Draft

## Architecture Placement

EAI4S 是 Track D 自主科学发现战略参考验证域。Track A physAgentOS 是唯一统一 EAOS 基座；本文件中的科学领域对象、Gate 和闭环需求用于验证并反向施压 Track A，不定义平级 Runtime、Governance、Evidence 或 Evolution authority。Track C 的 VLA/ActionProducer 能力若被科学实验使用，也必须通过 Track A 接入。D0 当前只产生设计要求，不构成运行证据。

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

