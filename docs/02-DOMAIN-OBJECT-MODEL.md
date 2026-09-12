# EAI4S Domain Object Model — Draft

> Status: Concept only. These are scientific-domain candidates, not stable EAOS contracts.

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

