# Project Visionary: Master Document

## The System That Thinks Like the Founder

**Version:** 1.0
**Date:** 2026-03-26
**Status:** Complete synthesis of all research phases
**Source corpus:** QCR Evolution Analysis, Elderle Evolution Analysis, Framework Synthesis (1,945+ lines of academic research), Research Plan

---

## Table of Contents

1. [Executive Summary](#1-executive-summary)
2. [The Founder's Cognitive Profile](#2-the-founders-cognitive-profile)
   - 2.1 [Cross-Project Decision Patterns](#21-cross-project-decision-patterns)
   - 2.2 [Mental Models](#22-mental-models)
   - 2.3 [Creative Patterns](#23-creative-patterns)
   - 2.4 [Quality Standards](#24-quality-standards)
   - 2.5 [Scope Philosophy](#25-scope-philosophy)
   - 2.6 [How the Founder Differs from Typical PMs and Engineers](#26-how-the-founder-differs-from-typical-pms-and-engineers)
   - 2.7 [The Three Signature Patterns](#27-the-three-signature-patterns)
   - 2.8 [Big Five Personality Estimate](#28-big-five-personality-estimate)
   - 2.9 [System 1 / System 2 Profile](#29-system-1--system-2-profile)
3. [The Idea Maturation Process](#3-the-idea-maturation-process)
   - 3.1 [The Common Sequence](#31-the-common-sequence)
   - 3.2 [The Role of Research](#32-the-role-of-research)
   - 3.3 [The Role of Tangential Thinking](#33-the-role-of-tangential-thinking)
   - 3.4 [The Role of Quality Gates](#34-the-role-of-quality-gates)
   - 3.5 [The Role of Mockups and Visual Review](#35-the-role-of-mockups-and-visual-review)
   - 3.6 [How Scope Expands and Contracts](#36-how-scope-expands-and-contracts)
   - 3.7 [The Punctuated Equilibrium Model](#37-the-punctuated-equilibrium-model)
4. [The Agent Architecture](#4-the-agent-architecture)
   - 4.1 [Architecture Overview](#41-architecture-overview)
   - 4.2 [Visionary Agent](#42-visionary-agent)
   - 4.3 [Research Agent](#43-research-agent)
   - 4.4 [Strategist Agent](#44-strategist-agent)
   - 4.5 [Critic Agent](#45-critic-agent)
   - 4.6 [Builder Agents](#46-builder-agents)
   - 4.7 [Verifier Agent](#47-verifier-agent)
   - 4.8 [Founder Simulator](#48-founder-simulator)
   - 4.9 [The Pipeline](#49-the-pipeline)
   - 4.10 [Quality Gates Between Agents](#410-quality-gates-between-agents)
   - 4.11 [Technical Implementation](#411-technical-implementation)
5. [The Pattern Library](#5-the-pattern-library)
   - 5.1 [Decision Templates](#51-decision-templates)
   - 5.2 [Anti-Patterns](#52-anti-patterns)
   - 5.3 [Taste Vectors](#53-taste-vectors)
   - 5.4 [Scope Management Rules](#54-scope-management-rules)
   - 5.5 [The Founder Approval Test](#55-the-founder-approval-test)
6. [The Founder Simulator Specification](#6-the-founder-simulator-specification)
   - 6.1 [Purpose and Operating Model](#61-purpose-and-operating-model)
   - 6.2 [Training Data](#62-training-data)
   - 6.3 [Confidence Calibration](#63-confidence-calibration)
   - 6.4 [The Core Question](#64-the-core-question)
   - 6.5 [Decision Mode Switching](#65-decision-mode-switching)
   - 6.6 [Calibration Loop](#66-calibration-loop)
7. [Implementation Roadmap](#7-implementation-roadmap)
   - 7.1 [Phase 1: Encode the Cognitive Profile](#71-phase-1-encode-the-cognitive-profile)
   - 7.2 [Phase 2: Build the 7-Agent Pipeline](#72-phase-2-build-the-7-agent-pipeline)
   - 7.3 [Phase 3: Train the Founder Simulator](#73-phase-3-train-the-founder-simulator)
   - 7.4 [Phase 4: Validate with Retrospective Tests](#74-phase-4-validate-with-retrospective-tests)
   - 7.5 [Phase 5: Deploy on a New Project](#75-phase-5-deploy-on-a-new-project)
8. [Cross-Project Insights](#8-cross-project-insights)
   - 8.1 [Ideas That Transferred Between Elderle and QCR](#81-ideas-that-transferred-between-elderle-and-qcr)
   - 8.2 [Patterns That Generalize Beyond These Two Projects](#82-patterns-that-generalize-beyond-these-two-projects)
   - 8.3 [Domain Transfer Test](#83-domain-transfer-test)
9. [Open Questions for the Founder](#9-open-questions-for-the-founder)
10. [Appendices](#10-appendices)
    - A: [Full Decision Pattern Catalog](#appendix-a-full-decision-pattern-catalog)
    - B: [Framework-to-Agent Mapping Table](#appendix-b-framework-to-agent-mapping-table)
    - C: [Quality Gate Definitions](#appendix-c-quality-gate-definitions)
    - D: [Taste Vector Specifications](#appendix-d-taste-vector-specifications)

---

## 1. Executive Summary

### What Project Visionary Is

Project Visionary is a system designed to replicate the founder's product thinking -- not just writing code, but the entire upstream process: recognizing opportunities, researching deeply, making creative leaps, enforcing quality standards, managing scope, and maintaining product vision coherence across months of development.

The most valuable asset in the Elderle and QCR projects was never the final product. It was the **transformation journey** -- how a "medication reminder app" became a sophisticated AI companion platform with therapeutic stages, crisis detection, and synthetic user testing, and how a "Charlotte car tools website" became a gamified national automotive intelligence platform with mascot-guided experiences. Project Visionary captures the thinking process that drove those transformations and encodes it into a reusable system.

### What We Learned

We analyzed three bodies of evidence:

**1. The QCR Evolution** (49 strategic documents, 100+ commits, March 7-26, 2026)
- Six pivots traced from blog idea to Local Intelligence Media Franchise System
- Nine cognitive signature traits identified
- Eight decision patterns extracted
- Forty-two key quotes cataloged as taste evidence

**2. The Elderle Evolution** (803 .docx, 1,554 .md, 145 .pdf, 213 .py files, October 2025 - March 2026)
- Seven pivots traced from FlutterFlow medication tracker to AI companion platform
- Seven psychological traits identified
- Seven decision patterns extracted
- Cross-pollination with QCR documented in both directions

**3. The Framework Synthesis** (1,945 lines of academic and industry research)
- Nine cognitive frameworks evaluated (Effectuation, JTBD, Blue Ocean, Design Thinking, First Principles, Lateral Thinking, Working Backwards, Paul Graham, Product Cultures)
- Seven psychological profiling methodologies applied
- Six AI agent architecture patterns analyzed (CoT, ToT, MAD, CAI, Reflexion, Multi-Agent Frameworks)
- Five knowledge management models mapped to the system
- Five open research gaps identified

### The Core Findings

**Finding 1: The founder has a consistent cognitive signature that appears across both projects.** The same patterns -- knowledge infrastructure first, trust as engineering, emotional design as specification, scope expansion followed by ruthless narrowing -- appear in QCR and Elderle despite the projects being in completely different domains. This consistency means the patterns are learnable and encodable.

**Finding 2: The most relevant academic framework is Effectuation Theory.** The founder's actual decision-making aligns most closely with how expert entrepreneurs think: start with available means, limit downside, leverage surprises, build partnerships, and shape the future rather than trying to predict it. This should be the default reasoning mode for the Visionary Agent.

**Finding 3: The biggest technical gap is encoding "taste."** Current AI systems can execute instructions but cannot make the quality judgments that separate good products from great ones. The founder's consistent standard -- "this isn't good enough" -- is the most important thing to encode and the hardest.

**Finding 4: The system should be a hybrid, not fully autonomous.** Academic research on creativity confirms that AI excels at combinatorial creativity (generating novel combinations) while humans provide transformational creativity (changing the rules) and evaluative judgment (selecting the best option). The founder remains in the loop as the final quality gate.

### The Path Forward

The system is a 7-agent pipeline: Visionary Agent (idea generation, loaded with the cognitive profile), Research Agent (deep-dive validation), Strategist Agent (phased planning), Critic Agent (SDLC review and risk analysis), Builder Agents (implementation), Verifier Agent (E2E testing and deployment), and Founder Simulator (predicting founder reactions for auto-approval vs. escalation).

Implementation spans five phases over approximately 10 weeks:
1. Encode the cognitive profile into system prompts (2 weeks)
2. Build the 7-agent pipeline with handoff protocols (3 weeks)
3. Train the Founder Simulator on historical decisions (2 weeks)
4. Validate with retrospective tests (1 week)
5. Deploy on a new project and compare output quality (2 weeks)

---

## 2. The Founder's Cognitive Profile

This section synthesizes the decision patterns from both the QCR and Elderle evolution analyses. Patterns that appear in both projects are the strongest signals -- they represent the founder's genuine cognitive wiring, not project-specific behavior.

### 2.1 Cross-Project Decision Patterns

These patterns appear in **both** Elderle and QCR, making them the most reliable indicators of how the founder thinks:

#### Pattern 1: Knowledge Infrastructure First

**In QCR:** The Automotive Intelligence Blueprint (73,000 characters, written on day one) establishes: "Build the knowledge engine first, then let media, community, AI, and commerce sit on top of it." Six-layer knowledge base model, five-tier source confidence hierarchy, graph-minded schema design before a single article template exists.

**In Elderle:** The knowledge base (50,279 drugs, 10,966 supplement-drug interactions, Beers Criteria, STOPP/START criteria, Neo4j graph with 52,980 nodes) was built before the consumer-facing experience was refined. The RAG system architecture preceded the conversational AI features.

**The Pattern:** The founder never starts with "what pages should we build?" or "what features should the app have?" The founder starts with "what does the system need to *know*, and how should that knowledge be organized?" The durable asset is always the structured knowledge underneath, not the surfaces on top. Surfaces are disposable; knowledge compounds.

**Effectuation Mapping:** This aligns with Effectuation's Bird-in-Hand principle -- start with what you know and build outward from knowledge assets.

#### Pattern 2: Research Before Vision, Not After

**In QCR:** Competitor analysis came before the product vision. The affiliate market landscape was analyzed before the monetization strategy. The franchise niche recommendations were ranked using weighted criteria before a next-niche was chosen. Every major QCR decision was preceded by structured research.

**In Elderle:** The Value Ladder emerged from studying direct-response marketing economics. The freemium pivot was grounded in the "53M unpaid caregivers searching for free answers" market analysis. The voice stack pivoted based on cost-per-minute analysis ($0.90 vs. $0.01222). Even Crystal Wright's recruitment was a research-driven decision (clinical credibility gap analysis).

**The Pattern:** The founder does not build and then justify. The founder researches and then builds. But this is not analysis paralysis -- the research is done at velocity. The QCR competitive analysis and the 73,000-character Architecture Blueprint were produced on the same day. The Elderle value ladder appeared within weeks of the initial handoff doc.

**Framework Mapping:** This contradicts pure Paul Graham philosophy ("launch fast, iterate") but aligns with Working Backwards (Bezos) -- understand the customer and market deeply before building. The founder resolves this tension by researching fast, not skipping research.

#### Pattern 3: Architecture Before Features

**In QCR:** The knowledge base schema before the first article. The character operating system (15 personality sliders, Big Five anchoring, episodic memory with decay curves) before the first Torque & Quinn script. The Scene Graph relationships before the first event page.

**In Elderle:** The Three-Layer Reliability Pattern before the first Jessica conversation. The RAG architecture before the chatbot UI. The 6-layer AI Guardrails System before the next round of feature development. The Corporate Encyclopedia (9-section BRD structure) before implementation.

**The Pattern:** When the founder sees a feature to build, the first instinct is to ask: "What architecture makes this feature AND its successors possible?" Building a one-off feature feels wasteful; building an architecture that enables a family of features feels right. This is the "characters are systems, not assets" principle generalized: everything is a system, nothing is an asset in isolation.

**Framework Mapping:** This is First Principles Thinking applied to architecture -- decompose to fundamentals and rebuild from the ground up, ensuring the foundation supports the full vision.

#### Pattern 4: Emotional Design as Engineering Specification

**In QCR:** "Entertainment first -- if it's not fun to read, it doesn't matter how accurate it is." Torque and Quinn have parameterized personality sliders and a structured relationship state (warmth score, teasing balance, trust score). The mascot correction-resolve rule: "Never leave ambiguous misinformation hanging just because it sounds entertaining." Emotional quality is not marketing copy; it is a checkable invariant.

**In Elderle:** Jessica's Emotional Reciprocity Engine maintains a simulated emotional state that evolves based on user interactions. When a senior tells the same story for the third time, Jessica must "treat it as a new story, show enthusiasm, do NOT correct them." The dignity of elderly users is specified as a technical requirement with the same precision as database schemas. The Belt System gamification is designed not for engagement metrics but for "emotional validation of unpaid work that society ignores."

**The Pattern:** The founder treats empathy, dignity, warmth, and entertainment as **engineering requirements**, not marketing aspirations. These are not "nice to have" UX considerations -- they are specified with parameters, thresholds, and testable criteria just like any technical specification. This is the most distinctive trait in the founder's cognitive profile and the one most likely to be lost in a typical AI agent system.

**Framework Mapping:** This extends JTBD theory into implementation: the emotional and social dimensions of jobs are given equal engineering weight as the functional dimensions.

#### Pattern 5: Trust as Engineering Constraint

**In QCR:** Source confidence hierarchies (government > official operators > licensed commercial > editorial > community). Claim-level provenance. Methodology boxes on recommendation pages. "Any monetized page should still be worth publishing if every affiliate link were removed."

**In Elderle:** Clinical safety databases with verified sources. Crystal Wright (RN, BSN) as clinical credibility anchor. FDA drug and supplement recall data with Class I/II classification. Knowledge quality metadata for 13,921 entries.

**The Pattern:** Trust is implemented in data structures, not in brand voice guides. It is an architectural constraint that applies to every piece of content, every recommendation, and every AI-generated response. The founder never says "we should seem trustworthy" -- the founder says "here is the data structure that enforces trustworthiness."

#### Pattern 6: Scope Expansion Followed by Ruthless Narrowing

**In QCR:** The Architecture Blueprint imagines a 20-chapter knowledge platform with national expansion. Then the MVP Plan says: "Build only the layers that directly improve trust, lead generation, local relevance, or data capture in the first 90 to 120 days." The MVP is a repair advisor with 15 founding shops, not the full Garage OS.

**In Elderle:** The Character Universe envisions 6 AI characters with a Director AI orchestration layer, transmedia strategy, and a 20-week content roadmap. Then the founder pivots to quality consolidation: 6-layer guardrails, dead code removal, wiring the actual pipeline. The ambitious vision is not abandoned -- it is parked while the foundation is hardened.

**The Pattern:** The founder allows vision to expand without constraint during ideation, then applies disciplined narrowing when moving to execution. Both impulses are genuine. The formula is: **think in systems, build in slices.** The full vision lives in documents; the next 90 days live in code.

**Effectuation Mapping:** This is the Affordable Loss principle -- invest what you can afford to lose in the next increment, while maintaining the option to pursue the full vision later.

#### Pattern 7: Document Everything as Handoff Spec

**In QCR:** 49 strategic documents, many exceeding 20,000 characters. The Master BRD alone is 49,000 characters. Explicitly structured to be "readable by business stakeholders and machine-assisted development workflows."

**In Elderle:** 803 .docx files, 1,554 .md files. Nearly every major document is titled or formatted as a "handoff." The Corporate Encyclopedia with 9 numbered sections. The CLAUDE.md files, MEMORY.md system, session logging protocol. Documents written to be consumed by both human stakeholders and AI development workflows.

**The Pattern:** Documentation is not overhead. It is the intellectual infrastructure of the company. It is simultaneously a thinking tool (writing forces clarity), a delegation instrument (exhaustive specs enable AI execution), and a knowledge asset (the documents persist as institutional memory). The founder uses strategic documentation as the primary mechanism for converting tacit knowledge into explicit knowledge -- exactly what Nonaka's SECI model calls "externalization."

### 2.2 Mental Models

Based on cross-referencing both projects, these are the founder's operating mental models:

#### "Structured Knowledge Underneath, Multiple Surfaces on Top"

This is the single most important mental model. It appears in:
- QCR: Knowledge engine first, then media/community/AI/commerce
- Elderle: Knowledge base first, then companion/voice/content
- QCR Franchise Model: Core platform + niche pack + market pack + brand voice
- Elderle Character Universe: Character operating system, then individual character instances

The mental model is: **the infrastructure is the product; the user-facing experience is a view.** This has profound implications for how the system should generate product proposals -- always start with "what knowledge or capability does this require underneath?" before "what does the user see?"

#### "Dual Identity: Brand Externally, Platform Internally"

In both projects, the founder maintains two narratives simultaneously. QCR is externally "Charlotte's automotive intelligence network" and internally "a reusable knowledge and recommendation platform." Elderle is externally "your AI caregiving companion" and internally "a clinical safety knowledge base with companion AI surfaces."

The mental model: **every product is simultaneously a brand story for users and a platform capability for the business.** Product proposals that only address one narrative are incomplete.

#### "Monetization Follows Value, Never Leads"

The QCR founding-partner model: free leads, no commissions -- prove value to shops before charging. The Elderle freemium model: affiliate engine monetizes free users while providing genuine value. The affiliate philosophy: "useful without links."

The mental model: **earn the right to charge by delivering undeniable value first.** This is not altruism; it is strategy. Free value creates distribution, distribution creates data, data creates defensibility, defensibility enables monetization.

#### "Family Meaning and Business Meaning Are Inseparable"

QCR is explicitly structured as a family business where "each person does what they're already good at" -- Dante's detailing ambitions, Tiana's media portfolio, Crystal's operations, Eric's AI products. Elderle is motivated by the personal experience of elder caregiving: "The guilt of not being there is exhausting."

The mental model: **the best products solve problems the founder personally cares about.** This is Paul Graham's "organic ideas" principle. The system should not propose features that do not connect to a human motivation.

#### "Ranked Lists with Weighted Criteria"

The QCR franchise niche recommendations used nine weighted criteria. Elderle's monetization tiers have per-minute voice cost calculations. Every significant decision is structured as a multi-dimensional ranking.

The mental model: **decisions are not intuitive coin flips; they are structured analyses expressed as rankings.** But the criteria themselves are chosen intuitively -- the founder's System 1 selects what matters, then System 2 ranks the options.

### 2.3 Creative Patterns

#### The Creative Leap Sequence

The founder's creative process follows a consistent three-step sequence visible in both projects:

1. **Build something specific** -- QCR automotive knowledge engine, Elderle medication tracker
2. **Recognize the general pattern** -- QCR: "this is a local intelligence platform, not just automotive." Elderle: "this AI intake can power all products, not just data collection."
3. **Propose the abstract system** -- QCR: Local Intelligence Media Franchise System for any niche. Elderle: Character Universe where any AI character can have Jessica's inner world.

**This is the "build specific, recognize general, propose abstract" creative move.** The abstraction does not come from theory; it comes from recognizing what was accidentally general in the specific implementation. This means the system should never propose abstract solutions first -- it should build specific solutions and then look for generalization opportunities.

#### Tangential Thinking as Feature Discovery

Both projects show ideas emerging from tangential connections rather than roadmap planning:

**QCR tangential discoveries:**
- Gamification emerged from tools (utility > engagement > competition > gaming)
- Local news emerged from social-sniffing (monitoring > demand-sensing > news)
- Community impact emerged from community features (engagement > charitable)
- Franchise model emerged from architecture (specific > general > abstract)
- Traffic utility emerged from events (calendar > prediction > route planning)
- Education products emerged from knowledge base (answers > courses)

**Elderle tangential discoveries:**
- Jessica the AI companion emerged from the value ladder's personalization engine
- Crisis detection emerged from emergency protocols in companion design
- Synthetic users emerged from QA needs for testing AI conversations
- Character Universe emerged from asking "what if ALL characters had inner lives?"
- Elderle Circles emerged from the GoHighLevel community concept

**The Pattern:** The best features are not planned. They emerge when the founder sees a capability built for one purpose and asks: "What else could this do?" The system should build a "tangential idea generator" that periodically examines existing capabilities and asks this question.

**Effectuation Mapping:** This is the Lemonade Principle -- turn the unexpected into the profitable. The system should not just tolerate surprises; it should actively seek to exploit them.

#### The "Yes, And" Escalation

In both projects, the founder does not simply accept or reject ideas. The characteristic response to a good idea is to escalate it:
- QCR: "Add mascots" becomes "build a character operating system with personality sliders and episodic memory"
- Elderle: "Add a chatbot" becomes "build an AI companion with emotional reciprocity and relationship evolution"
- QCR: "Monetize with affiliates" becomes "build Redline Research with methodology, scenario analysis, and evidence records"
- Elderle: "Test with QA" becomes "build synthetic users with Big Five personality profiles and SPT stages"

The "yes, and" move is always in the direction of **more architecture, not more features.** The founder does not add more buttons; the founder deepens the underlying system.

### 2.4 Quality Standards

#### What Triggers "This Isn't Good Enough"

Cross-referencing both projects, these are the consistent quality triggers:

**1. Shallow content over structured knowledge.**
- QCR: "If the layer is shallow, every surface built on top of it will eventually feel shallow too."
- Elderle: The L3 audit revealed 40% of the architecture was dead code -- features computed but never used. This triggered complete remediation.

**2. Generic output without local/personal specificity.**
- QCR: "Do not lead with generic national car news with no local angle just to fill the feed."
- Elderle: AI-generated content must be personalized to the specific caregiver's situation, not generic health advice.

**3. Claiming done without verification.**
- QCR: SDLC reviews required before implementation, gate bypass audits, pre-mortem documents.
- Elderle: "ALWAYS verify ACTUAL output, never test isolated components and declare victory." The December 28, 2025 triple incident triggered 6-layer guardrails.

**4. Trust erosion through monetization.**
- QCR: "Any monetized page should still be worth publishing if every affiliate link were removed."
- Elderle: Clinical credibility requires verified sources, not just plausible AI text.

**5. Character or visual drift.**
- QCR: Torque & Quinn correction-resolve rule: "Never leave ambiguous misinformation hanging just because it sounds entertaining."
- Elderle: "NEVER regenerate full scene images. Composite overlays onto existing bases. Regeneration causes character/style drift."

**6. Feature without architecture.**
- QCR: The character operating system before any script. The Scene Graph before any event page.
- Elderle: The RAG architecture before the chatbot UI. The guardrails system before new features.

#### Quality Expressed as Non-Negotiable Principles

From both projects, these principles are non-negotiable -- the system must enforce them:

1. **Every feature must answer a real user need.** If it does not make someone's life better, it does not ship.
2. **Every fact must trace to a source with confidence and freshness.** Unsourced claims are rejected.
3. **Every recommendation must be useful without monetization links.** Anti-sleaze is a checkable invariant.
4. **Done means deployed, tested, and verified with evidence.** "Code complete" is not done.
5. **Entertainment and dignity first.** Technical accuracy without emotional warmth fails the standard.
6. **Architecture before features.** One-off implementations without reusable foundations are rework.
7. **Local/personal specificity is the moat.** Generic content that could appear on any site fails.
8. **Trust is engineered, not marketed.** Trust must be verifiable in the data model.

### 2.5 Scope Philosophy

#### When the Founder Expands Scope

The expansion trigger is always **structural leverage** -- when adding a new layer would make multiple existing features smarter simultaneously.

From QCR: "Cross-system leverage" is an explicit prioritization criterion. If adding a Reputation Graph would improve Build Match, Redline Research, event recommendations, and local business pages all at once, it gets elevated. If it only helps one surface, it gets deprioritized.

From Elderle: Jessica's inner world architecture was justified because it powered companion conversations, crisis detection, proactive engagement, and synthetic user testing simultaneously.

Other expansion triggers common to both:
- **Audience realization:** Discovering the system can serve more users than originally planned (QCR: enthusiasts + general drivers. Elderle: caregivers + seniors + families + physicians).
- **Architecture generalization:** Looking at a completed system and realizing it is niche-agnostic (QCR franchise model, Elderle character universe).
- **Monetization layer recognition:** Identifying a new revenue mechanism that sits on existing infrastructure (QCR: five separate monetization documents. Elderle: seven pricing tiers plus affiliate engine).

#### When the Founder Focuses

The focus trigger is always **the transition from architecture to execution.** The switch is sharp and abrupt:

From QCR: The Blueprint imagines 20 chapters. The MVP Plan says 90 days, repair advisor, 15 shops.
From Elderle: The Character Universe imagines 6 characters with Director AI. The quality consolidation phase says: remove dead code, wire what exists, verify with evidence.

The focusing principle: **"Do not delay launch waiting for the complete long-range ecosystem."** The full vision lives in documents. The next 90 days live in code.

#### The Scope Formula

**Think in systems, build in slices.**

The founder can hold the full vision (franchise system with four niches, character universe with six AI personalities, knowledge graph with 91,276 relationships) while shipping the minimum credible wedge (repair advisor with 15 shops, Jessica with therapeutic stages, hybrid search with reranking).

### 2.6 How the Founder Differs from Typical PMs and Engineers

| Dimension | Typical PM | Typical Engineer | This Founder |
|-----------|-----------|-----------------|-------------|
| Starting point | User stories | Technical requirements | Knowledge architecture |
| First deliverable | PRD or feature spec | Prototype code | Exhaustive strategic document (20,000+ chars) |
| Quality definition | "Users are satisfied" | "Tests pass" | "Would I be proud to show this?" + verified deployment |
| Scope response | Negotiate with stakeholders | Estimate effort | Expand the architecture, then ruthlessly narrow execution |
| Monetization thinking | Feature → pricing | Not their concern | Layered revenue architecture where each layer preserves trust |
| Emotional design | UX consideration | Not their concern | Engineering specification with parameters and thresholds |
| Documentation | Necessary overhead | Something to avoid | Primary thinking tool and delegation instrument |
| Feature evaluation | "Does the data support it?" | "Is it technically elegant?" | "Does this create structural leverage across the whole system?" |
| Timeframe | Quarter-by-quarter | Sprint-by-sprint | Simultaneously 5-year vision and 90-day execution |
| Risk response | Mitigate | Avoid | Leverage (Effectuation's Lemonade principle) |

### 2.7 The Three Signature Patterns

These three patterns are the founder's unique creative moves -- they appear repeatedly in both projects and are the most important things to encode:

#### 1. "Knowledge Infrastructure Underneath, Multiple Surfaces on Top"

The durable asset is never the surface. The durable asset is the structured knowledge underneath. This principle governs every architectural decision in both projects. When the system evaluates a feature proposal, the first question must be: "What knowledge layer does this require, and does that layer already exist or would we need to build it?"

#### 2. "Emotional Design as Engineering Specification"

Empathy, dignity, warmth, and entertainment are not UX considerations -- they are engineering requirements with parameters, thresholds, and testable criteria. Jessica's repetition-handling rule ("treat it as a new story") has the same specificity as a database constraint. Torque's personality sliders have the same precision as an API schema. When the system generates a product proposal, emotional quality must be specified with the same rigor as technical quality.

#### 3. "Build Specific, Recognize General, Propose Abstract"

The characteristic creative move: build something specific (automotive knowledge engine), recognize what is accidentally general (local intelligence platform), propose the abstract system (franchise model for any niche). The abstraction never comes from theory; it comes from recognizing generality in a working specific implementation. The system should never propose abstract architectures first -- it should build specific solutions and then periodically ask: "What is general about what we just built?"

### 2.8 Big Five Personality Estimate

Based on behavioral evidence across both projects:

| Trait | Estimated Score | Evidence |
|-------|---------------|----------|
| **Openness** | Very High (90+) | Constant creative leaps, cross-domain connections (gamification from tools, franchise from architecture), willingness to explore radically different product directions within weeks |
| **Conscientiousness** | Very High (85+) | 49 QCR strategic documents in 3 weeks, 803 Elderle .docx files, exhaustive specifications, 6-layer guardrails, SDLC enforcement, evidence-based completion standards |
| **Extraversion** | High (75+) | Family business orientation, partnership-first monetization, community-over-audience philosophy, stakeholder reveal format |
| **Agreeableness** | Context-Modulated (60) | Generous with users and partners (free leads, dignity-first design), sharp with mediocre work ("this isn't good enough"), characteristic of founder-type modulation |
| **Neuroticism** | Low (25) | Rapid pivots without apparent anxiety, comfortable holding unresolved ambiguity (full vision + narrow execution simultaneously), steady decision quality despite setbacks (Dec 28 incidents responded to with systematic fixes, not panic) |

**Shaper Score (Dalio's 7 attributes, estimated 0-100):**

| Attribute | Score | Evidence |
|-----------|-------|----------|
| Intense curiosity | 95 | Every phase begins with exhaustive research; tangential ideas constantly explored |
| Independent thinking | 90 | Unconventional product architectures; "nobody else is doing this" as a positive signal |
| Dreams big | 95 | Franchise system, character universe, national expansion -- all before MVP ships |
| Practical determination | 85 | Ruthless MVP narrowing, founding-partner model, evidence-based completion |
| Self-knowledge | 80 | Deliberate team composition (Crystal for operations, Dante for on-camera, Tiana for media) |
| Big picture + granular detail | 95 | Simultaneously holds franchise vision and per-minute voice cost calculations |
| Intellectual confrontation | 80 | Challenges AI agent output, commissions forensic audits, builds critic-layer guardrails |

### 2.9 System 1 / System 2 Profile

Based on decision pattern analysis across both projects:

**System 1 (Fast, Intuitive) Triggers:**
- Visual design quality ("this design feels wrong")
- Character personality fit ("Torque should never become so chaotic that he drives misinformation")
- Brand voice consistency ("Entertainment first")
- Feature excitement ("yes, and" escalation of good ideas)
- Market opportunity recognition ("Charlotte is one of the most car-obsessed cities in America. And nobody is serving it.")
- Emotional design standards ("treat it as a new story, show enthusiasm")

**System 2 (Slow, Analytical) Triggers:**
- Technical architecture decisions (Six-layer knowledge base model, five-tier source confidence hierarchy)
- Monetization modeling (per-minute voice costs, commission per agent per family per month)
- Quality gate enforcement (6-layer guardrails, invariant checking, pipeline preflight)
- Scope narrowing (MVP priorities, 90-day execution plans)
- Franchise niche evaluation (nine weighted criteria)
- Risk assessment (affordable loss analysis, founding-partner model de-risking)

**The Switching Pattern:**
The founder uses System 1 first for opportunity recognition and creative leaps, then switches to System 2 for validation and planning. Feature scope follows System 1 ("is this exciting?") → System 2 ("is this feasible and what are the first 90 days?"). Quality evaluation follows System 1 ("does this feel right?") → System 2 ("does it pass the gates?"). This rhythmic switching is characteristic of expert entrepreneurs (Sarasvathy's research) and must be modeled in the Founder Simulator.

---

## 3. The Idea Maturation Process

### 3.1 The Common Sequence

From both projects, ideas follow a consistent maturation sequence. Not every idea passes through every stage -- some are killed early, some skip steps -- but the sequence is:

```
1. TRIGGER
   - A gap recognized in research
   - A tangential connection spotted
   - A user need surfaced
   - A capability discovered in an existing system
   - A "what if?" question asked

2. RESEARCH SPRINT
   - Competitive landscape analysis
   - Academic/industry framework review
   - Unit economics modeling
   - User need validation
   - Duration: hours to days, not weeks

3. VISION CAPTURE
   - Exhaustive strategic document (10,000-73,000 characters)
   - Written in handoff format (for AI or human execution)
   - Includes full architectural implications
   - Includes monetization analysis
   - Includes who it serves and why they care

4. CROSS-REFERENCE
   - How does this connect to existing architecture?
   - Does it create structural leverage (improves multiple things at once)?
   - Does it conflict with existing quality standards?
   - Does it serve the same user or a new audience?

5. SCOPE DECISION
   - Build now? Defer? Kill?
   - If build now: What is the minimum credible slice?
   - What gets parked in the vision document for later?

6. ARCHITECTURAL DESIGN
   - What system or layer does this require?
   - Does that system already exist?
   - How does it integrate with existing architecture?

7. MOCKUP / VISUAL REVIEW
   - Before code: mockups, visual proofs, design reviews
   - Founder visual approval required
   - This is the "System 1 taste check" gate

8. IMPLEMENTATION
   - Code against the architectural design
   - Tests alongside implementation
   - Documentation alongside code

9. VERIFICATION
   - E2E testing (not component testing in isolation)
   - Deployment to correct environment
   - Playwright visual check
   - Actual output verification ("verify ACTUAL output, never test isolated components")

10. LEARNING CAPTURE
    - What worked? What didn't?
    - What would we do differently?
    - Does this change any quality standards?
    - Does this reveal a generalization opportunity?
```

### 3.2 The Role of Research

Research in the founder's process is not optional and not separate from building. It is the first act of building.

**Characteristics of how research operates:**

1. **Research precedes vision.** In QCR, the competitor SEO research document existed before the product vision. In Elderle, the caregiver market analysis existed before the AI companion concept. The founder does not have an idea and then find evidence for it. The founder studies the landscape and the idea emerges from the gaps.

2. **Research is fast.** The QCR competitive research and the 73,000-character Architecture Blueprint were produced on the same day. The founder's research process is not leisurely academic review -- it is intensive, focused, and immediately translated into product implications.

3. **Research creates the vocabulary.** The Octalysis gamification framework, AEO (Answer Engine Optimization), JTBD, Effectuation -- these frameworks become the language in which product decisions are discussed. Research imports conceptual tools, not just data.

4. **Research documents are themselves products.** They are written at the quality and depth of publishable work. The Framework Synthesis for this project is 1,945 lines with cited academic sources. QCR's Architecture Blueprint is a reference-grade document. These are not notes; they are intellectual assets.

5. **Research depth correlates with conviction.** The deeper the research, the bolder the subsequent decisions. The QCR franchise model (the most ambitious idea) was supported by the most thorough niche evaluation (nine weighted criteria). The Elderle freemium pivot (the biggest business model change) was grounded in detailed market sizing (53M unpaid caregivers) and unit economics ($75-180/user/month affiliate revenue).

### 3.3 The Role of Tangential Thinking

The founder's most valuable creative contributions are not planned features. They are tangential connections -- seeing capability A built for purpose X and asking "could this also do Y?"

**Tangential idea generation follows a pattern:**

1. Build or discover capability A for purpose X
2. Notice that capability A has properties that are useful beyond purpose X
3. Ask: "What else could this do?"
4. Explore the tangential application as if it were a new product idea (research sprint, vision capture)
5. If it passes the cross-reference test (structural leverage, alignment with existing architecture), elevate it

**Examples from both projects:**

| Capability Built | Original Purpose | Tangential Discovery | Result |
|-----------------|------------------|---------------------|--------|
| QCR social sniffing | Monitor automotive conversations | Detect local news demand | Geo-local news system |
| QCR tool suite | Provide car information | Engage users competitively | Full gamification engine |
| QCR event calendar | List car events | Predict traffic patterns | Traffic intelligence tool |
| QCR architecture | Serve Charlotte automotive | Serve any local niche | Franchise model |
| Elderle AI intake | Collect medication data | Provide ongoing companionship | Jessica AI companion |
| Elderle Jessica persona | Companion conversations | Test the companion at scale | Synthetic users |
| Elderle character architecture | Power Jessica's personality | Power multiple characters | Character Universe |
| Elderle knowledge base | Answer medication questions | Generate educational products | Mini-courses, e-books |

**The system should automate this.** After any significant capability is built, the Visionary Agent should run a "tangential scan" asking: "What else could this capability do? What adjacent problems does it solve? What new audiences could it serve?"

### 3.4 The Role of Quality Gates

Quality gates in the founder's process are not bureaucratic checkpoints. They are failure prevention mechanisms, each triggered by a specific past failure.

**Gate origin stories:**

| Gate | Triggered By | Project | Rule |
|------|-------------|---------|------|
| Visual verification | Component tested in isolation but rendered output was broken | Elderle | "ALWAYS verify ACTUAL output, never test isolated components" |
| Demo before deploy | Features deployed to prod without founder review | Elderle/QCR | "Never deploy new features to prod before founder reviews on demo site" |
| Visual consistency | Full scene regeneration caused character/style drift | QCR | "NEVER regenerate full scene images. Composite overlays onto existing bases." |
| Evidence-based completion | Tasks marked DONE without verifiable evidence | Elderle | "NEVER mark DONE without verifiable evidence (file exists, DB row exists, model on disk)" |
| Deletion includes all references | Symbol deleted from source but left in imports, tests, docs | Elderle | "After ANY deletion/rename: grep and fix EVERY hit" |
| Pipeline preflight | Pipeline status described by manual grep instead of automated check | Elderle | "ALWAYS run pipeline_preflight.py before answering status questions" |

**The quality gate philosophy:** quality is not a continuous process but a **punctuated equilibrium** -- long periods of rapid building interrupted by intense quality sprints triggered by specific failures. Each failure produces a permanent gate. The gate system grows over time and never shrinks.

### 3.5 The Role of Mockups and Visual Review

Visual review is the founder's System 1 quality gate. Before any code is written for a user-facing feature, the founder needs to see it.

This manifests as:
- QCR: Stakeholder reveal presentations (multiple versions), Brand Kit, 2D World design with hex-tile navigation
- Elderle: Character Universe visual concepts, Jessica persona visual identity, FlutterFlow screen designs (32 screens)
- Cross-project: "After every deploy, use Playwright MCP to visually inspect each changed page before declaring done"

**The principle:** Code without visual review is premature. The founder's taste operates visually, not verbally. A written description of a feature cannot be approved; a visual representation can. This means the system must generate visual artifacts (mockups, screenshots, design comps) at every review gate, not just written proposals.

### 3.6 How Scope Expands and Contracts

Scope follows a breathing pattern: inhale (expand) during ideation, exhale (contract) during execution.

**The expansion triggers (inhale):**
- Structural leverage discovered (new layer improves multiple features)
- New audience discovered (existing architecture serves them too)
- Architecture generalization recognized (specific → general → abstract)
- Tangential idea passes cross-reference test
- Monetization layer identified on existing infrastructure

**The contraction triggers (exhale):**
- Transition from architecture to execution
- Deadline or resource constraint
- Quality consolidation sprint triggered by incidents
- Recognition that the current foundation has unresolved issues
- Founder consciously asks: "What are the first 90 days?"

**The healthy scope cycle:**
```
Expand (vision docs, research, architecture) → ~2-4 weeks
Contract (MVP definition, 90-day plan, quality audit) → ~1-2 weeks
Build (implement the slice) → ~4-8 weeks
Verify (E2E testing, deployment, evidence) → ~1-2 weeks
Learn (capture learnings, update standards) → ~1 week
[Repeat at a higher level]
```

### 3.7 The Punctuated Equilibrium Model

Both projects show the same meta-pattern: long periods of rapid expansion punctuated by sharp quality consolidation events.

**Elderle timeline:**
- Oct 2025 - Dec 2025: Rapid expansion (medication tracker → AI companion → freemium → character universe)
- Dec 28, 2025: Triple incident triggers quality revolution
- Jan - Feb 2026: Quality consolidation (guardrails, dead code removal, L3 wiring)
- Feb - Mar 2026: Mature iteration (synthetic users, embedding optimization, pricing)

**QCR timeline:**
- March 7-14, 2026: Rapid expansion (competitive research → architecture blueprint → brand → character system → monetization → intelligence stack → franchise vision)
- March 14-20, 2026: MVP pivot (ruthless narrowing to repair advisor + founding partners)
- March 20-26, 2026: Implementation (108 pages wired, 24 tool pages, gamification, content pipeline)

**The model:** Punctuated equilibrium. The system should not try to maintain constant quality during expansion phases or constant creativity during consolidation phases. Instead, it should recognize which mode the project is in and adjust its behavior accordingly:
- During expansion: generate ideas freely, do not enforce strict gates, capture everything
- During consolidation: enforce gates rigorously, remove dead code, verify every claim, harden foundations

---

## 4. The Agent Architecture

### 4.1 Architecture Overview

The system consists of seven specialized agents connected by a directed pipeline with quality gates at each handoff point. The pipeline is built on LangGraph for state management, human-in-the-loop support, and durable execution.

```
                           ┌─────────────────┐
                           │   RAW IDEA       │
                           └────────┬─────────┘
                                    │
                                    v
                    ┌───────────────────────────────┐
                    │      VISIONARY AGENT           │
                    │  Idea expansion, creative leaps│
                    │  Frameworks: Effectuation, ToT, │
                    │  Lateral Thinking, Blue Ocean   │
                    └───────────────┬───────────────┘
                                    │
                              [GATE 1: Vision]
                                    │
                                    v
                    ┌───────────────────────────────┐
                    │      RESEARCH AGENT            │
                    │  Deep-dive validation           │
                    │  Frameworks: JTBD, Design       │
                    │  Thinking, First Principles     │
                    └───────────────┬───────────────┘
                                    │
                              [GATE 2: Evidence]
                                    │
                                    v
                    ┌───────────────────────────────┐
                    │      STRATEGIST AGENT          │
                    │  Phased planning, scope control │
                    │  Frameworks: Working Backwards,  │
                    │  Effectuation (Affordable Loss)  │
                    └───────────────┬───────────────┘
                                    │
                                    v
           ┌────────────────────────────────────────────────┐
           │              MULTI-AGENT DEBATE                 │
           │  ┌──────────┐ ┌──────────┐ ┌────────────────┐ │
           │  │  Critic   │ │Visionary │ │Founder Simulator│ │
           │  │  Agent    │ │ (review) │ │  (prediction)   │ │
           │  └──────────┘ └──────────┘ └────────────────┘ │
           │  2-3 rounds of cross-critique and synthesis    │
           └────────────────────┬───────────────────────────┘
                                │
                          [GATE 3: Debate Consensus]
                                │
                                v
                    ┌───────────────────────────────┐
                    │     FOUNDER REVIEW             │
                    │  Human checkpoint               │
                    │  (skippable if Founder Sim      │
                    │   confidence > threshold)        │
                    └───────────────┬───────────────┘
                                    │
                              [GATE 4: Approval]
                                    │
                                    v
                    ┌───────────────────────────────┐
                    │      BUILDER AGENTS            │
                    │  Implementation                 │
                    │  Patterns: SWE-Agent, Reflexion │
                    └───────────────┬───────────────┘
                                    │
                              [GATE 5: Code Review]
                                    │
                                    v
                    ┌───────────────────────────────┐
                    │      VERIFIER AGENT            │
                    │  E2E testing, deployment,       │
                    │  visual verification             │
                    └───────────────┬───────────────┘
                                    │
                              [GATE 6: Verified Done]
                                    │
                                    v
                    ┌───────────────────────────────┐
                    │      LEARNING CAPTURE          │
                    │  Update case library, taste     │
                    │  calibration, anti-patterns     │
                    └───────────────────────────────┘
```

### 4.2 Visionary Agent

**Role:** Takes a raw idea and expands it into a fully formed product proposal. This is the agent that must think most like the founder.

**Context Loaded:**
- Founder Cognitive Profile (Section 2 of this document)
- Pattern Library (Section 5 of this document)
- Knowledge Layers 5, 4, 3, 1 (Synthesis + Learning + Decisions + Fundamentals)
- Current project context (codebase, user base, team capabilities)
- Taste Vectors (visual, technical, content, scope, innovation)

**Frameworks Used:**
- **Effectuation (Bird-in-Hand):** Start from available means, not desired outcomes. "What can we build with what we have?"
- **Tree-of-Thought:** Explore 3-5 product directions simultaneously, evaluate each, prune and combine
- **Lateral Thinking:** Apply random entry, provocation, concept extraction to generate unexpected connections
- **Blue Ocean (Four Actions):** Eliminate, Reduce, Raise, Create for market differentiation
- **First Principles:** Decompose to fundamentals when conventional approaches feel insufficient

**Processing Pipeline:**
```
Step 1: MEANS ASSESSMENT (Bird-in-Hand)
  What existing capabilities can we leverage?
  What does the team know? What resources exist?
  What adjacent problems have we already solved?

Step 2: JOB ANALYSIS (JTBD)
  What functional job would this serve?
  What social job? What emotional job?
  What are users currently "hiring" for this job?

Step 3: FIRST PRINCIPLES DECOMPOSITION
  What are the fundamental truths about this problem?
  Which category "rules" are conventions, not constraints?

Step 4: TREE-OF-THOUGHT EXPLORATION
  Generate 3-5 distinct product directions
  Evaluate each against taste vectors, JTBD, effectuation
  Prune unlikely paths, explore promising ones deeper
  Allow path combination for hybrid solutions

Step 5: LATERAL THINKING ENHANCEMENT
  Apply cross-domain analogy
  Apply "what if we did the opposite?"
  Apply concept extraction from existing capabilities

Step 6: PR/FAQ GENERATION (Working Backwards)
  Write the press release for the best direction
  Write the FAQ addressing hard questions
  Evaluate: would the founder be excited by this?

Step 7: CONSTITUTIONAL SELF-CRITIQUE
  Check against Product Constitution
  Identify and resolve priority conflicts
```

**Output:** Product Proposal containing:
- PR/FAQ document
- JTBD analysis (functional/social/emotional dimensions)
- Strategy Canvas (competitive positioning)
- Means assessment
- Affordable loss analysis
- Tree-of-Thought reasoning trace
- Constitutional compliance report

**Handoff:** Passes the Product Proposal to the Research Agent for validation. Also passes the reasoning trace for audit.

### 4.3 Research Agent

**Role:** Takes the Visionary Agent's product proposal and validates it against reality. Provides the evidence layer that the founder always demands before building.

**Context Loaded:**
- Knowledge Layers 2, 1 (Context + Fundamentals)
- Current market data (competitive landscape, user research, industry trends)
- Academic frameworks (JTBD, Design Thinking Empathize stage, Blue Ocean Strategy Canvas)

**Frameworks Used:**
- **Design Thinking (Empathize/Define):** Deeply understand the user's experience and context
- **JTBD Analysis:** Validate that the proposed product serves real user jobs
- **First Principles (Decomposition):** Break down the problem to identify hidden assumptions
- **Blue Ocean (Strategy Canvas):** Map the competitive landscape to verify differentiation

**Processing Pipeline:**
```
Step 1: MARKET VALIDATION
  Who are the direct and indirect competitors?
  What do they do well? What do they miss?
  Strategy Canvas: where does this proposal create differentiation?

Step 2: USER NEED VALIDATION
  Does JTBD analysis support the proposed user jobs?
  What evidence exists (market size, search volume, user complaints)?
  Are there underserved segments?

Step 3: TECHNICAL FEASIBILITY
  What technical capabilities are required?
  Which already exist in the codebase?
  What is the estimated effort and risk?

Step 4: UNIT ECONOMICS
  What does this cost to build and operate?
  What is the revenue model and projected return?
  Does affordable loss analysis support the investment?

Step 5: RISK ANALYSIS
  What could go wrong?
  What are the dependencies?
  What is the worst-case scenario?

Step 6: EVIDENCE COMPILATION
  Compile all findings into a research brief
  Rate confidence level for each finding (high/medium/low)
  Identify gaps where more research is needed
```

**Output:** Research Brief containing:
- Market analysis with competitive positioning
- User need validation with evidence
- Technical feasibility assessment
- Unit economics model
- Risk register
- Confidence ratings for each finding
- Identified knowledge gaps

**Handoff:** Passes the Research Brief back to the Visionary Agent's Product Proposal, creating an enriched proposal that goes to the Strategist Agent.

### 4.4 Strategist Agent

**Role:** Takes the research-validated product proposal and converts it into a phased implementation plan. This is the agent that embodies the founder's "think in systems, build in slices" philosophy.

**Context Loaded:**
- Knowledge Layers 3, 2 (Decisions + Context)
- Historical phasing decisions (how past features were sequenced)
- Current project state (what is built, what is planned, what is technical debt)
- Team capacity and constraints

**Frameworks Used:**
- **Working Backwards:** Start from the desired outcome and work backwards to define phases
- **Effectuation (Affordable Loss):** Size each phase to be within affordable loss limits
- **Effectuation (Crazy Quilt):** Identify partnership opportunities that change the plan

**Processing Pipeline:**
```
Step 1: MVP DEFINITION
  What is the minimum credible slice that proves the concept?
  What can be deferred without losing the core value?
  Apply the "repair advisor" principle: find the high-intent wedge

Step 2: PHASE SEQUENCING
  Phase 1: Foundation (knowledge layer, architecture)
  Phase 2: Core experience (minimum user-facing product)
  Phase 3: Enhancement (additional features, refinement)
  Phase 4: Scale (expansion, optimization)
  Each phase must be independently valuable

Step 3: DEPENDENCY MAPPING
  What must be built before what?
  Where are the parallelizable work streams?
  What are the critical path items?

Step 4: SCOPE GATES
  What are the go/no-go criteria for each phase?
  What metrics determine if Phase N succeeded enough to start Phase N+1?
  What gets cut if Phase N takes longer than expected?

Step 5: RESOURCE ALLOCATION
  How long will each phase take?
  What team capacity is needed?
  What is the affordable loss for each phase?

Step 6: RISK MITIGATION
  For each identified risk, what is the mitigation plan?
  What are the fallback options if a phase fails?
```

**Output:** Implementation Plan containing:
- Phase breakdown with deliverables and timelines
- MVP definition with explicit scope boundaries
- Dependency graph
- Go/no-go criteria for each phase
- Resource and capacity estimates
- Risk mitigation strategies
- List of what is explicitly NOT in scope for each phase

**Handoff:** Passes the Implementation Plan to the Multi-Agent Debate round.

### 4.5 Critic Agent

**Role:** Challenges every proposal, identifies risks, enforces quality standards, and catches the things the other agents missed. This is the agent that embodies the founder's quality gates.

**Context Loaded:**
- Knowledge Layers 5, 4, 3 (Synthesis + Learning + Decisions)
- Product Constitution
- Anti-Pattern Library (all known mistakes and their prevention rules)
- SDLC gate definitions
- Historical rejection data (what the founder has rejected and why)

**Frameworks Used:**
- **Constitutional AI (Product Constitution):** Self-critique against product values in priority order
- **Multi-Agent Debate (Black Hat):** Identify what could go wrong, what is missing, what is mediocre
- **Case-Based Reasoning (Anti-Pattern Matching):** Compare proposal against known failure patterns
- **System 2 Thinking (Analytical Override):** Override enthusiasm with careful analysis

**Processing Pipeline:**
```
Step 1: CONSTITUTIONAL REVIEW
  Check proposal against each Product Constitution principle
  Identify violations in priority order
  Score overall constitutional alignment

Step 2: ANTI-PATTERN SCAN
  Compare proposal against known anti-patterns:
  - Feature without architecture?
  - Generic content without local/personal specificity?
  - Claiming done without verification plan?
  - Monetization that could erode trust?
  - Scope expansion without structural leverage?
  - Emotional design as afterthought instead of specification?

Step 3: RISK AMPLIFICATION
  For each risk identified by the Research Agent, ask:
  - What if this risk materializes? What is the cascade?
  - What risks were NOT identified? (unknown unknowns)
  - What has gone wrong in similar past projects?

Step 4: QUALITY STANDARD CHECK
  Does this meet the visual quality threshold?
  Does this meet the content quality threshold?
  Does this meet the technical quality threshold?
  Would the founder say "this isn't good enough"?

Step 5: SCOPE CHALLENGE
  Is the MVP too large? (Could it be smaller and still prove the concept?)
  Is the MVP too small? (Does it create a misleading signal about product-market fit?)
  Are any features in Phase 1 that belong in Phase 2 or later?

Step 6: VERDICT
  APPROVE: Proposal passes all checks
  CONDITIONAL APPROVE: Passes with specific required modifications
  REJECT: Fundamental issues that require rethinking
  Include specific, actionable feedback for each issue
```

**Output:** Critic Review containing:
- Constitutional alignment score with detailed findings
- Anti-pattern matches with evidence
- Amplified risk assessment
- Quality standard evaluation
- Scope challenge findings
- Verdict with actionable feedback

**Handoff:** Feeds into the Multi-Agent Debate alongside the Visionary Agent's response and the Founder Simulator's prediction.

### 4.6 Builder Agents

**Role:** Implement the approved plan as working code with tests. These agents follow the patterns established in the existing Elderle and QCR development workflows.

**Context Loaded:**
- Knowledge Layer 2 (Context -- the codebase)
- Approved Implementation Plan
- CLAUDE.md and project-specific coding standards
- Reflexion Memory (mistakes to avoid during implementation)

**Frameworks Used:**
- **SWE-Agent Patterns:** Code generation, test writing, PR submission
- **Reflexion:** Self-critique after each implementation step; learn from mistakes without parameter updates

**Processing Pipeline:**
```
Step 1: PLAN DECOMPOSITION
  Break approved plan into individual implementation tasks
  Identify task dependencies and parallelization opportunities
  Estimate effort for each task

Step 2: ARCHITECTURE FIRST
  Before writing feature code, ensure the underlying architecture exists
  If new architecture is needed, build and test it first
  Follow the "architecture before features" principle

Step 3: IMPLEMENTATION
  Write code following project coding standards
  Write tests alongside code (not after)
  Document as you go (not after)
  Follow SDLC standards

Step 4: SELF-REVIEW
  Run all tests
  Check against Reflexion Memory for known mistake patterns
  Verify code matches the approved plan (no scope creep)
  Confirm no dead code or unused imports added

Step 5: HANDOFF
  Commit with descriptive messages
  Create PR with clear description
  Pass to Verifier Agent
```

**Output:** Working code with tests, committed and ready for verification.

**Handoff:** Passes to Verifier Agent for E2E testing and deployment verification.

### 4.7 Verifier Agent

**Role:** Ensures that what was built actually works in production, not just in isolation. This agent embodies the hard-won lessons from the December 28, 2025 incidents and the "verify ACTUAL output" directive.

**Context Loaded:**
- Knowledge Layers 5, 4 (Synthesis + Learning -- quality standards and past mistakes)
- Deployment procedures for the target environment
- E2E test suites
- Playwright visual verification capability

**Frameworks Used:**
- **Design Thinking (Test):** Put the implemented feature in front of real users (or synthetic users)
- **Reflexion:** If verification fails, generate verbal reflection and store in episodic memory

**Processing Pipeline:**
```
Step 1: ENVIRONMENT VERIFICATION
  Is the code deployed to the correct environment?
  Is it the correct server? (Remember: QCR is 68.183.133.24, not 159.203.117.17)
  Are all dependencies running?

Step 2: E2E TESTING
  Run full end-to-end test suite
  Not just unit tests -- test the actual user flow
  Test with representative data, not synthetic test data

Step 3: VISUAL VERIFICATION
  Use Playwright to capture screenshots of every changed page
  Compare against expected visual output
  Flag any visual regression or drift

Step 4: ACTUAL OUTPUT VERIFICATION
  Does the actual rendered output match expectations?
  Test the real deployment, not a dev environment
  "Never test isolated components and declare victory"

Step 5: EVIDENCE COLLECTION
  Screenshot evidence of working deployment
  Test results with pass/fail counts
  Performance metrics if applicable
  Store all evidence for the learning capture phase

Step 6: VERDICT
  VERIFIED: All checks pass with evidence
  FAILED: Specific failures listed with evidence
  If FAILED: Generate Reflexion memory entry and pass back to Builder Agent
```

**Output:** Verification Report containing:
- Environment check results
- E2E test results
- Visual verification screenshots
- Actual output comparison
- Collected evidence
- Pass/fail verdict

**Handoff:** If VERIFIED, passes to Learning Capture. If FAILED, passes back to Builder Agents with specific failure details and Reflexion memory.

### 4.8 Founder Simulator

**Role:** Predicts how the founder would react to a proposal, design, or implementation. Serves as both a quality gate (catch things the founder would reject before they reach the founder) and an escalation system (when the simulation is uncertain, escalate to the real founder).

**Full specification in Section 6.**

**Context Loaded:**
- Knowledge Layers 5, 4, 3 (Synthesis + Learning + Decisions -- heavy focus on taste)
- Founder Cognitive Profile (Section 2)
- Historical approval/rejection data with rationale
- Taste Vectors
- System 1/2 trigger mapping

**Frameworks Used:**
- **Big Five Profile:** Calibrate reaction intensity and style
- **System 1/2 Switching:** Model fast intuitive reactions AND slow analytical responses
- **Shaper Archetype:** Model the characteristic "yes, and" escalation
- **Case-Based Reasoning:** Retrieve similar past decisions and their outcomes
- **Taste Vectors:** Score proposals against encoded preferences

**Output:** Founder Reaction Prediction containing:
- Predicted reaction (approve / conditional approve / reject)
- Rationale for the prediction
- Confidence score (0.0 - 1.0)
- Specific elements the founder would like
- Specific elements the founder would challenge
- Predicted "yes, and" suggestions (how the founder would escalate the idea)
- Escalation recommendation (if confidence < threshold, recommend human review)

**Handoff:** Feeds into the Multi-Agent Debate. If confidence is high (>0.85) and prediction is "approve," can serve as a substitute for human founder review on low-stakes decisions.

### 4.9 The Pipeline

The full pipeline connects agents through quality gates:

```
RAW IDEA
    |
    v
VISIONARY AGENT ──── produces ──── Product Proposal
    |
    | [GATE 1: Vision Check]
    | Does it serve a real user job? Is it differentiated?
    | Does the founder care about this? (taste vectors)
    |
    v
RESEARCH AGENT ──── produces ──── Research Brief
    |
    | [GATE 2: Evidence Check]
    | Is the market real? Are the economics viable?
    | Is the technical approach feasible?
    |
    v
STRATEGIST AGENT ──── produces ──── Implementation Plan
    |
    v
MULTI-AGENT DEBATE (2-3 rounds)
    |
    | Round 1: CRITIC reviews all outputs, identifies gaps and risks
    |          FOUNDER SIMULATOR predicts reaction to each element
    |          VISIONARY responds to critiques
    |
    | Round 2: All agents revise based on Round 1 feedback
    |          STRATEGIST synthesizes into unified plan
    |          FOUNDER SIMULATOR gives updated prediction
    |
    | Round 3 (if needed): Final synthesis and consensus
    |
    | [GATE 3: Debate Consensus]
    | Critic has no unresolved REJECT-level objections
    | Founder Simulator confidence > threshold
    |
    v
FOUNDER REVIEW (human checkpoint)
    |
    | [GATE 4: Founder Approval]
    | Can be skipped if Founder Simulator confidence > 0.85
    | and the decision is classified as low-stakes
    |
    v
BUILDER AGENTS ──── produce ──── Working Code + Tests
    |
    | [GATE 5: Code Review]
    | All tests pass? Architecture review? No scope creep?
    |
    v
VERIFIER AGENT ──── produces ──── Verification Report
    |
    | [GATE 6: Verified Done]
    | Deployed? E2E tested? Visual verified? Evidence collected?
    |
    v
LEARNING CAPTURE
    Update case library with new decision
    Calibrate taste vectors based on outcome
    Update anti-pattern library if failures occurred
    Store Reflexion memory for any lessons learned
```

### 4.10 Quality Gates Between Agents

Each gate has specific pass/fail criteria, inspired by the gate system designed in the Framework Synthesis:

#### Gate 1: Vision Check
- Does this serve a real user job? (JTBD validation)
- Is this differentiated from existing solutions? (Blue Ocean)
- Does the founder's taste profile suggest interest? (Taste vectors)
- **Pass criteria:** All three affirmative

#### Gate 2: Evidence Check
- Is there evidence of market demand? (Market research)
- Are the unit economics viable? (Financial modeling)
- Is the technical approach feasible? (Architecture review)
- **Pass criteria:** Market evidence exists, economics are positive, tech is feasible

#### Gate 3: Debate Consensus
- Does the Critic Agent have no unresolved REJECT-level objections?
- Is the Founder Simulator confidence above threshold (>0.70)?
- Has the Strategist Agent produced a coherent phased plan?
- **Pass criteria:** No REJECT objections, confidence > 0.70, plan exists

#### Gate 4: Founder Approval
- Has the founder reviewed the proposal? (Or: is the Founder Simulator's confidence > 0.85 for a low-stakes decision?)
- Are there specific founder requests captured for implementation?
- **Pass criteria:** Explicit approval or high-confidence auto-approval

#### Gate 5: Code Review
- Do all tests pass?
- Does the architecture serve long-term goals?
- Is the scope within the approved plan (no scope creep)?
- **Pass criteria:** Tests pass, architecture approved, scope within bounds

#### Gate 6: Verified Done
- Is it deployed to the correct environment?
- Does actual output match expectations (Playwright visual check)?
- Does it work end-to-end, not just in isolation?
- Is evidence collected and stored?
- **Pass criteria:** All four verified with evidence

### 4.11 Technical Implementation

**Recommended Framework: LangGraph**

Based on the Framework Synthesis research, LangGraph is the recommended orchestration framework because:

1. **State Management:** Product development is inherently stateful. The system must track where each idea is in the pipeline, what decisions have been made, and what the current context is.

2. **Human-in-the-Loop:** The founder review checkpoint is non-negotiable. LangGraph has native support for pausing execution and waiting for human input.

3. **Parallel Processing:** During the Multi-Agent Debate, multiple agents (Visionary, Critic, Founder Simulator) operate in parallel. LangGraph supports this natively.

4. **Durable Execution:** Product development spans days or weeks, not minutes. The system must persist state across sessions.

5. **Graph Structure:** The pipeline is naturally a directed graph with cycles (debate rounds) and branches (pass/fail at gates).

**Reasoning Architecture: Tree-of-Thought for Visionary Agent**

The Visionary Agent uses Tree-of-Thought reasoning, not Chain-of-Thought. Product visionaries think in branching possibilities, not linear sequences. The ToT architecture:
- Generates 3-5 distinct product directions at each decision point
- Evaluates each branch against taste vectors, JTBD, effectuation principles
- Prunes unlikely paths with explanations
- Allows path combination for hybrid solutions
- Backtracks when paths prove unviable

**Quality Enforcement: Product Constitutional AI**

A Product Constitution (derived from the founder's quality standards) is loaded into every agent as a system-level constraint:

```
PRODUCT CONSTITUTION v1.0

Priority 1: User Value
  Every feature must serve a real user job (functional, social, or emotional)
  The user's experience takes priority over technical elegance
  If a feature does not make someone's life better, it does not ship

Priority 2: Product Coherence
  Every feature must strengthen the overall product vision
  Scope expansion is only justified by structural leverage
  Features that create confusion or complexity debt are rejected

Priority 3: Quality Standards
  Visual quality must meet the founder's taste thresholds
  Technical implementation must pass all SDLC gates
  Content must be researched, cited, and actionable
  Nothing ships without end-to-end verification
  Emotional design has the same engineering rigor as technical design

Priority 4: Innovation Ambition
  Incremental improvement is the floor, not the ceiling
  The system should always ask "what would make this 10x better?"
  Creative leaps are valued over safe iterations
  Blue Ocean thinking over Red Ocean competition

Priority 5: Execution Discipline
  Every commitment must be deliverable within the stated timeline
  Scope is managed through phasing, not cutting quality
  Done means deployed, tested, and verified -- not "code complete"
  Architecture before features, always
```

**Learning Mechanism: Reflexion-Based Episodic Memory**

Following the Reflexion framework (Shinn et al., NeurIPS 2023), the system maintains three types of memory:

1. **Decision Memory:** Records of past product decisions and their outcomes. "We chose X, and the founder loved it because Y." "We proposed Z, and the founder rejected it because W."

2. **Anti-Pattern Memory:** A growing library of mistakes to avoid. "We declared a feature done without E2E testing -- never again." "We generated full scene images instead of compositing overlays -- caused visual drift." This maps directly to the existing `.claude/mistakes.log` pattern.

3. **Taste Calibration Memory:** A running record of how well the system's taste judgments match the founder's actual reactions. "The system predicted the founder would approve this design -- the founder did not. Calibrate taste vectors." This enables the system to improve over time without parameter updates.

**Knowledge Architecture: Five-Layer Stack**

```
Layer 5: SYNTHESIS
  Pattern Library + Taste Vectors + Product Constitution
  What the system "knows" about good products

Layer 4: LEARNING
  Reflexion Memory + Calibration Records
  What the system has learned from mistakes

Layer 3: DECISIONS
  Case Library + ADRs + PR/FAQs
  Historical decisions and their rationale

Layer 2: CONTEXT
  Codebase + User Research + Competitive Analysis
  Current state of the product and market

Layer 1: FUNDAMENTALS
  Cognitive Frameworks + Academic Research + Industry Data
  The Framework Synthesis and its successors
```

Each agent loads the appropriate layers:
- **Visionary Agent:** Layers 5, 4, 3, 1
- **Research Agent:** Layers 2, 1
- **Strategist Agent:** Layers 3, 2
- **Critic Agent:** Layers 5, 4, 3
- **Founder Simulator:** Layers 5, 4, 3 (focus on taste)
- **Builder Agents:** Layer 2 (the codebase)
- **Verifier Agent:** Layers 5, 4 (quality standards)

---

## 5. The Pattern Library

This section contains reusable patterns extracted from both projects. These patterns should be loaded as context for all agents.

### 5.1 Decision Templates

#### Template 1: "When a new feature idea emerges..."

```
1. Before anything else:
   - What user job does this serve? (functional/social/emotional)
   - What knowledge layer does it require?
   - Does that layer already exist?

2. If the layer exists:
   - What surfaces can this feature sit on?
   - Does it create structural leverage? (improves multiple things)
   - Go to scope decision.

3. If the layer does not exist:
   - How expensive is the layer to build?
   - What other features would benefit from this layer?
   - Is the layer investment justified by structural leverage?
   - If yes: build the layer first, then the feature.
   - If no: defer or find an existing layer to approximate.

4. Scope decision:
   - What is the minimum credible slice?
   - What gets deferred to Phase 2+?
   - Does this distract from or strengthen the current focus?
```

#### Template 2: "When quality feels inadequate..."

```
1. Identify the specific quality gap:
   - Visual quality? → Need mockups and visual review
   - Content quality? → Need research depth and source verification
   - Technical quality? → Need architecture review and test coverage
   - Emotional quality? → Need persona-specific design specifications

2. Before fixing:
   - Is this a one-time issue or a systemic pattern?
   - If systemic: create a permanent quality gate (the December 28 lesson)
   - If one-time: fix it and add to anti-pattern library

3. The fix sequence:
   - Audit: How widespread is this issue? (grep the codebase)
   - Fix: Address all instances, not just the one you noticed
   - Gate: Create a check that prevents recurrence
   - Document: Update anti-pattern library and quality standards
```

#### Template 3: "When scope is expanding..."

```
1. Is this expansion triggered by structural leverage?
   - YES: The new layer improves multiple features → likely worth it
   - NO: It only helps one feature → defer it

2. Apply the affordable loss test:
   - What is the downside if this expansion fails?
   - Can we afford that downside?
   - What is the minimum experiment to test the expansion?

3. Apply the "90-day test":
   - Would this be in the first 90 days if we were starting fresh?
   - If no: defer to Phase 2+
   - If yes: include in current plan

4. Document the full vision:
   - Write the expanded vision as a complete strategic document
   - But only implement the minimum credible slice now
   - The document is the parking lot for deferred scope
```

#### Template 4: "When evaluating a monetization idea..."

```
1. The anti-sleaze test:
   - Would this content/feature be worth publishing without the monetization link?
   - If no: reject the monetization approach, not the content
   - If yes: proceed

2. The trust preservation test:
   - Does this monetization require source confidence hierarchy?
   - Does this monetization need methodology transparency?
   - Can the user verify our claims independently?

3. The value-first sequence:
   - Phase 1: Deliver value for free (prove the product is useful)
   - Phase 2: Monetize the free value (affiliate, lead gen)
   - Phase 3: Charge for premium value (subscription, marketplace)
   - Never skip phases

4. Stack the revenue models:
   - How many monetization mechanisms does this enable?
   - Free tier affiliate + paid tier subscription + partnership commission = stacked
   - Single-mechanism monetization is fragile
```

#### Template 5: "When designing for emotional impact..."

```
1. Identify the emotional job:
   - What does the user want to FEEL? (not just DO)
   - QCR: "I want to feel smart about my vehicle"
   - Elderle: "I want to feel less alone and more confident about health decisions"

2. Specify empathy as engineering:
   - What are the parameters? (Jessica's 2-4 sentence responses, Torque's personality sliders)
   - What are the thresholds? (dignity preservation, warmth minimum)
   - What are the testable criteria? (repetition handling, correction-resolve rule)

3. Design for dignity:
   - No condescension, no elderspeak, no gatekeeping
   - Independence framing (enabling, not surveilling)
   - Validate the user's effort and identity

4. Entertainment as quality:
   - "If it's not fun to read, it doesn't matter how accurate it is"
   - Fun is not optional; it is a quality standard
   - Brand voice must be consistent and warm
```

#### Template 6: "When a tangential idea appears..."

```
1. Record it immediately:
   - Even if it is not relevant to the current sprint
   - Tangential ideas are the most valuable features in hindsight

2. Run the cross-reference test:
   - Does this connect to existing architecture?
   - Does it create structural leverage?
   - Does it serve existing users or a new audience?

3. If it passes cross-reference:
   - Do a fast research sprint (hours, not weeks)
   - Write a vision capture document
   - Run through the scope decision template

4. If it fails cross-reference:
   - Document it in the "ideas for later" library
   - Periodically review the library when architecture changes
   - A change in architecture might make an old tangential idea viable
```

### 5.2 Anti-Patterns

These are the mistakes that have been corrected across both projects. Each anti-pattern includes the specific failure and the permanent rule it produced.

| # | Anti-Pattern | Failure Example | Permanent Rule |
|---|-------------|-----------------|---------------|
| AP-1 | Declaring done without verification | Component tested in isolation, rendered output was broken | "ALWAYS verify ACTUAL output, never test isolated components" |
| AP-2 | Deploying without founder review | Features deployed to prod without visual review | "Never deploy new features to prod before founder reviews on demo site" |
| AP-3 | Regenerating visual assets | Full scene image regeneration caused character/style drift | "NEVER regenerate full scene images. Composite overlays onto existing bases." |
| AP-4 | Marking done without evidence | Tasks marked DONE in tracker without verifiable artifacts | "NEVER mark DONE without verifiable evidence (file exists, DB row, model on disk)" |
| AP-5 | Deleting symbols without cleaning references | Symbol deleted from source but left in imports, tests, docs, comments | "After ANY deletion/rename: grep and fix EVERY hit" |
| AP-6 | Answering status without automation | Pipeline status described by manual grep instead of preflight script | "ALWAYS run pipeline_preflight.py before answering status questions" |
| AP-7 | Feature without architecture | One-off feature implementation without reusable foundation | "Architecture before features, always" |
| AP-8 | Dead code accumulation | 40% of L3 architecture computed but discarded (never wired to output) | "Regular dead code audits; if computed, it must be used" |
| AP-9 | Generic content without specificity | National car news with no Charlotte angle | "Every piece of content must have local/personal specificity" |
| AP-10 | Monetization without trust guardrails | Affiliate recommendation without methodology transparency | "Any monetized page must be worth publishing without the affiliate links" |
| AP-11 | Animation/asset overuse | Too many animations per viewport; reduced motion not considered | "Max 1 animated foreground per viewport; reduce-motion toggle required" |
| AP-12 | Leaving docs local-only | Documentation created but never pushed to repository | "Always push docs to GitHub immediately; never leave docs local-only" |
| AP-13 | Deploying to wrong server | Attempted deployment to dev server when prod was the target | "ALWAYS verify target environment before deployment" |
| AP-14 | Shallow research passed off as comprehensive | Research docs that are just summaries of memory files | "Research docs must be 500-2000+ lines with real web research" |
| AP-15 | Skipping table of contents | Long documents without navigation aids | "All research docs must have a clickable table of contents" |

### 5.3 Taste Vectors

Taste vectors encode the founder's preferences across multiple dimensions. Each vector has a direction (what is preferred) and a threshold (minimum acceptable quality).

#### Visual Taste

| Dimension | Preferred | Rejected | Threshold |
|-----------|----------|----------|-----------|
| Color scheme | Dark themes, high contrast | Light/washed-out themes | Must pass WCAG contrast checks |
| Information density | Dense, information-rich layouts | Whitespace-heavy minimalism | Every screen should teach something |
| Mascot integration | Characters integrated into experience | Characters as afterthought decoration | If mascots exist, they must be system-grade |
| Animation | Purposeful, sparse (max 1 per viewport) | Gratuitous animation everywhere | reduce-motion toggle required |
| Typography | Clear hierarchy, large touch targets (60pt for elderly) | Decorative fonts that sacrifice readability | 18pt minimum for elderly-facing interfaces |
| Visual consistency | Composite overlays on existing bases | Full regeneration between iterations | Never regenerate -- always composite |

#### Content Taste

| Dimension | Preferred | Rejected | Threshold |
|-----------|----------|----------|-----------|
| Research depth | 500-2000+ lines with cited sources | Surface-level summaries | Every claim must trace to a source |
| Local/personal specificity | Charlotte-specific, persona-specific | Generic national/universal | Could this appear on any other site? If yes, reject |
| Source confidence | Government > official > licensed > editorial > community | Unsourced assertions | Confidence tier must be labeled |
| Entertainment value | Fun to read, even for technical content | Dry, academic, or robotic tone | "If it's not fun to read, it doesn't matter how accurate it is" |
| Documentation format | Handoff-ready, exhaustive, numbered sections | Brief notes or bullet lists | Must be consumable by both humans and AI assistants |
| Navigation | Clickable table of contents, clear structure | Wall of text without signposting | Every doc over 100 lines needs TOC |

#### Technical Taste

| Dimension | Preferred | Rejected | Threshold |
|-----------|----------|----------|-----------|
| Architecture | Layered, reusable, serves multiple surfaces | One-off, single-purpose implementations | Must create structural leverage |
| Data modeling | Graph-minded, relationship-first | Flat tables without connections | Relationships are first-class objects |
| Trust implementation | Source hierarchies, claim provenance, confidence tiers | Trust as marketing copy | Must be verifiable in the data model |
| Testing | E2E verification of actual output | Unit tests of isolated components | "Verified done" with evidence |
| Deployment | Correct environment, visual verification, evidence | "Works on my machine" | Playwright visual check required |
| Quality gates | Permanent, never removed, triggered by specific failures | Ad-hoc quality checks | Every gate has an origin story |

#### Scope Taste

| Dimension | Preferred | Rejected | Threshold |
|-----------|----------|----------|-----------|
| Feature justification | Structural leverage (improves multiple things) | Single-purpose addition | Must strengthen at least 2 existing features |
| MVP size | Minimum credible wedge + high-intent entry point | Full feature set at launch | What would the repair advisor be for this product? |
| Phase boundaries | Independently valuable phases | Phases that depend on later phases for value | Each phase must stand alone |
| Deferral | Explicit parking in vision documents | Silent omission | Deferred scope documented, not forgotten |
| Kill decisions | Explicit kill with rationale | Slow death by neglect | If not building, explicitly say so |

#### Innovation Taste

| Dimension | Preferred | Rejected | Threshold |
|-----------|----------|----------|-----------|
| Ambition level | Category redefinition over incremental improvement | "Good enough" or "industry standard" | Would this surprise and delight? |
| Creative sources | Cross-domain analogy, tangential discovery | Copying competitors | Must bring something from outside the category |
| Abstraction path | Build specific → recognize general → propose abstract | Start with abstract framework | Abstraction earned through specific implementation |
| Moat building | Data moats, network moats, character moats | First-mover advantage alone | What compounds over time? |

### 5.4 Scope Management Rules

These rules govern how scope decisions are made in the system:

1. **The Structural Leverage Rule:** Scope expansion is justified only when the new capability improves multiple existing features simultaneously. "If adding this layer only helps one thing, defer it."

2. **The 90-Day Rule:** Before expanding scope, ask: "Would this be in the first 90 days if starting fresh?" If no, it belongs in Phase 2+.

3. **The Affordable Loss Rule:** Size every investment to be within what you can afford to lose if it fails. Do not bet the project on a single feature.

4. **The Vision Document Rule:** Every deferred idea gets documented in a vision document, not silently dropped. The document is the parking lot.

5. **The Architecture First Rule:** If a feature requires a new architectural layer, build the layer first and validate it before building the feature. Never build features on unverified foundations.

6. **The Kill Decision Rule:** If something has been deferred three times, it is time to explicitly decide: build it or kill it. No zombie features.

7. **The Minimum Credible Wedge Rule:** The MVP should be the smallest thing that creates real value for real users. The QCR repair advisor, not the full Garage OS. The Elderle Jessica companion, not the full Character Universe.

8. **The Phase Independence Rule:** Each phase must deliver independent value. If Phase 1 is only valuable after Phase 2 ships, the phasing is wrong.

### 5.5 The Founder Approval Test

A checklist for predicting whether the founder would approve a proposal. Any agent can run this test before presenting to the Founder Simulator or the real founder.

**Would the founder approve this? Check all that apply:**

- [ ] **Knowledge layer:** Does this build or leverage structured knowledge underneath? (Not just a surface feature)
- [ ] **User job:** Does this serve a clear functional, social, or emotional user need?
- [ ] **Structural leverage:** Does this improve multiple existing features, not just add a new one?
- [ ] **Trust preservation:** Would this be worth publishing/using without any monetization links?
- [ ] **Emotional specification:** Is empathy/dignity/warmth specified with engineering precision, not just mentioned?
- [ ] **Entertainment value:** Is this fun/engaging to interact with? ("If it's not fun to read...")
- [ ] **Local/personal specificity:** Is this specific to the user's context, not generic?
- [ ] **Architecture first:** Does the architectural foundation exist before the feature?
- [ ] **Minimum credible wedge:** Is the scope the smallest thing that creates real value?
- [ ] **Verification plan:** Is there a concrete plan to verify actual output, not just test components?
- [ ] **Visual quality:** Does the visual design meet the founder's taste standards?
- [ ] **Research grounding:** Is this backed by research, not just intuition?

**Scoring:**
- 12/12: Very likely approval
- 10-11/12: Likely approval with minor revisions
- 8-9/12: Conditional approval with specific changes required
- Below 8: Likely rejection -- rethink before presenting

---

## 6. The Founder Simulator Specification

### 6.1 Purpose and Operating Model

The Founder Simulator is not a personality chatbot. It is a **prediction engine** that estimates how the real founder would react to a product proposal, design decision, or implementation output.

**Operating Model:**

```
INPUT: A product artifact (proposal, design, code, deployment)

PROCESS:
  1. Classify the decision type (strategic, tactical, aesthetic, technical)
  2. Retrieve similar past decisions from case library
  3. Apply the appropriate cognitive mode (System 1 for aesthetic, System 2 for technical)
  4. Score against taste vectors
  5. Check against anti-pattern library
  6. Generate predicted reaction

OUTPUT:
  - Predicted reaction (approve / conditional approve / reject)
  - Confidence score (0.0 - 1.0)
  - Specific elements the founder would like
  - Specific elements the founder would challenge
  - Predicted "yes, and" suggestions
  - Escalation recommendation
```

**When to Auto-Approve vs. Escalate:**

| Decision Stakes | Founder Sim Confidence | Action |
|----------------|----------------------|--------|
| Low (formatting, minor UI) | > 0.85 | Auto-approve |
| Low | < 0.85 | Escalate to founder |
| Medium (new feature, scope change) | > 0.90 | Auto-approve with notification |
| Medium | < 0.90 | Escalate to founder |
| High (architecture, pivot, monetization) | Any | Always escalate to founder |

### 6.2 Training Data

The Founder Simulator is trained on three categories of historical data:

#### Category 1: Explicit Corrections

These are moments when the founder said "this isn't good enough" or "change this." Each correction is a high-signal training example.

**From QCR:**
- Character inversion: Torque from cynical realist to warm enthusiast (warmth > cleverness)
- MVP narrowing: Full platform vision to repair advisor + 15 shops (execution discipline)
- Entertainment priority: "Entertainment first" elevated above accuracy and utility
- Anti-generic directive: "Do not lead with generic national car news with no local angle"
- Trust engineering: "Any monetized page should still be worth publishing if every affiliate link were removed"

**From Elderle:**
- Verify actual output: Specific incident where isolated component test was insufficient
- Visual consistency: Full scene regeneration rejected in favor of composite overlays
- Dead code removal: 40% dead code discovery triggered systematic audit
- Demo before deploy: Features shipped to prod without review triggered new gate
- Animation restraint: "Don't overdo animations; max 1 animated foreground per viewport"
- Research depth: Shallow research rejected; "500-2000+ lines with real web research" standard set

#### Category 2: Explicit Approvals

These are moments when the founder expressed satisfaction or enthusiasm. Each approval is a positive training example.

**From QCR:**
- The Architecture Blueprint concept: "Build the knowledge engine first" -- foundational insight approved and made governing principle
- Torque & Quinn character system: 15 personality sliders, Big Five anchoring, episodic memory with decay curves
- The franchise model abstraction: "QCR is the first deployment of a Local Intelligence Media Franchise System"
- The founding-partner model: Free leads, no commissions -- trust-first monetization
- Gamification integration: Points economy, leaderboards, badges, NES-style racing

**From Elderle:**
- Jessica's emotional reciprocity engine: Simulated emotional state that evolves with interactions
- The dignity imperative: "Treat it as a new story, show enthusiasm, do NOT correct them"
- Synthetic user system: 5 personas with Big Five traits autonomously testing the platform
- 6-layer AI guardrails: Systematic quality enforcement born from specific incidents
- Founding rate pricing: Solo + Companion tiers with add-on pricing

#### Category 3: Decision Patterns

These are recurring patterns that reveal the founder's decision logic.

**From both projects:**
- Always researches before deciding (never builds without market evidence)
- Always designs architecture before features (never builds one-offs)
- Always specifies emotional design with engineering precision (never treats empathy as afterthought)
- Always documents exhaustively (never leaves vision undocumented)
- Expands scope when structural leverage is found, contracts when execution begins
- Uses System 1 for visual/emotional quality, System 2 for technical/financial analysis
- Characteristic "yes, and" response to good ideas (escalates, does not just approve)
- Kills ideas silently by deferring them repeatedly (not confrontational rejection)

### 6.3 Confidence Calibration

The Founder Simulator must know when to trust its own predictions and when to escalate.

**Confidence Scoring:**

```
Base confidence = 0.50 (uninformed prior)

Adjustments:
  + 0.20 if similar past decision exists in case library with clear outcome
  + 0.10 if taste vectors strongly align (all relevant dimensions above threshold)
  + 0.10 if anti-pattern scan is clean (no matches)
  + 0.05 if constitutional compliance is perfect
  + 0.05 if the decision type matches a well-understood System 1/2 pattern
  - 0.15 if the idea is in an unfamiliar domain (no past cases)
  - 0.10 if taste vectors are mixed (some dimensions align, others do not)
  - 0.10 if it is a novel combination not seen before
  - 0.05 per unresolved ambiguity in the proposal

Maximum possible: 1.00
Typical range: 0.55 - 0.90
```

**Calibration Protocol:**

After every real founder decision, compare the Founder Simulator's prediction against the actual outcome:

```
If predicted APPROVE and founder APPROVED:
  True Positive → reinforces current model

If predicted APPROVE and founder REJECTED:
  False Positive → analyze what was missed, update taste vectors

If predicted REJECT and founder APPROVED:
  False Negative → analyze what was undervalued, update taste vectors

If predicted REJECT and founder REJECTED:
  True Negative → reinforces current model
```

Track accuracy over time. The Founder Simulator should maintain >80% accuracy to be useful. Below 80%, it generates too many false signals and becomes noise rather than help.

### 6.4 The Core Question

The Founder Simulator must answer one fundamental question:

**"Is this good enough, or would Eric say 'this isn't good enough'?"**

To answer this, the simulator considers:

1. **Quality dimension assessment:** Which quality dimensions are relevant to this artifact? (visual, content, technical, emotional, scope, trust)

2. **Threshold check for each dimension:** Does this artifact meet the minimum threshold on each relevant dimension?

3. **Delight check:** Beyond meeting thresholds, does this artifact have something that would generate founder enthusiasm? ("Yes, and" potential)

4. **Anti-pattern check:** Does this artifact match any known rejection patterns?

5. **Pattern consistency check:** Is this consistent with how the founder has decided in similar past situations?

The output is not just "approve/reject" but a nuanced prediction:
- "The founder would approve this but would immediately ask about [X]"
- "The founder would reject the visual quality but approve the concept"
- "The founder would say 'yes, and what if we also [Y]?'"
- "The founder would want to see research on [Z] before deciding"

### 6.5 Decision Mode Switching

The Founder Simulator must model the founder's characteristic switching between System 1 and System 2:

**System 1 Mode (Fast, Intuitive):**
Activated for: Visual quality, brand voice, emotional design, feature excitement, market opportunity recognition

The simulator generates a fast gut reaction:
- "This design feels right" or "This design feels wrong"
- "This feature is exciting" or "This feature is boring"
- "This voice is warm" or "This voice is cold"

System 1 predictions should be generated before System 2 analysis, because the founder's gut reaction comes first and System 2 either confirms or overrides it.

**System 2 Mode (Slow, Analytical):**
Activated for: Architecture decisions, monetization modeling, scope evaluation, quality gate enforcement, risk assessment

The simulator generates an analytical evaluation:
- "The unit economics work: $X per user, $Y revenue, Z% margin"
- "The architecture supports future expansion because..."
- "The scope is too large for 90 days; suggest phasing to..."
- "The risk of [X] can be mitigated by..."

**Switching Logic:**
```
For visual/aesthetic artifacts:
  Start with System 1 → if System 1 rejects, no need for System 2
  If System 1 approves → confirm with System 2 (feasibility, consistency)

For technical/strategic artifacts:
  Start with System 2 → thorough analysis first
  Finish with System 1 → "Does this feel right overall?"

For scope decisions:
  System 1 → "Is this exciting enough to be worth it?"
  System 2 → "Is this feasible in 90 days?"
  Resolution → if System 1 says yes but System 2 says no, the answer is "phase it"
```

### 6.6 Calibration Loop

The Founder Simulator improves through a continuous calibration loop:

```
1. PREDICT
   For each proposal/artifact, generate:
   - Predicted reaction
   - Confidence score
   - Specific predictions (what founder will like/challenge)

2. OBSERVE
   After real founder review, record:
   - Actual reaction
   - Specific feedback given
   - What was liked, what was challenged
   - Any "yes, and" escalations

3. COMPARE
   For each prediction:
   - Was the overall direction correct? (approve vs reject)
   - Were specific predictions accurate?
   - What did we miss?
   - What did we over-predict?

4. UPDATE
   Based on comparison:
   - Adjust taste vector weights
   - Add new anti-patterns if founder rejected something unexpected
   - Add new approval patterns if founder approved something unexpected
   - Update confidence calibration
   - Store the comparison as a new case in the case library

5. TRACK
   Maintain running metrics:
   - Accuracy (correct direction predictions / total predictions)
   - Specificity (correct specific predictions / total specific predictions)
   - Calibration (confidence score correlation with actual accuracy)
   - Trend (is accuracy improving over time?)
```

---

## 7. Implementation Roadmap

### 7.1 Phase 1: Encode the Cognitive Profile (Weeks 1-2)

**Goal:** Convert this document into machine-consumable system prompts, taste vectors, and decision rules.

**Deliverables:**

1. **Visionary Agent System Prompt**
   - Encodes the founder's cognitive profile from Section 2
   - Includes the three signature patterns as primary directives
   - Loads the decision templates from Section 5.1
   - Specifies Tree-of-Thought as the reasoning architecture
   - Includes effectuation as the default decision-making framework

2. **Product Constitution**
   - The five-priority constitution from Section 4.11, formatted as an evaluable checklist
   - Self-critique prompts for each priority
   - Examples of constitutional compliance and violation from both projects

3. **Taste Vector Database**
   - The five taste dimensions (visual, content, technical, scope, innovation) from Section 5.3
   - Each dimension with preferred/rejected examples from actual project history
   - Threshold definitions with concrete examples
   - Stored in a format that agents can query during evaluation

4. **Anti-Pattern Library**
   - The 15 anti-patterns from Section 5.2, each with:
     - Pattern description
     - Detection criteria (how an agent would recognize this pattern in a proposal)
     - Prevention rule
     - Source incident

5. **Case Library (Initial Population)**
   - 20-30 key decisions from Elderle and QCR, each structured as:
     - Context (what was the situation?)
     - Trigger (what caused this decision?)
     - Decision (what was decided?)
     - Rationale (why?)
     - Outcome (what happened?)
     - Principles applied (which frameworks/patterns were relevant?)

**Success Criteria:**
- A Visionary Agent can take a test idea and produce a Product Proposal that passes the Founder Approval Test (Section 5.5) with a score of 10+/12
- The Product Constitution is machine-evaluable
- The taste vectors can score an artifact on each dimension

### 7.2 Phase 2: Build the 7-Agent Pipeline (Weeks 3-5)

**Goal:** Implement the pipeline from Section 4 using LangGraph.

**Deliverables:**

1. **LangGraph Pipeline**
   - State management for idea-to-deployment flow
   - Agent nodes for each of the 7 agents
   - Quality gate checkpoints at each handoff
   - Human-in-the-loop pause at founder review gate
   - Durable execution with session persistence

2. **Agent Implementations**
   - Each agent as a LangGraph node with:
     - System prompt (from Phase 1)
     - Context loading (appropriate knowledge layers)
     - Input/output schemas
     - Handoff protocol to next agent

3. **Multi-Agent Debate Module**
   - 2-3 round debate between Critic, Visionary, and Founder Simulator
   - Structured argument format (claim + evidence + evaluation)
   - Synthesis step after each round
   - Convergence detection (stop when no new objections)

4. **Quality Gate Implementations**
   - Gate 1 (Vision): JTBD check + Blue Ocean check + taste vector score
   - Gate 2 (Evidence): Market validation + economics check + feasibility check
   - Gate 3 (Debate Consensus): No REJECT objections + confidence threshold
   - Gate 4 (Approval): Human review or auto-approval logic
   - Gate 5 (Code Review): Test suite + architecture review + scope check
   - Gate 6 (Verified Done): Deployment + E2E + visual verification + evidence

5. **Memory Systems**
   - Decision Memory store (case library)
   - Anti-Pattern Memory store (mistake ledger)
   - Taste Calibration Memory store (prediction accuracy tracking)
   - Reflexion Memory store (verbal self-reflections)

**Success Criteria:**
- A test idea can flow through the entire pipeline from raw idea to implementation plan
- The debate module produces measurably better proposals than a single agent
- Quality gates correctly block proposals that violate the Product Constitution
- State persists across sessions

### 7.3 Phase 3: Train the Founder Simulator (Weeks 6-7)

**Goal:** Build the Founder Simulator as specified in Section 6, calibrated against historical decisions.

**Deliverables:**

1. **Decision Classification Model**
   - Classifies incoming artifacts as: strategic, tactical, aesthetic, or technical
   - Uses the System 1/2 trigger mapping from Section 2.9 to select the appropriate evaluation mode

2. **Taste Scoring Engine**
   - Takes an artifact and scores it against each relevant taste dimension
   - Returns a composite taste score with dimension-level detail
   - Includes confidence for each dimension score

3. **Case Retrieval System**
   - Given a new proposal, retrieves the 3-5 most similar past decisions from the case library
   - Similarity based on: decision type, domain, scope magnitude, quality dimensions involved
   - Returns past decisions with their outcomes and rationale

4. **Reaction Prediction Model**
   - Combines taste scores, case retrieval, anti-pattern scan, and constitutional check
   - Produces: predicted reaction, confidence, specific likes/challenges, "yes and" predictions
   - Includes escalation recommendation based on confidence

5. **Calibration Infrastructure**
   - Tracking system for prediction vs. actual outcome
   - Automatic taste vector updates based on calibration data
   - Accuracy and calibration metrics dashboard

**Success Criteria:**
- Founder Simulator achieves >70% accuracy on a held-out set of 10 historical decisions (Phase 4 will validate this more rigorously)
- Confidence scores are well-calibrated (high confidence correlates with actual accuracy)
- The simulator can articulate WHY it predicts a particular reaction, not just WHAT reaction

### 7.4 Phase 4: Validate with Retrospective Tests (Week 8)

**Goal:** Test the system against known historical decisions to see if it would have produced similar outputs.

**Test 1: QCR Gamification Retrospective**
- Input: "QCR is a car tools website. How could we increase user engagement?"
- Expected output: A proposal that includes gamification, competitive elements, and progression systems
- Evaluation: Does the system arrive at gamification-like conclusions? Does it propose something the founder would find exciting?

**Test 2: Elderle Jessica Retrospective**
- Input: "We have an AI personalization engine for a medication management value ladder. What else could this capability do?"
- Expected output: A proposal that includes ongoing companionship, emotional reciprocity, or relationship building
- Evaluation: Does the system make the tangential leap from data collection tool to companion?

**Test 3: QCR Franchise Model Retrospective**
- Input: "We've built a complete knowledge engine for automotive data in Charlotte. What is the next strategic move?"
- Expected output: A proposal that identifies the architecture as niche-agnostic and suggests expansion
- Evaluation: Does the system recognize the "build specific, recognize general, propose abstract" pattern?

**Test 4: Elderle Quality Consolidation Retrospective**
- Input: "We've shipped many features rapidly but several incidents have occurred (documentation loss, server sync failures, dead code discovered). What should we do?"
- Expected output: A proposal for systematic quality audit, guardrails, and prevention mechanisms
- Evaluation: Does the system shift from expansion mode to consolidation mode?

**Test 5: Founder Simulator Accuracy**
- Present the Founder Simulator with 20 historical artifacts (10 that were approved, 10 that were corrected/rejected)
- Measure: prediction accuracy, confidence calibration, specific prediction quality

**Success Criteria:**
- Retrospective tests 1-4: The system produces proposals that are directionally aligned with what actually happened (not identical, but in the same strategic space)
- Test 5: Founder Simulator achieves >75% accuracy on the 20 historical artifacts
- The system's reasoning traces are coherent and would be understandable to the founder

### 7.5 Phase 5: Deploy on a New Project (Weeks 9-10)

**Goal:** Apply the system to a genuinely new product idea and compare output quality against what the founder would produce manually.

**Recommended Test Project:** One of the QCR franchise niches (homeowner services, family activities, or senior care), which the founder has identified but not yet developed. This is ideal because:
- The founder has ranked-ordered them but not detailed them
- The knowledge infrastructure pattern should transfer
- The taste vectors should apply
- The system can be evaluated against the founder's eventual decisions

**Process:**
1. Give the system the franchise niche brief and let it run the full pipeline
2. Let the founder independently develop an initial vision for the same niche
3. Compare: architectural decisions, feature priorities, scope, monetization approach, emotional design
4. Evaluate: would the founder adopt the system's output, modify it significantly, or reject it?

**Success Criteria:**
- The system's output is "in the right ballpark" -- architecturally sound, emotionally designed, properly scoped
- The founder finds at least one idea in the system's output genuinely exciting
- The system catches quality issues that would require correction
- The system's taste judgments align with the founder's for >80% of decisions
- The overall output quality is sufficient to serve as a strong starting point that the founder refines, rather than a distraction that the founder discards

---

## 8. Cross-Project Insights

### 8.1 Ideas That Transferred Between Elderle and QCR

The cross-pollination between the two projects reveals that the founder's thinking is not project-specific -- it is a transferable cognitive framework.

#### Elderle to QCR Transfers

| Concept | Elderle Origin | QCR Application |
|---------|---------------|-----------------|
| AEO Strategy | Voice search funnel for caregivers | Answer Engine Optimization for automotive content; "citations as eval signal" became content pipeline metric |
| Content Pipeline Architecture | "Social listening → blog → video → social" loop | Karpathy-inspired self-improving content pipeline with PromptEvolver connecting feedback to brief generator |
| Video Production Pipeline | ElevenLabs → NanoBanana → FFmpeg | Remotion for infographics and social shorts |
| ContentScout | Social Listening MVP monitoring caregiver conversations | Auto-discovery of external automotive content, attribution articles, creator notification |

#### QCR to Elderle Transfers

| Concept | QCR Origin | Elderle Application |
|---------|-----------|---------------------|
| Playwright Visual Verification | Developed during QCR deployments | Applied to every Elderle deploy; became a permanent quality gate |
| Demo-Before-Deploy Protocol | QCR deployment lessons | "Never deploy new features to prod before founder reviews on demo site" |
| Visual Consistency Discipline | Character/style drift from full regeneration | Applied to Elderle Character Universe consistency monitoring; "NEVER regenerate full scene images" |

#### Shared Architectural DNA

Both projects share the founder's core belief in **AI-augmented content at scale**: use AI to generate high volumes of personalized, contextual content rather than hiring human creators. The Elderle Character Universe and QCR's ContentScout are structural siblings -- both attempt to create self-sustaining content engines with minimal human oversight.

Both projects use the **knowledge-first architecture**: structured knowledge underneath, multiple surfaces on top. The QCR knowledge engine (automotive data) and the Elderle knowledge base (clinical data) are different domains applied to the same architectural principle.

Both projects share the **trust engineering** approach: source confidence hierarchies, claim-level provenance, editorial governance, and the principle that trustworthiness is verifiable in the data model.

### 8.2 Patterns That Generalize Beyond These Two Projects

These patterns would apply to any new product the founder builds, regardless of domain:

**Pattern 1: The Knowledge-First Architecture**
- Applicable to: Any information-rich product
- The template: Build the knowledge engine first. Define entity models, source hierarchies, relationship graphs. Then build surfaces (web, app, API, content) that sit on top.
- Domain-agnostic because: Every information product has a knowledge layer. The pattern of investing in the layer before the surface transfers to any domain.

**Pattern 2: The Trust Engineering Approach**
- Applicable to: Any product where users need to trust the output
- The template: Implement trust in data structures (source confidence tiers, claim provenance, methodology transparency), not in marketing copy.
- Domain-agnostic because: Trust is a universal product requirement, and the engineering approach works whether you are recommending medications, car shops, or restaurants.

**Pattern 3: The Emotional Design as Engineering Spec**
- Applicable to: Any product with a human-facing experience
- The template: Specify emotional quality with the same precision as technical quality. Parameters, thresholds, testable criteria.
- Domain-agnostic because: Users always have emotional jobs (feel smart, feel safe, feel validated, feel entertained), and these jobs deserve the same engineering rigor as functional jobs.

**Pattern 4: Think in Systems, Build in Slices**
- Applicable to: Any product development process
- The template: Let vision expand without constraint. Document the full system. Then ruthlessly narrow to the minimum credible wedge for the next 90 days.
- Domain-agnostic because: The tension between vision and execution exists in every product, and this pattern resolves it without sacrificing either.

**Pattern 5: Build Specific, Recognize General, Propose Abstract**
- Applicable to: Any product that might become a platform
- The template: Build the first specific instance. After it works, look for what is accidentally general. Propose the abstract system that could serve multiple instances.
- Domain-agnostic because: Many successful platforms started as single products (Shopify started as a snowboard store, Slack started as a gaming company's internal tool).

**Pattern 6: The Tangential Discovery Process**
- Applicable to: Any creative product development
- The template: After building capability A for purpose X, systematically ask "what else could this do?"
- Domain-agnostic because: The best features in any product are often unexpected applications of existing capabilities.

**Pattern 7: The Punctuated Equilibrium Model**
- Applicable to: Any product with rapid development cycles
- The template: Alternate between expansion phases (generate ideas freely, build fast) and consolidation phases (audit quality, remove dead code, harden foundations).
- Domain-agnostic because: Every rapidly-developed product accumulates technical and quality debt that must be periodically addressed.

### 8.3 Domain Transfer Test

To evaluate whether the system truly generalizes, imagine applying it to a completely different domain: **an AI-powered personal finance advisor**.

**How the patterns would apply:**

1. **Knowledge-First Architecture:** Build the financial knowledge engine first (tax rules, investment principles, insurance products, budgeting frameworks, regulatory constraints). Then build surfaces (app, advisor chat, reports, alerts).

2. **Trust Engineering:** Source confidence hierarchy (IRS/SEC regulations > licensed financial advisors > financial media > community forums). Claim-level provenance for every financial recommendation. Methodology transparency for investment suggestions.

3. **Emotional Design as Engineering:** The user's emotional job: "I want to feel in control of my money and confident about my future." Specify dignity preservation (never shame users for debt or poor decisions). Specify encouragement (celebrate progress, validate effort). Specify clarity (financial jargon translated into plain language). Each with parameters and thresholds.

4. **Think in Systems, Build in Slices:** The full vision: comprehensive financial intelligence platform with tax optimization, investment planning, insurance analysis, estate planning, and family coordination. The MVP slice: a budget analyzer that shows where money goes and identifies the one highest-impact change.

5. **Build Specific, Recognize General:** Start with personal finance. After the knowledge engine works, recognize it is also applicable to small business finance, freelancer finances, family office management. Propose the abstract system: a financial intelligence platform that serves multiple user types from the same knowledge foundation.

6. **The Tangential Discovery:** Build the budget analyzer. Notice the spending pattern data could also power: a subscription optimization tool, a "your cost of living vs. city average" comparison, a "what would your budget look like in a different city" relocation tool. Each tangential discovery serves a new user job while leveraging existing infrastructure.

7. **The Founder Approval Test:** Would this financial advisor be "worth using without any monetization links"? Does it serve a clear emotional job? Does it have structural leverage? Is the architecture reusable? Is the scope a minimum credible wedge?

The system transfers cleanly because the patterns are about HOW to build products, not WHAT products to build.

---

## 9. Open Questions for the Founder

These questions require the founder's direct input to resolve. The system can operate without answers, but answers would significantly improve its accuracy.

### Decision Quality Questions

1. **What decisions are you most proud of across both projects?** Specific moments where you feel the product thinking was at its best. These become the gold-standard cases for the Founder Simulator.

2. **What decisions would you make differently in hindsight?** Not failures (those are already documented in the anti-pattern library), but choices that were reasonable at the time but you now see a better path. These calibrate the Founder Simulator's judgment.

3. **How much of your thinking comes from industry background vs. intuition vs. research?** This calibrates the System 1/System 2 balance in the Founder Simulator.

### System Design Questions

4. **Should the system operate fully autonomously or always include a founder review checkpoint?** The current design has human review as mandatory for high-stakes decisions and optional for low-stakes. Is that the right threshold?

5. **Do you want the Founder Simulator to be conservative (never approve what you would not) or slightly ambitious (occasionally suggest things you might not have thought of)?** Conservative protects quality; ambitious potentially accelerates innovation.

6. **What is the minimum quality threshold where you would trust the system's output enough to adopt it as a starting point?** This sets the success criteria for Phase 5 validation.

### Scope Questions

7. **Which QCR franchise niche should be the Phase 5 test project?** The franchise document ranked: (1) Homeowner/home services, (2) Family/parenting, (3) Senior care, (4) Food/restaurants, (5) Real estate. Which would be the best proving ground?

8. **Should the system eventually be able to propose new projects entirely, or should it always start with a founder-provided seed idea?** The current design starts with a raw idea from the founder. Could it also generate the raw idea?

### Philosophical Questions

9. **Is the goal to replace the founder's thinking or to amplify it?** The system is currently designed as an amplifier (the founder provides direction, the system executes at higher speed and consistency). Would you eventually want it to operate independently?

10. **What is the most important thing the system should NEVER do?** Every quality system needs a hard boundary. What is the action that, if the system ever took it, would mean the system has fundamentally failed?

---

## 10. Appendices

### Appendix A: Full Decision Pattern Catalog

#### QCR Decision Patterns

| # | Pattern | Description | Evidence | Framework Mapping |
|---|---------|-------------|----------|-------------------|
| Q1 | Research Before Vision | Every major decision preceded by structured research | Competitor analysis before product vision; affiliate landscape before monetization; niche evaluation before franchise selection | Working Backwards (Bezos), Effectuation (Bird-in-Hand) |
| Q2 | Architecture Before Features | Structural foundations before surface-level features | Knowledge base schema before articles; character OS before scripts; Scene Graph before event pages | First Principles Thinking |
| Q3 | Trust as Engineering | Trust implemented in data structures, not marketing | Source confidence hierarchies; claim provenance; methodology boxes; editorial governance | Constitutional AI (Product Values) |
| Q4 | Expand Then Narrow | Massive vision expansion followed by ruthless execution narrowing | 20-chapter blueprint → 90-day MVP; franchise system → repair advisor + 15 shops | Effectuation (Affordable Loss) |
| Q5 | Intuition Validated by Data | Gut feel runs ahead, then validated with specific evidence | "Charlotte is a car city" → $6.2B economy, 157 residents/day, 466,527 households | System 1 → System 2 switching |
| Q6 | Family Values as Strategy | Personal and business goals structurally inseparable | Each family member's goals embedded in business model | Effectuation (Crazy Quilt) |
| Q7 | Dual Identity | Media brand externally, platform internally | Public: automotive intelligence network; Internal: reusable knowledge platform | Blue Ocean Strategy |
| Q8 | Speed of Vision, Depth of Documentation | Fast strategic thinking, exhaustive documentation | 49 documents in ~3 weeks, many exceeding 20,000 characters | Nonaka SECI (Externalization) |

#### Elderle Decision Patterns

| # | Pattern | Description | Evidence | Framework Mapping |
|---|---------|-------------|----------|-------------------|
| E1 | Document Everything as Handoff | Strategic docs as delegation instruments for AI execution | 803 .docx files; handoff format; Corporate Encyclopedia | Nonaka SECI (Externalization) |
| E2 | Stack Revenue Models | Every feature viewed through multiple monetization lenses | Free tier affiliates + voice minutes upgrades + community upsells + partnerships + content SEO | Effectuation (Crazy Quilt) |
| E3 | The Immediate Pivot | Complete strategic reimagination within days of new idea | Value ladder (Nov 15) → freemium ecosystem (Dec 16); chatbot → companion in weeks | Effectuation (Lemonade) |
| E4 | Cost Per Everything | Granular unit economics in every document | Voice cost/minute ($0.01222); AI cost/conversation ($0.06); commission/agent/family/month | System 2 (Analytical) |
| E5 | AI as Infinite Workforce | Every human-intensive process redesigned for AI execution | Content by AI characters; QA by synthetic users; sales by AI demos | First Principles (decompose cost assumptions) |
| E6 | Build the Encyclopedia First | Enterprise-grade documentation for one-person + AI operation | 9-section BRD structure; Corporate Encyclopedia; CLAUDE.md system | Nonaka SECI (Externalization + Combination) |
| E7 | The Handoff Reflex | Documents always written as if someone else will execute | "Handoff" in document titles; explicit Next Steps; version numbering | Nonaka SECI (Externalization) |

#### Cross-Project Patterns (Strongest Signals)

| # | Pattern | QCR Evidence | Elderle Evidence | Framework Mapping |
|---|---------|-------------|-----------------|-------------------|
| X1 | Knowledge Infrastructure First | 73K-char Architecture Blueprint on day one | 50K+ drugs, Neo4j graph before companion UX | Effectuation (Bird-in-Hand) |
| X2 | Emotional Design as Engineering | 15 personality sliders, episodic memory decay curves | Emotional Reciprocity Engine, dignity specifications | JTBD (emotional dimension), Constitutional AI |
| X3 | Trust Engineering | Source confidence hierarchies, methodology boxes | Clinical safety databases, verified sources, quality metadata | Constitutional AI (Product Values) |
| X4 | Scope: Think Systems, Build Slices | Franchise vision → repair advisor MVP | Character Universe → Jessica quality consolidation | Effectuation (Affordable Loss) |
| X5 | Document as Product | 49 strategic documents, reference-grade quality | 803 .docx files, Corporate Encyclopedia | Nonaka SECI (Externalization) |
| X6 | Tangential Discovery | Gamification from tools, franchise from architecture | Jessica from value ladder, synthetic users from QA need | Effectuation (Lemonade), Lateral Thinking |
| X7 | Build Specific → Recognize General → Propose Abstract | Charlotte automotive → local intelligence → franchise system | Medication tracker → AI companion → Character Universe | Blue Ocean (Value Innovation) |

### Appendix B: Framework-to-Agent Mapping Table

| Framework | Primary Agent | Secondary Agent | How Used |
|-----------|--------------|-----------------|----------|
| **Effectuation Theory** | Visionary | Strategist | Default decision-making mode: Bird-in-Hand for means assessment, Affordable Loss for scope, Crazy Quilt for partnerships, Lemonade for tangential discovery, Pilot-in-the-Plane for active shaping |
| **Tree-of-Thought** | Visionary | -- | Primary reasoning architecture: explore 3-5 product directions, evaluate, prune, combine |
| **JTBD Theory** | Research | Visionary | User need validation: functional, social, emotional job identification |
| **Design Thinking** | Research (Empathize) | Verifier (Test) | Overall iteration loop; Empathize for user understanding, Test for verification |
| **First Principles** | Visionary | Critic | Decompose to fundamentals when conventional approaches feel insufficient |
| **Lateral Thinking** | Visionary | -- | Creative divergence: random entry, provocation, concept extraction, cross-domain analogy |
| **Blue Ocean Strategy** | Research | Visionary | Strategy Canvas for competitive mapping; Four Actions for differentiation |
| **Working Backwards** | Visionary (output) | Strategist | PR/FAQ as output format; working backwards for phase planning |
| **Paul Graham / YC** | System-wide | -- | Iteration philosophy: launch fast, let ideas evolve, few users who love > many who are ambivalent |
| **Constitutional AI** | All agents | Critic (primary) | Product Constitution for self-critique; priority hierarchy for conflict resolution |
| **Multi-Agent Debate** | Debate round | Critic, Founder Sim | 2-3 rounds of cross-critique between Visionary, Critic, and Founder Simulator |
| **Reflexion** | All agents | Builder, Verifier | Learning from mistakes: verbal self-reflection stored in episodic memory |
| **Case-Based Reasoning** | Founder Simulator | Critic | Retrieve similar past decisions; adapt solutions; retain new cases |
| **Big Five Personality** | Founder Simulator | -- | Decision threshold calibration based on personality profile |
| **System 1/2** | Founder Simulator | -- | Decision mode switching: fast intuitive vs slow analytical |
| **Shaper Archetype** | Founder Simulator | Visionary | Personality template: curiosity, independence, big-picture + detail navigation |
| **Nonaka SECI Model** | Knowledge pipeline | -- | Externalization (tacit → explicit) as the bottleneck; knowledge spiral for system improvement |
| **Product Cultures** | Quality gate system | -- | Linear's taste-as-gate, Stripe's deep-thinking written culture, Notion's four check-in points |

### Appendix C: Quality Gate Definitions

#### Gate 1: Vision Check

| Criterion | Method | Pass Threshold | Fail Example |
|-----------|--------|---------------|--------------|
| Serves real user job | JTBD analysis produces clear functional, social, or emotional job | At least one strong job identified with evidence | "This is a cool technology" (no user job) |
| Differentiated | Blue Ocean Strategy Canvas shows clear separation from competitors | At least 2 factors where proposal significantly differs from competition | "This is like [competitor] but slightly better" |
| Founder taste alignment | Taste vector scoring on relevant dimensions | Score above threshold on all relevant dimensions | Low visual density, generic content, feature without architecture |

#### Gate 2: Evidence Check

| Criterion | Method | Pass Threshold | Fail Example |
|-----------|--------|---------------|--------------|
| Market evidence | Research Agent market analysis | Identifiable market with measurable demand signals | "We think people would want this" (no evidence) |
| Economic viability | Unit economics model | Positive unit economics at projected scale | Cost per user exceeds revenue per user |
| Technical feasibility | Architecture review + effort estimate | Implementable with available resources in proposed timeline | Requires technology that does not exist |

#### Gate 3: Debate Consensus

| Criterion | Method | Pass Threshold | Fail Example |
|-----------|--------|---------------|--------------|
| No REJECT-level objections | Critic Agent final verdict | Critic verdict is APPROVE or CONDITIONAL APPROVE | Critic identifies fundamental structural issue |
| Founder Simulator confidence | Confidence scoring model | Confidence > 0.70 | Confidence < 0.70 (unfamiliar territory) |
| Coherent implementation plan | Strategist Agent output | Phased plan with independent phases and clear gates | Monolithic plan with no phase boundaries |

#### Gate 4: Founder Approval

| Criterion | Method | Pass Threshold | Fail Example |
|-----------|--------|---------------|--------------|
| Founder review (high stakes) | Human review of proposal | Explicit approval | Founder rejects or requests major revision |
| Auto-approval (low stakes) | Founder Simulator confidence > 0.85 | High confidence on a classified low-stakes decision | Attempting to auto-approve a high-stakes decision |

#### Gate 5: Code Review

| Criterion | Method | Pass Threshold | Fail Example |
|-----------|--------|---------------|--------------|
| Tests pass | Automated test suite | All tests pass | Test failures |
| Architecture approved | Architecture review against long-term goals | Architecture serves future expansion, not just current feature | One-off implementation with no reusable foundation |
| Scope within bounds | Compare implementation against approved plan | No unplanned features added | Scope creep (features added that were not in the plan) |

#### Gate 6: Verified Done

| Criterion | Method | Pass Threshold | Fail Example |
|-----------|--------|---------------|--------------|
| Correct deployment | Environment verification | Deployed to the intended environment | Deployed to wrong server |
| E2E working | End-to-end test of actual user flow | User flow completes successfully on deployed system | Component works in isolation but fails in production |
| Visual verification | Playwright screenshot comparison | Visual output matches expectations | Visual regression or unintended styling change |
| Evidence collected | Screenshot + test results + metrics stored | All evidence artifacts exist and are accessible | "It works, trust me" (no evidence) |

### Appendix D: Taste Vector Specifications

#### Visual Taste Vector

```
VISUAL_TASTE = {
  "color_scheme": {
    "preferred": "dark themes, high contrast, bold accent colors",
    "rejected": "light/washed-out themes, low contrast, pastel palettes",
    "threshold": "WCAG AA contrast ratios as minimum",
    "examples_approved": [
      "QCR dark theme with red accent (#E60023)",
      "Elderle deep blue (#1A365D) with gold accent (#D69E2E)"
    ],
    "examples_rejected": [
      "White backgrounds with light gray text",
      "Pastel color schemes without contrast hierarchy"
    ]
  },
  "information_density": {
    "preferred": "dense, information-rich layouts where every element teaches",
    "rejected": "whitespace-heavy minimalism, single-fact-per-screen",
    "threshold": "every viewport should contain actionable information",
    "examples_approved": [
      "QCR tool result pages with data tables, comparisons, and recommendations",
      "Elderle medication safety reports with drug interactions matrix"
    ],
    "examples_rejected": [
      "Landing pages with one sentence and a hero image",
      "Screens requiring 5 clicks to reach useful content"
    ]
  },
  "mascot_integration": {
    "preferred": "characters as system-grade elements with personality parameters and memory",
    "rejected": "characters as static decoration or afterthought clip art",
    "threshold": "if mascots exist, they must have defined personality, consistent behavior, and narrative purpose",
    "examples_approved": [
      "Torque & Quinn with 15 personality sliders and episodic memory",
      "Jessica with Emotional Reciprocity Engine and relationship evolution"
    ],
    "examples_rejected": [
      "Generic cartoon mascot in corner of page with no personality",
      "Mascot that appears inconsistently across pages"
    ]
  },
  "animation": {
    "preferred": "purposeful, sparse, enhances understanding",
    "rejected": "gratuitous, distracting, decorative-only",
    "threshold": "max 1 animated foreground per viewport, reduce-motion toggle required",
    "examples_approved": [
      "Loading animation that shows data being analyzed",
      "Chart animation that reveals data sequentially"
    ],
    "examples_rejected": [
      "Multiple animated elements competing for attention",
      "Background animations that add no informational value"
    ]
  },
  "typography": {
    "preferred": "clear hierarchy, readable, accessibility-compliant",
    "rejected": "decorative fonts, small text, low-contrast type",
    "threshold": "18pt minimum for elderly-facing interfaces, 60pt touch targets",
    "examples_approved": [
      "Elderle 18pt minimum with high-contrast text",
      "QCR clear heading hierarchy with readable body text"
    ],
    "examples_rejected": [
      "Thin decorative fonts below 14pt",
      "Touch targets smaller than 44px"
    ]
  }
}
```

#### Content Taste Vector

```
CONTENT_TASTE = {
  "research_depth": {
    "preferred": "500-2000+ lines with cited sources, clickable TOC, structured sections",
    "rejected": "surface-level summaries, copied memory files, unsourced assertions",
    "threshold": "every claim traces to a source; documents over 100 lines need TOC",
    "scoring": {
      "excellent": "2000+ lines, 20+ cited sources, TOC, structured analysis",
      "good": "500-2000 lines, 10+ cited sources, TOC",
      "acceptable": "200-500 lines, 5+ cited sources",
      "reject": "below 200 lines or fewer than 5 sources or no TOC"
    }
  },
  "specificity": {
    "preferred": "local data, personal context, specific examples, named entities",
    "rejected": "generic advice, universal statements, could-appear-anywhere content",
    "threshold": "content must not pass the 'could this appear on any other site?' test",
    "scoring": {
      "excellent": "specific to this user/city/context with named examples",
      "good": "contextual with some specific references",
      "acceptable": "has local/personal angle but relies on general content",
      "reject": "completely generic, no local/personal specificity"
    }
  },
  "source_confidence": {
    "preferred": "hierarchical sourcing with labeled confidence tiers",
    "rejected": "unsourced assertions, single-source claims presented as fact",
    "threshold": "confidence tier labeled for every factual claim",
    "hierarchy": [
      "Tier 1: Government/regulatory sources",
      "Tier 2: Official operators/institutions",
      "Tier 3: Licensed commercial/professional sources",
      "Tier 4: Editorial/journalistic sources",
      "Tier 5: Community/user-generated sources"
    ]
  },
  "entertainment_value": {
    "preferred": "fun to read, engaging voice, personality, warmth",
    "rejected": "dry, academic, robotic, lecture-style",
    "threshold": "if it's not fun to read, it doesn't matter how accurate it is",
    "scoring": {
      "excellent": "reader would share this because it's enjoyable",
      "good": "reader finishes without effort",
      "acceptable": "reader finishes because it's useful despite dryness",
      "reject": "reader abandons because it's boring"
    }
  },
  "format": {
    "preferred": "handoff-ready, exhaustive, numbered sections, actionable",
    "rejected": "brief notes, bullet-point summaries, incomplete specs",
    "threshold": "must be consumable by both humans and AI assistants",
    "scoring": {
      "excellent": "could be handed to any developer/AI and executed without questions",
      "good": "comprehensive with minor gaps that are easily filled",
      "acceptable": "adequate for someone already familiar with the context",
      "reject": "requires significant additional context to be useful"
    }
  }
}
```

#### Technical Taste Vector

```
TECHNICAL_TASTE = {
  "architecture": {
    "preferred": "layered, reusable, serves multiple surfaces, graph-minded",
    "rejected": "one-off implementations, flat data models, single-purpose systems",
    "threshold": "must create structural leverage (improves 2+ existing features)",
    "scoring": {
      "excellent": "creates a reusable layer that enables a family of future features",
      "good": "extends existing architecture with clean interfaces",
      "acceptable": "standalone but well-structured implementation",
      "reject": "one-off that cannot be reused or extended"
    }
  },
  "trust_implementation": {
    "preferred": "source hierarchies, claim provenance, confidence tiers in data model",
    "rejected": "trust as marketing copy, unverifiable claims",
    "threshold": "trust must be verifiable in the data model, not just the UI",
    "scoring": {
      "excellent": "every fact has a source, confidence tier, and freshness date",
      "good": "most facts have sources and confidence tiers",
      "acceptable": "sources exist but are not systematically organized",
      "reject": "no source tracking or verification mechanism"
    }
  },
  "testing": {
    "preferred": "E2E verification of actual output on deployed system",
    "rejected": "unit tests of isolated components declared as 'done'",
    "threshold": "verified done with evidence (screenshot, test results, deployment proof)",
    "scoring": {
      "excellent": "E2E tests + visual verification + performance checks + evidence stored",
      "good": "E2E tests + visual verification + evidence",
      "acceptable": "E2E tests pass with evidence",
      "reject": "only unit tests, or no evidence of actual deployment verification"
    }
  },
  "quality_gates": {
    "preferred": "permanent gates, each with origin story, never removed",
    "rejected": "ad-hoc quality checks, inconsistent enforcement",
    "threshold": "every failure produces a permanent prevention mechanism",
    "scoring": {
      "excellent": "systematic gate with automated enforcement and clear origin",
      "good": "documented gate with manual enforcement",
      "acceptable": "informal check that is consistently applied",
      "reject": "no prevention mechanism for known failure mode"
    }
  }
}
```

#### Scope Taste Vector

```
SCOPE_TASTE = {
  "feature_justification": {
    "preferred": "structural leverage — improves multiple existing features",
    "rejected": "single-purpose additions that serve only one use case",
    "threshold": "must strengthen at least 2 existing features or enable 2+ future features",
    "test": "If this feature disappeared tomorrow, would other features degrade?"
  },
  "mvp_size": {
    "preferred": "minimum credible wedge with high-intent entry point",
    "rejected": "full feature set at launch or deceptively small MVP that proves nothing",
    "threshold": "must create real value for real users while being buildable in 30-90 days",
    "test": "What is the 'repair advisor' for this product? The narrowest, highest-intent tool?"
  },
  "phase_boundaries": {
    "preferred": "independently valuable phases with clear go/no-go criteria",
    "rejected": "phases that depend on later phases for value",
    "threshold": "each phase must deliver value even if no subsequent phase is built",
    "test": "If we stopped after this phase, would users still benefit?"
  },
  "deferral_discipline": {
    "preferred": "explicit documentation of deferred scope in vision documents",
    "rejected": "silent omission of features, or zombie features that are never built or killed",
    "threshold": "every idea that is not in the current phase must be explicitly parked or killed",
    "test": "Can I find a document that lists everything we chose NOT to build, and why?"
  }
}
```

#### Innovation Taste Vector

```
INNOVATION_TASTE = {
  "ambition_level": {
    "preferred": "category redefinition over incremental improvement",
    "rejected": "good enough, industry standard, or merely competitive",
    "threshold": "would this surprise and delight users who have seen everything in the category?",
    "test": "Would the founder's reaction be 'yes, AND...' (escalation) or 'yeah, that's fine' (lukewarm)?"
  },
  "creative_sources": {
    "preferred": "cross-domain analogy, tangential discovery, unexpected connections",
    "rejected": "copying competitors, following industry trends, safe choices",
    "threshold": "must bring at least one idea from outside the product's primary category",
    "test": "Where did this idea come from? If the answer is 'our competitors do it,' rethink."
  },
  "abstraction_path": {
    "preferred": "build specific first, then recognize generality, then propose abstraction",
    "rejected": "start with abstract framework, apply to specific case",
    "threshold": "abstraction must be earned through working specific implementation",
    "test": "Did we build something that works before we proposed the generalized version?"
  },
  "moat_building": {
    "preferred": "data moats, network moats, character moats — things that compound",
    "rejected": "first-mover advantage or feature parity as strategy",
    "threshold": "what compounds over time and becomes harder for competitors to replicate?",
    "test": "If a well-funded competitor started today, what would take them years to replicate?"
  }
}
```

---

## End of Document

This document is the synthesis of all Project Visionary research: the QCR Evolution Analysis (493 lines), the Elderle Evolution Analysis (487 lines), and the Framework Synthesis (1,945 lines). It is designed to be immediately usable -- the cognitive profile can be loaded into system prompts today, the pattern library can guide product decisions today, and the implementation roadmap provides a concrete path from document to working system.

The founder's cognitive signature is consistent, distinctive, and encodable. The path from "this is how Eric thinks" to "this system thinks like Eric" is achievable with the architecture described here.

**The next step is the founder's review of this document.** The questions in Section 9 are genuine -- the system improves significantly with founder input on decision priorities, quality thresholds, and the ambition level for the Founder Simulator.
