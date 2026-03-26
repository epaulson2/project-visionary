# Project Visionary — Research Plan

**Goal:** Build an AI agent system that can take a raw idea and mature it into a fully realized product — not just writing code, but thinking like a product visionary. Codify the founder's thinking patterns from the Elderle and QCR projects into a reusable intelligence layer.

---

## Table of Contents

1. [The Core Insight](#the-core-insight)
2. [Phase 1: Psychological Profiling of Project Evolution](#phase-1-psychological-profiling)
3. [Phase 2: Framework Research](#phase-2-framework-research)
4. [Phase 3: Pattern Extraction](#phase-3-pattern-extraction)
5. [Phase 4: Agent Architecture Design](#phase-4-agent-architecture-design)
6. [Phase 5: Validation](#phase-5-validation)

---

## The Core Insight

The most valuable thing about the Elderle and QCR development process isn't the final product — it's the **transformation journey**. How a "companion AI for elderly care" became a system with therapeutic stages, personality adaptation, crisis detection, and a knowledge graph. How a "Charlotte car tools website" became a gamified national platform with mascot-guided experiences, competitive gaming, and progressive local intelligence.

The key is not just WHAT we decided, but HOW we got there:
- What triggered new ideas (a user complaint? a research paper? a competitor analysis? a tangential conversation?)
- How tangential ideas became core features (gamification started as "nice to have" and became the retention architecture)
- When the founder pushed back and WHY (visual quality standards, deployment verification, user testing requirements)
- How scope expanded intelligently vs how it got out of control
- The pattern of: raw idea → research → cross-reference → mockup → founder review → iterate → implement

**The product we're building is an agent system that can replicate this thinking process.**

---

## Phase 1: Psychological Profiling of Project Evolution

### What to research before starting:

1. **Cognitive frameworks for creative product thinking:**
   - Design Thinking (Stanford d.school) — empathize, define, ideate, prototype, test
   - Jobs-to-Be-Done (JTBD) theory — Clayton Christensen's framework for understanding WHY users hire products
   - First Principles Thinking — Elon Musk's approach to decomposing problems
   - Lateral Thinking — Edward de Bono's techniques for creative leaps
   - Effectuation Theory — how expert entrepreneurs think (Saras Sarasvathy's research)

2. **Psychological profiling methodologies:**
   - Big Five personality traits applied to decision-making style
   - Cognitive style analysis — intuitive vs analytical, convergent vs divergent
   - Myers-Briggs as a lens for product decisions (not as personality typing, but as decision pattern recognition)
   - Kahneman's System 1/System 2 thinking — when does the founder use fast intuition vs slow analysis?

3. **Git archaeology as psychological evidence:**
   - Commit message evolution (how language changes as vision matures)
   - Document version history (how specs transform over iterations)
   - Feature branching patterns (what gets explored vs what gets shipped)
   - Plan document archaeology (V1 → V2 → V3 → V4.2 — what changed and why)
   - Research document evolution (what external ideas triggered what internal changes)

### Approach for Elderle project profiling:

1. Read all git history chronologically: `git log --all --oneline --date-order`
2. Identify inflection points — commits where the project direction shifted
3. For each inflection point, read:
   - The commit message and diff
   - Any associated plan documents that changed
   - The conversation context (if available in session logs)
4. Map: trigger event → idea formation → research → decision → implementation
5. Catalog the tangential ideas that emerged:
   - Therapeutic stage progression (SPT)
   - Crisis detection
   - HippoRAG knowledge graph
   - Voice adaptation for elderly
   - Personality profiling
   - Joyful content system
   - Synthetic user simulation
   - Neo4j relationship modeling

### Approach for QCR project profiling:

1. Same git archaeology approach
2. Key transformation moments to trace:
   - Charlotte-only → national expansion decision
   - Tools-only → content + news + community platform
   - Static tool results → Quinn/Torque narrative flow
   - Utility app → gamified experience (Octalysis integration)
   - Website-only → native app with competitive gaming
   - Single-tier → preview/full/paid tier architecture
   - The SDLC system evolution itself — from documentation-only to mechanical enforcement

### Deliverable:
A **Founder Decision Profile** document that captures:
- Decision-making patterns (when does the founder trust intuition vs demand research?)
- Quality standards (what triggers "this isn't good enough"?)
- Scope management philosophy (when to expand vs when to focus)
- User empathy patterns (how does the founder think about end users?)
- Technical taste (what architectures/approaches appeal vs what gets rejected?)
- The "yes and" moments — when a suggestion triggered an even bigger idea

---

## Phase 2: Framework Research

### Academic and industry research needed:

1. **Product visionary profiling:**
   - Steve Jobs's product development methodology (from Isaacson biography + HBR cases)
   - Jeff Bezos's "working backwards" approach (press release first)
   - How Stripe, Notion, and Linear built product cultures
   - YC's approach to idea maturation (Paul Graham essays on startups)

2. **AI agent architectures for creative reasoning:**
   - Chain-of-Thought prompting for product decisions
   - Tree-of-Thought for exploring product possibilities
   - Debate frameworks (Red Team / Blue Team for product ideas)
   - Constitutional AI principles applied to product values
   - Multi-agent systems for simulating stakeholder perspectives

3. **Knowledge management for product intelligence:**
   - How to encode "taste" in a system (aesthetic preferences, quality standards)
   - Tacit knowledge externalization (Nonaka's SECI model)
   - Organizational memory systems
   - Case-based reasoning (using past decisions to inform future ones)

4. **SDLC agent pipeline research:**
   - Existing frameworks: Devin, SWE-Agent, AutoGPT, CrewAI, LangGraph
   - What works and what doesn't in autonomous coding agents
   - The gap between "writes code" and "makes good product decisions"
   - How to maintain quality standards across autonomous agents

### Deliverable:
A **Framework Synthesis** document mapping the most useful concepts from each field to the Project Visionary architecture.

---

## Phase 3: Pattern Extraction

### From the profiling (Phase 1) and frameworks (Phase 2), extract:

1. **Decision Templates** — reusable patterns for product decisions:
   - "When a user says X, research Y before implementing Z"
   - "When quality is below threshold, create mockups before code"
   - "When scope expands, split into phased briefs before proceeding"

2. **Taste Vectors** — encoded preferences:
   - Visual quality thresholds (dark themes, specific color palettes, mascot integration)
   - Content quality thresholds (research depth, avatar alignment, persona specificity)
   - Technical quality thresholds (SDLC compliance, gate passage, E2E verification)

3. **Idea Maturation Sequences** — the stages an idea goes through:
   - Raw concept → research document → cross-reference with existing → SDLC review → founder review → iterate → implement → verify
   - With decision gates at each stage

4. **Anti-Patterns** — what NOT to do:
   - Don't implement without founder mockup review
   - Don't declare done without deployment
   - Don't skip E2E testing
   - Don't use animation assets for publishing
   - Don't make things Charlotte-specific when going national

### Deliverable:
A **Pattern Library** that can be loaded as context for any agent in the system.

---

## Phase 4: Agent Architecture Design

### The agent roles needed:

1. **Visionary Agent** — generates ideas, sees opportunities, proposes features
   - Loaded with: founder decision profile, taste vectors, market knowledge
   - Output: feature proposals, moonshot ideas, pivot suggestions

2. **Research Agent** — deep dives into any topic
   - Loaded with: academic research standards, industry analysis frameworks
   - Output: 1000+ line research documents with citations

3. **Strategist Agent** — plans implementation sequences
   - Loaded with: phasing patterns, dependency management, scope control
   - Output: phased implementation plans with gates

4. **Critic Agent** — challenges ideas and finds weaknesses
   - Loaded with: SDLC rules, anti-patterns, risk frameworks
   - Output: SDLC reviews, risk registers, moonshot ideas

5. **Builder Agents** — implement code (existing pattern)
   - Loaded with: codebase context, coding standards, test requirements
   - Output: working code with tests

6. **Verifier Agent** — ensures quality before declaring done
   - Loaded with: gate definitions, E2E test suites, deployment procedures
   - Output: verified deployment with evidence

7. **Founder Simulator** — models the founder's likely reaction
   - Loaded with: founder decision profile, past feedback, quality standards
   - Output: "The founder would probably say..." predictions

### The pipeline:
```
Idea → Visionary (expand) → Researcher (validate) → Strategist (plan)
→ Critic (challenge) → Founder Simulator (predict reaction)
→ [Founder Review] → Builder (implement) → Verifier (deploy + test)
```

### Deliverable:
An **Agent Architecture Specification** with prompts, context loading, handoff protocols, and quality gates.

---

## Phase 5: Validation

### Test the system by:

1. **Retrospective test** — give the system a past idea (e.g., "gamification for QCR") and see if it produces similar output to what we actually built
2. **Novel test** — give the system a new idea neither project has explored and evaluate the quality of its output
3. **Cross-domain test** — give the system an idea from a completely different industry and see if the thinking patterns transfer

### Success criteria:
- The system's output is indistinguishable from human founder-level thinking in a blind review
- The system catches quality issues the founder would catch
- The system generates ideas the founder finds genuinely exciting
- The system's SDLC pipeline produces deployable code with passing gates

---

## Immediate Next Steps

1. **Start Phase 1** — Git archaeology on both projects. This is the foundation everything else builds on.
2. **Parallel: Phase 2 research** — Begin framework research while profiling is in progress.
3. **Estimated timeline:** Phase 1-2 (2-3 weeks), Phase 3 (1 week), Phase 4 (2 weeks), Phase 5 (1 week)

---

## Open Questions for Founder

1. Are there specific decisions from either project that you consider your BEST product thinking? Moments where you're particularly proud of the direction we took?
2. Are there decisions you'd make differently in hindsight?
3. How much of your thinking comes from your industry background vs intuition vs research?
4. Should this system be able to operate fully autonomously, or always include a founder review checkpoint?
5. Do you want the Founder Simulator agent to be conservative (never approve what you wouldn't) or slightly ambitious (occasionally suggest things you might not have thought of)?
