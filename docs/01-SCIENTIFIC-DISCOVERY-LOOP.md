# EAI4S Scientific Discovery Loop

> Status: Concept / Discussion Draft — No Code Development

## Architecture Placement

EAI4S 是 Track D 自主科学发现战略参考验证域。Track A physAgentOS 是唯一统一 EAOS 基座；本文件中的科学领域对象、Gate 和闭环需求用于验证并反向施压 Track A，不定义平级 Runtime、Governance、Evidence 或 Evolution authority。Track C 的 VLA/ActionProducer 能力若被科学实验使用，也必须通过 Track A 接入。D0 当前只产生设计要求，不构成运行证据。

```text
Question → Hypothesis → Protocol → Preflight → Governed Execution
→ Observation → Analysis → Claim → Replication → Knowledge → Next Hypothesis
```

## Stage Gates

| Stage | Required Output | Gate |
|---|---|---|
| Question | objective, scope, scientific principal | domain review |
| Hypothesis | mechanism, prediction, falsifier | competing hypothesis check |
| Protocol | controls, samples, procedure, stopping criteria | protocol review |
| Preflight | simulation, hazard and resource plan | safety approval |
| Execution | immutable run and action lineage | EAOS Policy/Lease/Cancel |
| Observation | raw multimodal evidence and QC | provenance completeness |
| Analysis | versioned method, uncertainty, alternatives | independent verifier |
| Claim | evidence-linked qualified statement | claim gate |
| Replication | repeat/transfer result | replication gate |
| Knowledge | confirmed, rejected or inconclusive result | human confirmation |

Parallel experiments share an objective but retain separate sample, instrument, environment, calibration and Evidence lineage.

