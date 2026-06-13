# 学术科研能力框架 | Academic Research Skills Framework

> A comprehensive integration of four complementary skill systems for AI-augmented academic research and high-impact paper writing.

## 📋 Framework Overview

This framework synthesizes four interconnected skill domains designed to guide researchers from research conception through publication-level writing:

```
┌─────────────────────────────────────────────────────────────────┐
│                    研究选题与方向管理                              │
│                  Supervisor-Skills                              │
│          (Research Direction & Advisor Collaboration)            │
└─────────────────────────────────────────────────────────────────┘
                              ↓
┌─────────────────────────────────────────────────────────────────┐
│                    学术文献与研究方法                              │
│        Academic Research Skills + Scientific-Agent-Skills         │
│   (Literature & Methodology Framework)                           │
└─────────────────────────────────────────────────────────────────┘
                              ↓
┌─────────────────────────────────────────────────────────────────┐
│                    高水平学术论文写作                              │
│                      Nature-Skills                               │
│          (Publication-Level Academic Writing)                    │
└─────────────────────────────────────────────────────────────────┘
```

---

## 1️⃣ Supervisor-Skills | 研究方向管理

### Purpose
指导研究选题、方向规划和导师互动策略

### Key Components

#### 1.1 Research Direction Selection
- **RQ Framing**: Transform broad interests into specific, answerable research questions
- **Scope Validation**: Check feasibility, novelty, and alignment with advisor expectations
- **Literature Positioning**: Position your work within existing research landscape
- **Advisor Communication Templates**: Structured dialogue frameworks for thesis/dissertation planning

#### 1.2 Supervision Strategy
- **Checkpoint Planning**: Define key milestones and deliverables
- **Feedback Integration Workflow**: How to interpret and incorporate advisor feedback
- **Problem Escalation Protocol**: When and how to seek guidance
- **Publication Readiness Criteria**: Joint agreement on quality gates

#### 1.3 Collaborative Research Planning
- **Co-author Workflows**: Managing multi-party research coordination
- **Data Ownership & Attribution**: IP and authorship clarity frameworks
- **Timeline & Resource Management**: Realistic scheduling for complex projects
- **Career Trajectory Alignment**: How research fits long-term goals

---

## 2️⃣ Academic Research Skills | 学术研究能力

### Purpose
系统的文献综述、研究方法论、和知识管理框架

### Core Modules

#### 2.1 Deep Research Pipeline
- **Socratic-Guided Literature Exploration** (Intent-aware mode selection)
  - Exploratory mode: For open-ended question development (≤60 turns, no auto-convergence)
  - Goal-oriented mode: For targeted information gathering
  - Dialogue health monitoring: Self-check for persistent agreement/conflict avoidance

- **7 Research Modes**
  1. **Full Mode**: Complete 13-agent research team (synthesis, risk-of-bias, meta-analysis)
  2. **Quick Mode**: Fast brief on topic (5 agents)
  3. **Systematic Review Mode**: PRISMA-compliant protocol + analysis
  4. **Socratic Mode**: Guided exploration with dialogue health checks
  5. **Fact-Check Mode**: Verify specific claims against evidence
  6. **Literature Review Mode**: Thematic synthesis of existing work
  7. **Review Mode**: Assess research quality of existing papers

#### 2.2 Literature Corpus Management
- **Corpus Schema** (v3.6.4+): Standardized entry format
  - Title, authors, year, DOI/URL
  - Abstract, method, findings, relevance score
  - Zotero/Obsidian adapter support
- **Anti-Leakage Protocol**: Knowledge isolation directive (prioritize material over LLM memory)
- **Semantic Scholar API Verification**: Tier-0 reference existence checks
- **Contamination Detection**: Multi-index triangulation (S2 + OpenAlex + Crossref)

#### 2.3 Integrity & Quality Gates
- **Data Access Level Metadata**
  - `raw`: Complete unfiltered data access
  - `redacted`: Sensitive data masked
  - `verified_only`: Pre-verified claims only
  
- **Citation Verification Gates** (v3.11.0+)
  - Deterministic cross-check against 4 bibliographic indexes
  - Locator anchors for manual verification
  - Hallucination audit trails

#### 2.4 Knowledge Organization
- **IRON RULE Markers**: Non-negotiable consistency checks
- **Anti-Pattern Library**: 29+ documented AI failure modes (hallucination, frame-lock, sycophancy)
- **Cognitive Frameworks**
  - Argumentation reasoning (Toulmin, Bradford Hill causal)
  - Review quality thinking (internal/external validity)
  - Writing judgment framework (clarity, voice, discipline fit)

---

## 3️⃣ Scientific-Agent-Skills | 科研方法与智能体协作

### Purpose
AI驱动的实验设计、数据分析、和多智能体科研工作流

### Research Automation Framework

#### 3.1 Multi-Agent Research Team Architecture
- **13-Agent Research Team**
  1. **Research Architect**: RQ decomposition + methodology design
  2. **Synthesis Agent**: Literature synthesis with hallucination guards
  3. **Bibliography Agent**: Reference corpus curation + cleaning
  4. **Risk-of-Bias Agent**: Study quality assessment (ROBINS-I, Cochrane)
  5. **Meta-Analysis Agent**: Effect size aggregation + heterogeneity
  6. **Monitoring Agent**: Temporal validity + publication bias checks
  7-13. **Domain Specialists** (varies by field)

#### 3.2 Experiment Provenance Protocol
- **External Experiment Tracking**: Record experiments conducted outside ARS
- **Material Passport Integration**: Structured provenance metadata
- **Reproducibility Lockfile**: Configuration documentation (not byte-replay guarantee)
- **Experiment Intake Declaration**: Fail-closed checks for experiment-backed claims

#### 3.3 Anti-Hallucination Countermeasures (v2.7+)

**5-Type Hallucination Taxonomy**
- TF: Totally Fabricated (no basis in literature)
- PAC: Partially Attributed Citation (partial quote misattributed)
- IH: Implicit Hallucination (reasonable but unsourced inference)
- PH: Parametric Hallucination (LLM memorized incorrectly)
- SH: Subtle Hallucination (correct conclusion, wrong reasoning chain)

**Compound Deception Patterns** (5 documented):
1. Nested authority chain (A cites B cites X, but B never read X)
2. Timeline distortion (redate old claims as recent)
3. Scope inflation (limited finding → universal claim)
4. Authority inflation (opinion → consensus)
5. Evidence substitution (different study cited instead of original)

#### 3.4 Integrity Verification v2.0
- **Anti-Hallucination Mandate**: No AI memory verification; external WebSearch only
- **3-Class Output**: VERIFIED / NOT_FOUND / MISMATCH (no gray zones)
- **Mandatory WebSearch Audit**: Every citation independently checked
- **Post-Publication Audit**: Independent stress test of references

#### 3.5 Devil's Advocate with Concession Threshold (v3.0+)
- **Score-Before-Respond Protocol**: DA must rate every rebuttal (1-5) before responding
- **Concession Rules**
  - ≥4: Directly addresses core attack with evidence → allowed
  - ≤3: Hold position, restate original attack
- **Anti-Sycophancy Guards**: No consecutive concessions, rate tracking, frame-lock detection

---

## 4️⃣ Nature-Skills | 高水平学术论文写作

### Purpose
Publication-grade academic writing across top-tier venues (Nature, Science, ICLR, etc.)

### Paper Writing Pipeline

#### 4.1 12-Agent Paper Writing Architecture
1. **Outline Agent**: IMRaD/Thematic structure generation
2. **Argument Strategist**: 4-level argument scoring + positioning
3. **Literature Strategist**: Corpus-first literature integration
4. **Draft Writer**: Content generation with style calibration
5. **Visualization Agent**: Figure generation + VLM verification
6. **Citation Compliance Agent**: Format conversion (APA/Chicago/IEEE/Vancouver)
7. **Revision Coach**: Point-by-point feedback integration
8. **Writing Quality Agent**: Anti-AI-speak detection (25 high-frequency term list)
9. **Plagiarism Screener**: Self-plagiarism + unattributed reuse checks
10. **LaTeX Hardener**: Math/notation verification
11. **Disclosure Agent**: Venue-specific AI usage statement generator
12. **Report Compiler**: Final assembly + cross-agent consistency

#### 4.2 Writing Modes (10 total)

| Mode | Use Case | Output |
|------|----------|--------|
| **full** | Complete paper from outline | MD + DOCX/LaTeX → PDF |
| **plan** | Socratic guidance on structure | Outline + revision roadmap |
| **outline-only** | Structure without content | IMRaD/Thematic outline |
| **revision** | Integrate reviewer feedback | Marked-up revision + response |
| **revision-coach** | Parse reviewer comments | Revision roadmap + priorities |
| **abstract-only** | Standalone abstract | Bilingual abstract + keywords |
| **lit-review** | Convert paper to literature review | Thematic synthesis paper |
| **format-convert** | Citation/format transformation | APA↔Chicago↔IEEE conversion |
| **citation-check** | Verify all citations | Citation audit report |
| **disclosure** | AI usage statement | Venue-specific disclosure |

#### 4.3 Style Calibration & Quality Control (v2.9+)

**Style Calibration Intake**
- Provide ≥3 past papers
- Pipeline learns your voice signature:
  - Sentence rhythm & vocabulary
  - Citation integration style
  - Discipline-specific terminology
  - Argument construction patterns

**Writing Quality Check** (5-category rubric)
- Category 1: AI high-frequency terms (25-term warning list)
- Category 2: Passive voice overuse
- Category 3: Hedging language density
- Category 4: Citation integration naturalness
- Category 5: Discipline-specific voice fit

#### 4.4 Peer Review & Integrity Gates

**7-Agent Multi-Perspective Review**
- **Editor-in-Chief**: Scope, novelty, significance
- **Reviewer 1-3**: Method, data, argument quality (assigned dynamically by field)
- **Devil's Advocate**: Frame-lock detection + contrarian challenge
- **Synthesis Agent**: Cross-reviewer consensus + meta-level assessment

**Quality Rubrics with 0-100 Scoring**
```
Scoring Bands:
≥80 → Accept (high quality)
65-79 → Minor Revision (good with improvements)
50-64 → Major Revision (significant work needed)
<50 → Reject (fundamental issues)
```

**Decision Mapping** (after Stage 3.5 reconciliation)
- Accept: All reviewers ≥75, no CRITICAL findings
- Minor Revision: Weighted avg 65-79, max 1 CRITICAL
- Major Revision: Weighted avg 50-64, ≤2 CRITICAL
- Reject: Avg <50 or ≥3 CRITICAL or core methodology flaw

#### 4.5 Integrity Verification Gates (Mandatory)

**Stage 2.5: Pre-Review Integrity Check** (Before Peer Review)
- 7-mode AI Research Failure checklist
- Reference existence verification (Semantic Scholar API)
- Statistical error detection
- Claims audit (if `ARS_CLAIM_AUDIT=1`)

**Stage 4.5: Post-Revision Integrity Check** (After Peer Review)
- Regression detection (no quality score drops >3 points)
- New reference verification
- Revision compliance confirmation

#### 4.6 Finalization Pipeline

**Output Chain**
```
Markdown (primary)
    ↓
[Pandoc available?]
    ├─ YES → .docx (intermediate)
    └─ NO → conversion instructions
    ↓
[LaTeX compilation needed?]
    ├─ tectonic available → PDF directly
    └─ else → LaTeX source + build instructions
```

**Bilingual Support**
- Abstract + keywords in Chinese + English
- Optional full paper bilingual generation
- APA 7.0 with Chinese citation rules

#### 4.7 Collaboration Quality Evaluation (Stage 6)

**6-Dimension Rubric** (1–100 scoring)
1. **Delegation Intensity**: What % of cognitive load did AI handle?
2. **Cognitive Vigilance**: How actively did you verify AI outputs?
3. **Cognitive Reallocation**: Did you shift focus to higher-value tasks?
4. **Zone Classification**: Did interaction span exploratory/decision/refinement zones?
5. **Sycophancy Risk**: Were there moments of excessive agreement/quick concession?
6. **Learning Curve**: Did you develop stronger evaluation skills during process?

---

## 5️⃣ Integration Points: How These Skills Work Together

### Research Conception to Publication Pipeline

```
STAGE 1: Supervisor-Skills Activation
├─ Select research direction (RQ framing)
├─ Align with advisor expectations
├─ Define milestones & checkpoints
└─ Establish collaboration protocol

        ↓

STAGE 2: Academic Research Skills + Scientific-Agent-Skills
├─ Systematic literature mapping (13-agent research team)
├─ Methodology design with advisor feedback
├─ Experiment execution & provenance tracking
├─ Integrity verification (7-mode AI failure checklist)
└─ Build Material Passport (schema v9+)

        ↓

STAGE 3: Nature-Skills Paper Writing
├─ Outline generation (Socratic-guided or direct)
├─ Draft with style calibration
├─ Integrate literature corpus (pre-screened)
├─ Multiple revision rounds with coaching
└─ Integrity verification gates (2.5 + 4.5)

        ↓

STAGE 4: Peer Review & Finalization
├─ 7-agent multi-perspective review
├─ Revision coaching + response drafting
├─ Final compliance check
├─ PDF generation (bilingual + APA 7.0)
└─ Collaboration quality evaluation (Stage 6)

        ↓

POST-PUBLICATION
├─ Manual reference audit (stress test)
├─ Continuous improvement feedback loop
└─ Career trajectory alignment (back to Supervisor-Skills)
```

---

## 6️⃣ Implementation Checklist

### ✅ For Research Conception
- [ ] Define 2-3 candidate RQs using Supervisor-Skills framework
- [ ] Draft RQ validation checklist (novelty, feasibility, significance)
- [ ] Schedule advisor check-in with structured agenda

### ✅ For Literature Review
- [ ] Set up literature corpus (Zotero, Obsidian, or custom)
- [ ] Run Systematic Review mode (PRISMA protocol)
- [ ] Build Material Passport with corpus metadata
- [ ] Trigger contamination detection across 3 indexes

### ✅ For Methodology & Experiments
- [ ] Use Scientific-Agent-Skills multi-agent team for experiment design
- [ ] Document experiment provenance (external runs)
- [ ] Run integrity verification v2.0 (anti-hallucination mandate)
- [ ] Prepare Material Passport handoff to writing stage

### ✅ For Paper Writing
- [ ] Collect ≥3 past papers for style calibration
- [ ] Use Nature-Skills plan mode for outline (if uncertain)
- [ ] Run full paper mode with corpus integration
- [ ] Trigger pre-review integrity gate (Stage 2.5)

### ✅ For Peer Review Preparation
- [ ] Format citations in target venue style (APA/Chicago/IEEE)
- [ ] Generate venue-specific AI disclosure statement
- [ ] Prepare response template for likely review questions
- [ ] Set collaboration quality target (e.g., Vigilance ≥70)

### ✅ For Final Submission
- [ ] Finalize bilingual abstract + keywords
- [ ] Compile LaTeX → PDF via tectonic
- [ ] Run post-revision integrity check (Stage 4.5)
- [ ] Generate process summary & collaboration report

---

## 7️⃣ Key Principles Across All Four Skills

### Anti-Sycophancy & Honesty
- Devil's Advocate with concession threshold protocol (v3.0+)
- Dialogue health monitoring (agreement detection, conflict avoidance)
- Cross-model verification when uncertain (optional)

### Hallucination Prevention
- Anti-Leakage Protocol (prioritize material over LLM memory)
- External-only verification (WebSearch, API checks, manual audit)
- 5-type hallucination taxonomy with compound patterns
- Mandatory integrity gates at publication-critical points

### Human-in-the-Loop, Not Automation
- **Every stage requires explicit user confirmation**
- AI is augmentation, not replacement
- Socratic guidance when direction uncertain
- Collaboration quality evaluation at end of process

### Transparency & Auditability
- Three-layer citation emission with locators (v3.7.3+)
- Claim-to-source alignment audit (v3.8+)
- Reproducibility lockfile (configuration documentation)
- Post-publication manual stress testing

---

## 8️⃣ Recommended Reading

### Official Guides
- **Setup & Installation**: `docs/SETUP.md` (prerequisites, API keys, installation methods)
- **Architecture & Modes**: `docs/ARCHITECTURE.md` (skill details, stage matrix, agent roster)
- **Performance & Cost**: `docs/PERFORMANCE.md` (token budgets, recommended settings)

### Methodological Foundations
- **Cognitive Frameworks**: `shared/references/argumentation_reasoning_framework.md` (Toulmin, Bradford Hill)
- **Review Quality Thinking**: `shared/references/review_quality_thinking.md` (validity lenses, common traps)
- **Writing Judgment Framework**: `shared/references/writing_judgment_framework.md` (clarity, voice, revision matrix)

### Case Study
- **Full Pipeline Output**: See `examples/showcase/` directory
  - Real 10-stage pipeline artifacts (research → writing → review → publication)
  - Integrity reports catching 22 issues (Stage 2.5) and confirming 0 regressions (Stage 4.5)
  - Post-publication audit: 21/68 refs corrected in manual stress test

---

## 9️⃣ Support & Contribution

**License**: CC-BY-NC 4.0 (Share with attribution, no commercial use)

**Citation Format**:
```
Based on Academic Research Skills by Cheng-I Wu
https://github.com/Imbad0202/academic-research-skills
```

**Version**: v3.12.0 (2026-06-08)

**Related Projects**:
- [Academic Research Skills for Claude Code](https://github.com/huyaun/academic-research-skills) — Full implementation
- [Experiment Agent](https://github.com/Imbad0202/experiment-agent) — External experiment orchestration
- [vibe-coding-cn](https://github.com/huyaun/vibe-coding-cn) — AI collaboration workflows

---

## 🔟 Quick Navigation

| Skill Domain | Primary Goal | Key Tool | Start Here |
|---|---|---|---|
| **Supervisor-Skills** | Research direction + advisor collaboration | RQ framing templates | Research Direction Selection |
| **Academic Research Skills** | Literature + methodology rigor | 13-agent research team | Deep Research Pipeline |
| **Scientific-Agent-Skills** | Experiment design + AI rigor | Multi-agent workflows | Multi-Agent Architecture |
| **Nature-Skills** | Publication-grade writing | 12-agent paper pipeline | 10 Writing Modes |

---

**Last Updated**: 2026-06-13  
**Framework Version**: 1.0  
**Status**: Active & Maintained
