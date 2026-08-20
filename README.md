# Tomas A. Martinez

**Founder / Principal | Willow & Birdie Innovations LLC**

I build practical software for difficult digital systems, with a focus on **digital forensics, applied AI, evidence processing, and automation**.

My work tends to live where software has to do more than produce an answer. It has to explain **what it found, where it came from, and what the evidence actually supports**.

## Current Work

### APK Sentinel

**Deterministic, evidence-backed static APK triage for software agents and security workflows.**

APK Sentinel accepts an Android APK and produces structured, machine-readable evidence about static characteristics, including:

- permissions and manifest declarations
- exported components and exposure
- static API and behavioral indicators
- deterministic rule contributions and risk scoring
- versioned JSON output for downstream systems and agents

The system is deliberately bounded. APKs are treated as untrusted evidence, not executed applications.

Testing against real-world APKs has driven work around oversized inputs, partial-analysis states, provenance, temporary-artifact cleanup, repeatability, and concurrent processing.

**[Explore the APK Sentinel repository](https://github.com/tmtz1/apk-sentinel)**

## What I Build

### Digital Forensics

Evidence acquisition, normalization, provenance, analysis, and defensible reporting.

### Applied AI and Agents

Using language models and autonomous agents as components of larger systems rather than treating the model itself as the product.

### Evidence-First Software

Systems designed to distinguish observations, inferences, uncertainty, and unsupported claims.

### Local and Private AI

Practical architectures where sensitive data, models, or workflows can remain under the operator's control.

### Automation and Tooling

Turning complex technical workflows into repeatable software interfaces that humans and agents can both use.

## Engineering Approach

A few principles show up repeatedly in my work:

- **Evidence over assertion.** Outputs should be traceable to what the system actually observed.
- **Determinism where it matters.** The same evidence should produce the same result when the underlying rules have not changed.
- **Explicit uncertainty.** Partial analysis should be represented as partial analysis, not quietly presented as complete.
- **Fail closed.** Unsupported or malformed input should produce a defined failure state rather than an invented answer.
- **Agents need contracts.** AI systems become much more useful when the tools around them expose stable schemas, bounded behavior, and predictable error states.
- **Real inputs beat idealized tests.** Production-like edge cases are where architecture gets honest.

Failed assumptions are useful engineering evidence. When real-world testing breaks an implementation, the important question is what the failure teaches us about the design.

## Selected Projects

### APK Sentinel

Static Android APK triage designed for programmatic and agent-driven workflows.

**[Project repository](https://github.com/tmtz1/apk-sentinel)**

### Willow & Birdie Innovations

Applied software research and development spanning digital forensics, data analysis, AI-assisted workflows, and automation.

**[Public engineering showcase](https://github.com/tmtz1/willow-birdie-public-showcase)**

**[willowbirdie.com](https://www.willowbirdie.com/)**

## Building for Humans and Agents

One area I am particularly interested in is the changing interface between software systems and AI agents.

Traditional tools assume a human will read a screen, interpret an error, or decide what an ambiguous result means.

Agent-facing systems need something different:

**structured evidence | stable contracts | explicit state | bounded behavior | machine-readable errors**

I am exploring what software looks like when an AI agent is a first-class consumer of the system rather than an afterthought.

---

*Practical software. Difficult digital systems. Claims supported by evidence.*
