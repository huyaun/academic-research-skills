# 学术科研能力框架 | Academic Research Skills Framework

> A comprehensive integration of four complementary skill systems for AI-augmented academic research and high-impact paper writing.
>
> 四大学术科研能力系统的综合整合指南：从研究选题到高水平论文发表

## 📋 Framework Overview | 框架概览

这个框架综合了四个相互连接的技能领域，旨在指导研究者从研究构思到出版级论文写作的整个过程：

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

### Purpose | 目的
指导研究选题、方向规划和导师互动策略

### Key Components | 核心组件

#### 1.1 Research Direction Selection | 研究方向选择
- **RQ Framing**: Transform broad interests into specific, answerable research questions
  - 将宽泛的研究兴趣转化为具体、可回答的研究问题
- **Scope Validation**: Check feasibility, novelty, and alignment with advisor expectations
  - 验证可行性、新颖性和与导师期望的对齐
- **Literature Positioning**: Position your work within existing research landscape
  - 在现有研究景观中定位您的工作
- **Advisor Communication Templates**: Structured dialogue frameworks for thesis/dissertation planning
  - 论文/论文研究规划的结构化对话框架

#### 1.2 Supervision Strategy | 督导策略
- **Checkpoint Planning**: Define key milestones and deliverables
  - 定义关键里程碑和可交付成果
- **Feedback Integration Workflow**: How to interpret and incorporate advisor feedback
  - 如何解读和整合导师反馈
- **Problem Escalation Protocol**: When and how to seek guidance
  - 何时以及如何寻求指导
- **Publication Readiness Criteria**: Joint agreement on quality gates
  - 出版就绪标准的联合协议

#### 1.3 Collaborative Research Planning | 协作研究规划
- **Co-author Workflows**: Managing multi-party research coordination
  - 管理多方研究协作
- **Data Ownership & Attribution**: IP and authorship clarity frameworks
  - 知识产权和作者身份的明确框架
- **Timeline & Resource Management**: Realistic scheduling for complex projects
  - 复杂项目的切实可行的调度
- **Career Trajectory Alignment**: How research fits long-term goals
  - 研究如何符合长期目标

---

## 2️⃣ Academic Research Skills | 学术研究能力

### Purpose | 目的
系统的文献综述、研究方法论和知识管理框架

### Core Modules | 核心模块

#### 2.1 Deep Research Pipeline | 深度研究管道
- **Socratic-Guided Literature Exploration** (Intent-aware mode selection)
  - Exploratory mode: For open-ended question development (≤60 turns, no auto-convergence)
    - 探索模式：用于开放式问题开发（≤60轮，无自动收敛）
  - Goal-oriented mode: For targeted information gathering
    - 目标导向模式：用于有针对性的信息收集
  - Dialogue health monitoring: Self-check for persistent agreement/conflict avoidance
    - 对话健康监测：持久性同意/冲突回避的自我检查

- **7 Research Modes | 7种研究模式**
  1. **Full Mode**: Complete 13-agent research team (synthesis, risk-of-bias, meta-analysis)
  2. **Quick Mode**: Fast brief on topic (5 agents)
  3. **Systematic Review Mode**: PRISMA-compliant protocol + analysis
  4. **Socratic Mode**: Guided exploration with dialogue health checks
  5. **Fact-Check Mode**: Verify specific claims against evidence
  6. **Literature Review Mode**: Thematic synthesis of existing work
  7. **Review Mode**: Assess research quality of existing papers

#### 2.2 Literature Corpus Management | 文献库管理
- **Corpus Schema** (v3.6.4+): Standardized entry format
  - Title, authors, year, DOI/URL
  - Abstract, method, findings, relevance score
  - Zotero/Obsidian adapter support
- **Anti-Leakage Protocol**: Knowledge isolation directive (prioritize material over LLM memory)
  - 防泄漏协议：知识隔离指令（优先考虑材料而不是LLM记忆）
- **Semantic Scholar API Verification**: Tier-0 reference existence checks
  - 第一级参考文献存在检查
- **Contamination Detection**: Multi-index triangulation (S2 + OpenAlex + Crossref)
  - 污染检测：多索引三角测量

#### 2.3 Integrity & Quality Gates | 完整性与质量门控
- **Data Access Level Metadata**
  - `raw`: Complete unfiltered data access | 完整未过滤数据访问
  - `redacted`: Sensitive data masked | 敏感数据已屏蔽
  - `verified_only`: Pre-verified claims only | 仅预验证的声明
  
- **Citation Verification Gates** (v3.11.0+)
  - Deterministic cross-check against 4 bibliographic indexes
  - Locator anchors for manual verification
  - Hallucination audit trails

#### 2.4 Knowledge Organization | 知识组织
- **IRON RULE Markers**: Non-negotiable consistency checks
  - 铁则标记：不可协商的一致性检查
- **Anti-Pattern Library**: 29+ documented AI failure modes (hallucination, frame-lock, sycophancy)
  - 反模式库：29+记录的AI故障模式
- **Cognitive Frameworks**
  - Argumentation reasoning (Toulmin, Bradford Hill causal)
  - Review quality thinking (internal/external validity)
  - Writing judgment framework (clarity, voice, discipline fit)

---

## 3️⃣ Scientific-Agent-Skills | 科研方法与智能体协作

### Purpose | 目的
AI驱动的实验设计、数据分析和多智能体科研工作流

### Research Automation Framework | 研究自动化框架

#### 3.1 Multi-Agent Research Team Architecture | 多智能体研究团队架构
- **13-Agent Research Team | 13智能体研究团队**
  1. **Research Architect**: RQ decomposition + methodology design
  2. **Synthesis Agent**: Literature synthesis with hallucination guards
  3. **Bibliography Agent**: Reference corpus curation + cleaning
  4. **Risk-of-Bias Agent**: Study quality assessment (ROBINS-I, Cochrane)
  5. **Meta-Analysis Agent**: Effect size aggregation + heterogeneity
  6. **Monitoring Agent**: Temporal validity + publication bias checks
  7-13. **Domain Specialists** (varies by field)

#### 3.2 Experiment Provenance Protocol | 实验溯源协议
- **External Experiment Tracking**: Record experiments conducted outside ARS
  - 外部实验跟踪：记录在ARS之外进行的实验
- **Material Passport Integration**: Structured provenance metadata
  - 材料护照集成：结构化溯源元数据
- **Reproducibility Lockfile**: Configuration documentation (not byte-replay guarantee)
  - 可重现性锁定文件：配置文档（不是字节重放保证）
- **Experiment Intake Declaration**: Fail-closed checks for experiment-backed claims
  - 实验摄入声明：实验支持的声明的失败关闭检查

#### 3.3 Anti-Hallucination Countermeasures (v2.7+) | 防幻觉对策

**5-Type Hallucination Taxonomy | 5类幻觉分类法**
- **TF**: Totally Fabricated (no basis in literature)
  - 完全虚构（文献中没有基础）
- **PAC**: Partially Attributed Citation (partial quote misattributed)
  - 部分属性引用（部分引用误分）
- **IH**: Implicit Hallucination (reasonable but unsourced inference)
  - 隐性幻觉（合理但无源推理）
- **PH**: Parametric Hallucination (LLM memorized incorrectly)
  - 参数幻觉（LLM记忆错误）
- **SH**: Subtle Hallucination (correct conclusion, wrong reasoning chain)
  - 微妙幻觉（正确结论，推理链错误）

**Compound Deception Patterns | 复合欺骗模式** (5 documented):
1. Nested authority chain (A cites B cites X, but B never read X)
2. Timeline distortion (redate old claims as recent)
3. Scope inflation (limited finding → universal claim)
4. Authority inflation (opinion → consensus)
5. Evidence substitution (different study cited instead of original)

#### 3.4 Integrity Verification v2.0 | 完整性验证v2.0
- **Anti-Hallucination Mandate**: No AI memory verification; external WebSearch only
  - 防幻觉强制：无AI记忆验证；仅外部网络搜索
- **3-Class Output**: VERIFIED / NOT_FOUND / MISMATCH (no gray zones)
  - 三类输出：已验证/未找到/不匹配（无灰色区域）
- **Mandatory WebSearch Audit**: Every citation independently checked
  - 强制网络搜索审计：每个引用独立检查
- **Post-Publication Audit**: Independent stress test of references
  - 出版后审计：参考文献的独立压力测试

#### 3.5 Devil's Advocate with Concession Threshold (v3.0+) | 带让步阈值的魔鬼代言人
- **Score-Before-Respond Protocol**: DA must rate every rebuttal (1-5) before responding
  - 评分前回应协议：DA必须在回应前评分每个反驳（1-5）
- **Concession Rules | 让步规则**
  - ≥4: Directly addresses core attack with evidence → allowed
  - ≤3: Hold position, restate original attack
- **Anti-Sycophancy Guards**: No consecutive concessions, rate tracking, frame-lock detection
  - 反讨好警卫：无连续让步，速率追踪，框架锁定检测

---

## 4️⃣ Nature-Skills | 高水平学术论文写作

### Purpose | 目的
Publication-grade academic writing across top-tier venues (Nature, Science, ICLR, etc.)

### Paper Writing Pipeline | 论文写作管道

#### 4.1 12-Agent Paper Writing Architecture | 12智能体论文写作架构
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

#### 4.2 Writing Modes (10 total) | 写作模式（共10种）

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

#### 4.3 Style Calibration & Quality Control (v2.9+) | 风格校准与质量控制

**Style Calibration Intake | 风格校准摄入**
- Provide ≥3 past papers
- Pipeline learns your voice signature:
  - Sentence rhythm & vocabulary
  - Citation integration style
  - Discipline-specific terminology
  - Argument construction patterns

**Writing Quality Check** (5-category rubric) | 写作质量检查
- Category 1: AI high-frequency terms (25-term warning list)
- Category 2: Passive voice overuse
- Category 3: Hedging language density
- Category 4: Citation integration naturalness
- Category 5: Discipline-specific voice fit

#### 4.4 Peer Review & Integrity Gates | 对等评审与完整性门控

**7-Agent Multi-Perspective Review | 7智能体多视角评审**
- **Editor-in-Chief**: Scope, novelty, significance
- **Reviewer 1-3**: Method, data, argument quality (assigned dynamically by field)
- **Devil's Advocate**: Frame-lock detection + contrarian challenge
- **Synthesis Agent**: Cross-reviewer consensus + meta-level assessment

**Quality Rubrics with 0-100 Scoring | 0-100评分质量标准**
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

#### 4.5 Integrity Verification Gates (Mandatory) | 强制的完整性验证门控

**Stage 2.5: Pre-Review Integrity Check** (Before Peer Review)
- 7-mode AI Research Failure checklist
- Reference existence verification (Semantic Scholar API)
- Statistical error detection
- Claims audit (if `ARS_CLAIM_AUDIT=1`)

**Stage 4.5: Post-Revision Integrity Check** (After Peer Review)
- Regression detection (no quality score drops >3 points)
- New reference verification
- Revision compliance confirmation

#### 4.6 Finalization Pipeline | 最终化管道

**Output Chain | 输出链**
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

**Bilingual Support | 双语支持**
- Abstract + keywords in Chinese + English
- Optional full paper bilingual generation
- APA 7.0 with Chinese citation rules

#### 4.7 Collaboration Quality Evaluation (Stage 6) | 协作质量评估

**6-Dimension Rubric** (1–100 scoring) | 6维度标准（1-100评分）
1. **Delegation Intensity**: What % of cognitive load did AI handle?
   - 委托强度：AI处理了多少%的认知负荷？
2. **Cognitive Vigilance**: How actively did you verify AI outputs?
   - 认知警惕：您多积极地验证AI输出？
3. **Cognitive Reallocation**: Did you shift focus to higher-value tasks?
   - 认知重新分配：您是否将重点转移到更高价值的任务？
4. **Zone Classification**: Did interaction span exploratory/decision/refinement zones?
   - 区域分类：交互是否跨越探索/决策/优化区域？
5. **Sycophancy Risk**: Were there moments of excessive agreement/quick concession?
   - 讨好风险：是否有过度同意/快速让步的时刻？
6. **Learning Curve**: Did you develop stronger evaluation skills during process?
   - 学习曲线：您是否在过程中发展了更强的评估技能？

---

## 5️⃣ Integration Points: How These Skills Work Together | 整合点：四大技能的协作

### Research Conception to Publication Pipeline | 研究构思到出版管道

```
STAGE 1: Supervisor-Skills Activation | 导师技能激活
├─ Select research direction (RQ framing)
├─ Align with advisor expectations
├─ Define milestones & checkpoints
└─ Establish collaboration protocol

        ↓

STAGE 2: Academic Research Skills + Scientific-Agent-Skills | 学术研究+科研方法
├─ Systematic literature mapping (13-agent research team)
├─ Methodology design with advisor feedback
├─ Experiment execution & provenance tracking
├─ Integrity verification (7-mode AI failure checklist)
└─ Build Material Passport (schema v9+)

        ↓

STAGE 3: Nature-Skills Paper Writing | 高水平论文写作
├─ Outline generation (Socratic-guided or direct)
├─ Draft with style calibration
├─ Integrate literature corpus (pre-screened)
├─ Multiple revision rounds with coaching
└─ Integrity verification gates (2.5 + 4.5)

        ↓

STAGE 4: Peer Review & Finalization | 对等评审与最终化
├─ 7-agent multi-perspective review
├─ Revision coaching + response drafting
├─ Final compliance check
├─ PDF generation (bilingual + APA 7.0)
└─ Collaboration quality evaluation (Stage 6)

        ↓

POST-PUBLICATION | 出版后
├─ Manual reference audit (stress test)
├─ Continuous improvement feedback loop
└─ Career trajectory alignment (back to Supervisor-Skills)
```

---

## 6️⃣ Implementation Checklist | 实施检查清单

### ✅ For Research Conception | 研究构思
- [ ] Define 2-3 candidate RQs using Supervisor-Skills framework
- [ ] Draft RQ validation checklist (novelty, feasibility, significance)
- [ ] Schedule advisor check-in with structured agenda

### ✅ For Literature Review | 文献综述
- [ ] Set up literature corpus (Zotero, Obsidian, or custom)
- [ ] Run Systematic Review mode (PRISMA protocol)
- [ ] Build Material Passport with corpus metadata
- [ ] Trigger contamination detection across 3 indexes

### ✅ For Methodology & Experiments | 方法与实验
- [ ] Use Scientific-Agent-Skills multi-agent team for experiment design
- [ ] Document experiment provenance (external runs)
- [ ] Run integrity verification v2.0 (anti-hallucination mandate)
- [ ] Prepare Material Passport handoff to writing stage

### ✅ For Paper Writing | 论文写作
- [ ] Collect ≥3 past papers for style calibration
- [ ] Use Nature-Skills plan mode for outline (if uncertain)
- [ ] Run full paper mode with corpus integration
- [ ] Trigger pre-review integrity gate (Stage 2.5)

### ✅ For Peer Review Preparation | 对等评审准备
- [ ] Format citations in target venue style (APA/Chicago/IEEE)
- [ ] Generate venue-specific AI disclosure statement
- [ ] Prepare response template for likely review questions
- [ ] Set collaboration quality target (e.g., Vigilance ≥70)

### ✅ For Final Submission | 最终提交
- [ ] Finalize bilingual abstract + keywords
- [ ] Compile LaTeX → PDF via tectonic
- [ ] Run post-revision integrity check (Stage 4.5)
- [ ] Generate process summary & collaboration report

---

## 7️⃣ Key Principles Across All Four Skills | 四大技能的核心原则

### Anti-Sycophancy & Honesty | 反讨好与诚实性
- Devil's Advocate with concession threshold protocol (v3.0+)
- Dialogue health monitoring (agreement detection, conflict avoidance)
- Cross-model verification when uncertain (optional)

### Hallucination Prevention | 幻觉预防
- Anti-Leakage Protocol (prioritize material over LLM memory)
- External-only verification (WebSearch, API checks, manual audit)
- 5-type hallucination taxonomy with compound patterns
- Mandatory integrity gates at publication-critical points

### Human-in-the-Loop, Not Automation | 人类在循环中，不是自动化
- **Every stage requires explicit user confirmation**
- AI is augmentation, not replacement
- Socratic guidance when direction uncertain
- Collaboration quality evaluation at end of process

### Transparency & Auditability | 透明性与可审计性
- Three-layer citation emission with locators (v3.7.3+)
- Claim-to-source alignment audit (v3.8+)
- Reproducibility lockfile (configuration documentation)
- Post-publication manual stress testing

---

## 8️⃣ Detailed Module Guides | 详细模块指南

For in-depth guidance on each skill, see detailed documentation in `academic-skills` repository:

- **📘 docs/supervisor-skills.md** - Research direction management | 研究方向管理
- **📗 docs/academic-research-skills.md** - Literature & methodology | 文献与方法论
- **📕 docs/scientific-agent-skills.md** - AI-driven research workflows | AI科研工作流
- **📙 docs/nature-skills.md** - Publication-grade writing | 出版级论文写作

---

## 9️⃣ Key Resources | 关键资源

- **Official Academic Research Skills**: https://github.com/huyaun/academic-research-skills
- **Comprehensive Skills Framework**: https://github.com/huyaun/academic-skills
- **Vibe Coding CN**: https://github.com/huyaun/vibe-coding-cn
- **Experiment Agent**: https://github.com/Imbad0202/experiment-agent

---

## License | 许可证

CC-BY-NC 4.0 (Attribution required, non-commercial use only)

**Citation Format**:
```
Based on Academic Research Skills Framework
https://github.com/huyaun/academic-skills
```

---

**Last Updated**: 2026-06-13  
**Framework Version**: 2.0 (Synchronized)  
**Status**: Active & Maintained  
**Sync Status**: ✅ All modules synchronized across repositories
