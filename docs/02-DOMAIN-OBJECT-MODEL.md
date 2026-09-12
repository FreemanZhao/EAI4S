# EAI4S Domain Object Model — Draft

> Status: Concept only. These are scientific-domain candidates, not stable EAOS contracts.

## Architecture Placement

EAI4S 是 Track D 自主科学发现战略参考验证域。Track A physAgentOS 是唯一统一 EAOS 基座；本文件中的科学领域对象、Gate 和闭环需求用于验证并反向施压 Track A，不定义平级 Runtime、Governance、Evidence 或 Evolution authority。Track C 的 VLA/ActionProducer 能力若被科学实验使用，也必须通过 Track A 接入。D0 当前只产生设计要求，不构成运行证据。

```text
ScientificQuestion
Hypothesis
MechanismConstraint
ExperimentObjective
ExperimentalProtocol
ProtocolCompilation
ExperimentRun
SampleBatch
InstrumentConfiguration
CalibrationRecord
ScientificObservation
MeasurementDataset
AnalysisPlan
AnalysisResult
DiscoveryClaim
ReplicationPlan
ReplicationResult
ScientificSafetyCase
KnowledgeCommit
```

Every object requires immutable identity, version/hash, parent refs, principal, time and evidence refs where applicable. Observation, inference and confirmation are separate types or states.

EAOS generic contracts remain external authority: Principal, Policy, Approval, Lease, Cancel, Task, World, Resource, Device, Invocation, Evidence, Verifier, Audit, Artifact and ImprovementCandidate.

