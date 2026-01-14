---
name: end-to-end-process-design
description: Apply Michael Hammer's end-to-end process methodology to redesign organizational workflows for faster, cheaper, and better results. Use when users want to diagnose process problems, eliminate waste, redesign workflows, reduce cycle time, improve cross-functional collaboration, or prepare for AI/automation implementation. Specifically triggered by requests like "流程优化", "端到端流程", "BPR", "业务流程再造", "消除浪费", "跨部门协调", "流程卡住了", or scenarios involving slow processes, departmental silos, quality issues, or customer complaints about service delivery.
---

# End-to-End Process Design

Transform organizational workflows using Michael Hammer's proven methodology to achieve breakthrough improvements in speed, cost, and quality.

## Overview

This skill applies the end-to-end process framework from Michael Hammer's work to help organizations:

- **Diagnose** process inefficiencies and identify root causes
- **Redesign** workflows to eliminate waste and maximize value
- **Implement** process improvements with clear ownership and metrics
- **Enable** AI and automation on solid process foundations

The core philosophy: shift from department-centric thinking to end-to-end value delivery for customers.

## When to Use This Skill

Apply this skill when encountering:

**Process Problems**:
- Long cycle times (e.g., "30 days to complete but only 3 days of actual work")
- Frequent handoffs and waiting
- High error rates and rework
- Customer complaints about slow or complex processes

**Organizational Symptoms**:
- Cross-departmental conflicts and finger-pointing
- Dependence on "hero employees" to make things work
- Improvement efforts (Six Sigma, etc.) showing limited results
- No one owns end-to-end outcomes

**Strategic Initiatives**:
- Preparing to implement AI or automation
- Business transformation or digital transformation
- Responding to competitive pressure
- Scaling operations efficiently

## Core Methodology: 3-Phase Workflow

### Phase 1: Diagnose Current State

**Objective**: Understand the current process and identify improvement opportunities

**1.1 Conduct Initial Assessment**

Use the diagnostic questionnaire:
- Read `assets/diagnostic-questionnaire.md`
- Adapt and present relevant questions to the user
- Gather responses through conversation

**1.2 Apply Diagnostic Framework**

Reference `references/process-diagnostic-framework.md` for:
- Identifying process boundaries (start/end points)
- Classifying work into: value-add, non-value-add, waste
- Finding断点 (breakpoints) where process flows interrupt
- Calculating key metrics (cycle time, value-add ratio, handoff count)

**1.3 Map Current State**

Use `assets/process-map-template.md` to document:
- All process steps with roles and timing
- Handoffs and decision points
- Problem areas and bottlenecks
- Current metrics baseline

**Key Output**: Current state process map with quantified problems

### Phase 2: Design Future State

**Objective**: Redesign the process applying Hammer's six principles

**2.1 Apply Design Principles**

Reference `references/process-redesign-guide.md` for detailed guidance on:

1. **Organize around outcomes, not tasks**
   - Designate end-to-end process owners
   - Create roles that own complete customer outcomes

2. **Have those who use information produce it**
   - Capture data once at the source
   - Eliminate information handoffs

3. **Put decision-making where work is performed**
   - Empower front-line workers with clear rules
   - Replace approvals with monitoring

4. **Eliminate waste, minimize non-value-add**
   - Remove unnecessary steps entirely
   - Automate non-value-add where possible
   - Optimize value-add activities

5. **Parallelize instead of serialize**
   - Identify independent steps that can run concurrently

6. **Build in quality at the source**
   - Design error-proof mechanisms (Poka-Yoke)
   - Enable self-checking rather than separate QA

**2.2 Use Redesign Canvas**

Work through `assets/redesign-canvas.md` to:
- Apply each principle systematically
- Design new roles and responsibilities
- Define new metrics
- Plan technology enablers
- Identify obstacles and mitigation strategies

**Key Output**: Future state process design with clear implementation path

### Phase 3: Plan Implementation

**Objective**: Create actionable roadmap for change

**3.1 Establish Process Ownership**

Use `assets/process-owner-charter.md` to:
- Define the Process Owner role
- Specify responsibilities and authority
- Set KPIs aligned with end-to-end outcomes
- Secure executive sponsorship

**3.2 Develop Phased Roadmap**

Structure implementation in phases:
- **Quick Wins** (1-3 months): Low-hanging fruit for early momentum
- **Core Redesign** (3-6 months): Major process changes
- **Optimization** (6-12 months): Continuous improvement and scaling

**3.3 Address the Nine Levers**

While detailed guidance is in `references/《端到端流程》核心要点.md`, ensure your implementation plan covers:

**Process Enablers**:
1. Design (covered in Phase 2)
2. Metrics (define end-to-end KPIs)
3. Process Owner (assign with clear charter)
4. People & Infrastructure (training, systems)
5. Leadership & Culture (executive support, mindset shift)

**Enterprise Capabilities**:
6. Governance (decision-making structure)
7. Expertise (process management skills)
8. (Additional capabilities as needed)

**Key Output**: Implementation roadmap with clear milestones, owners, and success metrics

## Working with Users

### Question-Driven Approach

Don't assume you understand the process. Ask questions like:
- "When does this process actually start? What triggers it?"
- "What does 'complete' look like from the customer's perspective?"
- "Who touches this process? What do they do?"
- "Where does work sit waiting? Why?"
- "What percentage of steps actually add value the customer cares about?"

### Socratic Method for Root Causes

When users describe problems, dig deeper:
- "Why does that approval take so long?"
- "Why does information need to be re-entered?"
- "Why can't the person doing the work make that decision?"

Often the answer is "because that's how we've always done it" — that's your opening for redesign.

### Balance Ambition with Pragmatism

- Start with **one pilot process** if organization is new to this
- Pursue **breakthrough improvement** (30-50%+) not just incremental gains
- But ensure changes are **implementable** with available resources and technology

### Manage Expectations

Be transparent about what this requires:
- **Executive sponsorship** is non-negotiable
- **Cross-functional collaboration** will be necessary
- **Cultural change** takes time beyond process redesign
- **Short-term disruption** may occur during transition

## Common Patterns and Cases

### Pattern 1: The "Heroic Employee" Symptom

**Scenario**: Organization has star performers who "make things happen" through personal relationships and workarounds.

**Diagnosis**: The formal process is so broken that success requires bypassing it.

**Redesign Approach**:
- Map what the heroes actually do (not what the official process says)
- Incorporate their workarounds into the new standard process
- Remove obstacles that made heroics necessary

**Reference**: Andlawn Aerospace case in `references/《端到端流程》核心要点.md`

### Pattern 2: Multi-Department Hand-Off Hell

**Scenario**: Process ping-pongs between departments, each optimizing their piece while overall cycle time explodes.

**Diagnosis**: Functional silos with no end-to-end ownership.

**Redesign Approach**:
- Create "single point of contact" roles that coordinate across functions
- Or form "case teams" with members from all needed functions
- Measure end-to-end cycle time, not departmental metrics

**Reference**: Andlawn's Amore and Jane roles (客户单点联系人 & 运营单点联系人)

### Pattern 3: Death by Approval

**Scenario**: Every decision requires multiple layers of approval, yet approvals rarely catch real problems.

**Diagnosis**: Decision rights not aligned with knowledge; approvals are CYA theater.

**Redesign Approach**:
- Define clear decision rules so front-line can decide within bounds
- Reserve approvals only for genuine exceptions
- Replace pre-approvals with post-monitoring and audits

### Pattern 4: "Ready for AI" Assessment

**Scenario**: Organization wants to deploy AI/automation but doesn't know where to start.

**Diagnostic Questions**:
- Is the process clearly defined? (AI can't automate chaos)
- Which steps are rule-based vs. judgment-based?
- Where does the process break down currently?

**Redesign Approach**:
- First redesign the process to eliminate waste
- Then identify: What should AI do? What should humans do? What needs human+AI collaboration?
- Avoid automating broken processes ("paving cow paths")

**Reference**: See `references/process-redesign-guide.md` sections on technology enablement

## Reference Materials

This skill includes comprehensive reference documents. Load them as needed:

- **`references/《端到端流程》核心要点.md`** - Complete summary of Michael Hammer's book including theory, nine levers framework, PEMM model, and case studies. Read this for deep theoretical grounding.

- **`references/process-diagnostic-framework.md`** - Structured diagnostic approach with signals, questions, and analysis methods. Use when starting diagnosis phase.

- **`references/process-redesign-guide.md`** - Detailed redesign principles, workshop facilitation guide, and common patterns. Use during redesign phase.

## Output Templates

Generate these deliverables using provided templates:

- **`assets/diagnostic-questionnaire.md`** - Adapt this questionnaire to gather current state data
- **`assets/process-map-template.md`** - Document current and future state processes
- **`assets/redesign-canvas.md`** - Work through redesign decisions systematically
- **`assets/process-owner-charter.md`** - Formalize process ownership with clear responsibilities

## Critical Success Factors

Based on Hammer's research and case studies:

✅ **Executive Commitment** - Without top-level support, cross-functional change will stall

✅ **End-to-End Perspective** - Optimizing parts != optimizing the whole

✅ **Process Owner** - Someone must own outcomes, not just their departmental piece

✅ **Employee Participation** - Those doing the work know where the problems are

✅ **Patience** - Real transformation takes months/years, not weeks

✅ **Culture Change** - Mindset shift from "my department" to "customer value" is hardest but most important

✅ **Measurement** - Right metrics drive right behaviors; wrong metrics drive local optimization

## Anti-Patterns to Avoid

❌ **Just reorganizing** - Moving boxes on org chart doesn't change how work flows

❌ **Technology first** - Automating a bad process makes it fail faster

❌ **Local optimization** - Making one department faster while overall process slows

❌ **Planning paralysis** - Don't wait for perfect plan; start with pilot and iterate

❌ **Ignoring culture** - Process design is easy; changing behaviors is hard

❌ **Consultant dependency** - Build internal process management capability

## Skill Usage Tips

**Start with Understanding**: Before jumping to solutions, deeply understand the current state through conversation and mapping.

**Be Socratic**: Guide users to discover insights themselves through questions rather than lecturing.

**Stay Grounded**: Use real examples from their organization, not generic advice.

**Reference Authoritative Sources**: Cite specific cases or principles from Hammer's work when relevant.

**Create Artifacts**: Generate tangible deliverables (maps, canvases, charters) that users can use in their organization.

**Manage Scope**: If the problem is huge, help them choose one process to pilot rather than boiling the ocean.

## Related Methods

This skill complements but differs from:

- **Six Sigma**: Hammer's approach redesigns workflows; Six Sigma reduces variation in existing processes. Often use redesign first, then Six Sigma to optimize.

- **Lean**: Shares focus on eliminating waste but Hammer emphasizes radical redesign and end-to-end ownership more than Lean's continuous improvement.

- **Agile**: Agile is for product development workflows; this skill applies to operational processes (order fulfillment, customer service, etc.).

## Getting Started Checklist

When user engages this skill:

1. [ ] Clarify which process they want to improve (or help them identify it)
2. [ ] Understand their pain points and goals
3. [ ] Assess their readiness (executive support, resources, urgency)
4. [ ] Choose appropriate depth: Quick diagnosis vs. full redesign
5. [ ] Load relevant reference materials
6. [ ] Begin Phase 1 (Diagnose) unless they already have clear current state

---

*This skill is based on Michael Hammer's "Faster Cheaper Better: The 9 Levers for Transforming How Work Gets Done" and related Business Process Reengineering (BPR) principles.*
