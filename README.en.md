# Akihisa Ono / 小野 昭久（古明地ゆとり / Yutori Komeiji）

[日本語版 / Japanese](./README.md)

Enterprise SAP practitioner with **20+ years of experience** and an independent AI systems designer working on **responsibility pathways, bounded AI authority, human-return mechanisms, and operational controls for AI-enabled systems**.

I publish under **Akihisa Ono / 小野 昭久**, **古明地ゆとり (Yutori Komeiji)**, and the ID **dantarg**.

My work currently sits at the intersection of:

- enterprise systems and SAP delivery;
- AI judgment and responsibility-pathway design;
- runtime governance for AI agents and external actions;
- human–AI system architecture;
- public technical writing and open research artifacts.

---

## Current public work

### Responsibility Pathway Design (RPD)

**[responsibility-pathway-design](https://github.com/YutoriKomeiji/responsibility-pathway-design)**

A provisional, reviewable design framework for keeping responsibility connected across **judgment, delegation, execution, interruption, recovery, and residual impact** in AI-involved sociotechnical systems.

Public artifacts include design patterns, transformation records, assurance interfaces, operational monitoring and reopening structures, worked cases, and verification/validation vocabulary.

### Responsibility Pathway Engineering (RPE)

**[responsibility-pathway-engineering](https://github.com/YutoriKomeiji/responsibility-pathway-engineering)**

A public reference kernel and toolkit for turning explicitly scoped Responsible AI requirement mappings into bounded runtime controls such as:

```text
allow / hold / human_gate / deny
```

The current public repository documents the **M1 Governed Reference Kernel**, including a deterministic Python kernel, requirement-pack evaluation, REST/OpenAPI/MCP reference interfaces, lifecycle governance, versioning, schemas, fixtures, checkers, and CI guards.

### Responsibility Pathway Runtime (RPR)

**[responsibility-pathway-runtime](https://github.com/YutoriKomeiji/responsibility-pathway-runtime)**

An MIT-licensed Python runtime for placing an explicit responsibility pathway in front of consequential external actions.

The current public alpha is **0.1.0a4**, with a published package on PyPI. Its documented scope includes persistent pathway state, Human Gates, repair/resume/reconciliation boundaries, readback-aware execution handling, crash/restart continuity, MCP integration, and selected Lean 4 state-machine invariants.

- PyPI: https://pypi.org/project/responsibility-pathway-runtime/
- Live browser demo: https://yutorikomeiji.github.io/responsibility-pathway-runtime/demo.html

### Asymmetric Human–AI Agency (AHAA)

**[Asymmetric-Human-AI-Agency](https://github.com/YutoriKomeiji/Asymmetric-Human-AI-Agency)**

A design principle and reference architecture built around a simple rule:

> **Capability may be delegated. Authority must not be.**

The repository focuses on preventing silent autonomy drift, preserving explicit human decision points, and keeping AI as a bounded non-sovereign actor.

---

## Enterprise background

I have worked on SAP-related projects in Japan for more than two decades, spanning implementation, maintenance, consulting, coordination, and project leadership.

### Delivery / development

- ABAP development
- basic design
- development leadership
- interface-related coordination
- integration-phase support

### Consulting / project work

- requirements definition
- functional consulting
- migration coordination
- team lead / sub-lead roles
- PMO
- project management
- support for client-side project leadership

### SAP domains

My experience includes:

- logistics
- manufacturing-related processes
- finance / controlling
- analytics / reporting

Stronger areas include inventory-related operations, cost accounting, and cost control / management.

I have worked with both classic SAP environments and S/4HANA-based landscapes, including on-premise and cloud-oriented projects.

### Industry exposure

Projects have included sectors such as:

- trading
- manufacturing
- pharmaceuticals
- advertising / media-related work
- industrial equipment and related business domains

---

## Why I publish this work under my own name

I am employed by a company, but the AI responsibility research and OSS presented here are **personal research activities, separate from my employer's product activity**.

For that reason, I do not present this work under my employer's name or imply employer sponsorship, endorsement, or institutional authority.

At the same time, I do not want personal research to become anonymous or responsibility-free simply because it is independent. If I publish software, architecture, claims, and design decisions publicly, I want the public record to make clear who is maintaining them, what is implemented, what remains unverified, and where criticism or repair can return.

That is why I publish under my real name, **Akihisa Ono / 小野 昭久**.

For me, open-source publication under my own name is not only about freedom to build. It is also a way of refusing to silently step away from the **Residual Owner** position for what I choose to publish.

This separation matters in both directions:

- my employer should not be treated as the author or sponsor of independent work it did not publish;
- I should not use the absence of an institutional label as a way to avoid responsibility for public artifacts I did publish.

---

## Design themes

Across my public AI work, recurring themes include:

- **Authority ≠ capability**
- **evidence sufficiency ≠ authority**
- AI output ≠ authorized organizational decision
- execution receipt ≠ verified external effect
- recovery ≠ automatic restoration of authority
- Human Return and Residual Owner should remain explicit
- technical controls should fail visibly rather than silently invent permission

I am particularly interested in systems that preserve responsibility through the full path from observation and judgment to execution, verification, interruption, recovery, and human return.

---

## Luminalia

I also design and operate **Luminalia**, a structured human–AI research and dialogue environment used for architecture work, evaluation, operational experiments, and reflective co-creation.

Public adjacent architecture work includes responsibility-pathway research and human–AI agency design; internal operational components are not presented here as public evidence.

---

## Public writing

I publish technical and conceptual writing on AI judgment, responsibility pathways, human–AI agency, and operational governance.

- **note:** https://note.com/dantarg
- **Zenn:** https://zenn.dev/dantarg
- **LinkedIn:** https://www.linkedin.com/in/akihisaono

---

## Selected public repositories

- [Responsibility Pathway Design](https://github.com/YutoriKomeiji/responsibility-pathway-design)
- [Responsibility Pathway Engineering](https://github.com/YutoriKomeiji/responsibility-pathway-engineering)
- [Responsibility Pathway Runtime](https://github.com/YutoriKomeiji/responsibility-pathway-runtime)
- [Asymmetric Human–AI Agency](https://github.com/YutoriKomeiji/Asymmetric-Human-AI-Agency)
- [genai-web](https://github.com/YutoriKomeiji/genai-web)
- [genai-ai-api](https://github.com/YutoriKomeiji/genai-ai-api)

---

## Research posture

I try to keep public claims narrower than the evidence supporting them.

Public repositories are treated as **reviewable engineering and research surfaces**, not as automatic proof of safety, compliance, legal adequacy, production readiness, or external validation.

Where possible, I separate:

- observed evidence from interpretation;
- design verification from implementation verification;
- exercise evidence from operational evidence;
- formal-model results from runtime and real-world claims;
- assurance from authorization.

---

## Identity anchor

This profile repository connects the public identity:

**Akihisa Ono = 小野 昭久 = 古明地ゆとり = Yutori Komeiji = dantarg**

across enterprise systems practice, AI system design, public writing, and responsibility-pathway research.
