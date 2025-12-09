# Report: Construction of the Presentation "KI in der Hochschulbildung"

## Executive Summary

This document details the systematic construction of a half-day workshop presentation on AI in higher education. The presentation argues that AI tools are designed for experts and make experts more productive, while learners often do not benefit—and may be harmed—because learning requires the cognitive effort that AI eliminates.

The presentation was constructed by synthesizing six research documents from `assets/reports/`, supplemented by external sources on critical thinking. The result is a ~3.25-hour workshop with five parts, structured as a progressive argument moving from AI capabilities through cognitive science foundations to the central productivity-learning paradox.

---

## 1. Source Material Analysis

### 1.1 Core Theoretical Document

**File:** `claude-critical_thinking_analysis.md`

This document provided the theoretical foundation for the expert-learner distinction. Key arguments extracted:

- Critical thinking is **domain-specific**, not a transferable skill (citing Willingham)
- What studies measure as "critical thinking" often conflates domain expertise, prior achievement, metacognitive strategies, and general cognitive ability
- The "execution gap": metacognitive strategies require domain knowledge to execute
- Practical implication: students need domain expertise before AI becomes beneficial

This became Part 3 of the presentation ("Kritisches Denken ist domänenspezifisch") and informed the core thesis that learners cannot evaluate AI outputs without domain knowledge.

---

### 1.2 Central Evidence Document

**File:** `compass_artifact_wf-f088985d-7601-4f60-918d-8b360f6c020e_text_markdown.md`

Title: "The Cognitive Cost of Convenience"

This comprehensive report (~320 lines) provided the empirical backbone:

#### The Bastani Study (used in slides 21, 26)

- 1,000 Turkish high school students, RCT design
- 48% more problems solved with GPT-4
- 17% worse performance when AI removed
- Quote used: "Students attempt to use GPT-4 as a 'crutch'"

#### MIT Neuroimaging Study (slide 22)

- EEG during essay writing under three conditions
- Brain connectivity systematically decreased with AI
- "Cognitive debt" concept: reduced patterns persist after AI removal

#### Cognitive Load Theory Framework (slides 9-11)

- Working memory: 4±1 chunks, 15-30 seconds
- Three types of load: intrinsic, extraneous, germane
- The critical question: which load does AI reduce?

#### Expertise Reversal Effect (slide 11)

- Meta-analysis data: d = 0.505 for low prior knowledge with high assistance
- d = -0.428 for high prior knowledge with high assistance
- Same tool, opposite effects

#### Desirable Difficulties (slides 23-24)

- Bjork's research on productive struggle
- Four interventions: variation, interleaving, spacing, retrieval practice
- Generation effect: d = 0.40 across 86 studies

#### Historical Analogues (slide 25)

- GPS and spatial memory (Dahmani & Bohbot)
- Calculator effects (expertise-dependent)
- Google Effect on memory (Sparrow et al.)

#### Extended Mind Thesis (slide 29)

- Clark's distinction: mind-extending vs. mind-replacing
- Criteria for genuine cognitive extension

**How used:** This document provided the empirical backbone for Part 4 ("Das Produktivitäts-Lern-Paradox") and the theoretical framework for Part 2 ("Wie Expertise entsteht").

---

### 1.3 Supporting Evidence Documents

**Elicit Reports** (PDFs, content extracted via prior analysis)

These provided quantitative evidence:

| Report | Key Finding |
|--------|-------------|
| AI and Cognitive Offloading | 17.3 percentage points lower critical thinking scores with high AI use; 22% worse memory retention |
| Cognitive Offloading and Skill Acquisition | Structured vs. unstructured offloading distinction |
| Enhancing Student Learning with LLMs | Task-dependent effects; beneficial for retrieval practice, harmful for code generation |
| Critical Thinking General or Specific | Additional evidence for domain-specificity |

---

### 1.4 External Source

**Willingham Blog Post**

URL: `https://www.kirschnered.nl/2025/02/23/the-science-of-teaching-critical-thinking/`

Key extractions:

- Core thesis: "Critical thinking is not a skill"
- Evidence: neurologists cannot diagnose cardiac cases; technical writers cannot write newspaper articles
- Four-step teaching framework
- Transfer failure across domains

**How used:** Direct quotes in slides 14-15, and the conceptual foundation for Part 3.

---

## 2. Narrative Arc Construction

### 2.1 Design Principle: Three-Act Structure

The presentation was structured as a progressive argument:

```text
Act 1: What AI Can Do (establish stakes)
     ↓
Act 2: Why It Works for Experts (cognitive science foundation)
     ↓
Act 3: Why It Often Fails Learners (the paradox)
```

**Rationale:** This structure moves from capability (which the audience likely knows) through explanation (which provides tools for understanding) to the central argument (which challenges assumptions). This is more persuasive than leading with the conclusion.

---

### 2.2 Part 1: Understanding AI Capabilities (~30 min)

**Purpose:** Brief grounding so participants understand what we're discussing.

| Slide | Content | Rationale |
|-------|---------|-----------|
| 1 | Opening provocation with Bastani data | Hook: immediately establish the paradox |
| 2 | How LLMs produce text | Conceptual foundation (user requested "conceptual only") |
| 3 | How "thinking" works in AI | Demystify chain-of-thought reasoning |
| 4 | Tool-enabled agents | Show capability frontier |
| 5 | Discussion | Activate prior knowledge, surface experiences |

**Design choice:** The Bastani "48%/17%" finding was used as the opening hook because it encapsulates the entire presentation's thesis in a single data point. This creates cognitive tension that the rest of the presentation resolves.

---

### 2.3 Part 2: How Expertise Develops (~45 min)

**Purpose:** Establish the cognitive science foundation before discussing AI effects.

| Slide | Content | Source |
|-------|---------|--------|
| 6 | Expert-novice distinction | General cognitive psychology |
| 7 | ACT-R: weak to strong methods | Anderson 1982 |
| 8 | Proceduralization and compilation | Anderson 1982 |
| 9 | CLT fundamentals | Sweller 2024 |
| 10 | Three types of cognitive load | Cognitive Cost report |
| 11 | Expertise reversal effect | Kalyuga 2009, Tetzlaff meta-analysis |
| 12 | Think-Pair-Share discussion | 10 min |

**Design choice:** This section was placed *before* the AI evidence because understanding cognitive load theory is prerequisite to understanding why AI affects learners differently than experts. Without this foundation, the Bastani results would seem puzzling rather than predictable.

**Key quote extracted:** "Alles Lernen muss durch das Nadelöhr des Arbeitsgedächtnisses" (All learning must pass through the bottleneck of working memory). This became a callout because it's the central mechanism.

---

### 2.4 Part 3: Critical Thinking is Domain-Specific (~30 min)

**Purpose:** Dismantle the myth that "AI literacy" is a transferable skill.

| Slide | Content | Source |
|-------|---------|--------|
| 13 | Traditional assumption | Framing |
| 14 | Willingham's challenge | Willingham 2008, blog post |
| 15 | Evidence for domain-specificity | Blog post examples |
| 16 | Applied to AI evaluation | claude-critical_thinking_analysis.md |
| 17 | Metacognition gap | claude-critical_thinking_analysis.md |
| 18 | Key implication | Synthesis |
| 19 | Discussion | 5 min |

**Design choice:** This section was placed here (rather than in Part 4) because it provides the conceptual bridge between expertise development and the productivity-learning paradox. The argument flow is:

1. Expertise develops through effortful practice (Part 2)
2. Critical evaluation of AI requires domain expertise (Part 3)
3. Therefore, AI that eliminates effort prevents expertise that would enable critical evaluation (Part 4)

**Specific construction from report:**

From `claude-critical_thinking_analysis.md`:

> "A biomedical science expert can spot when ChatGPT gets biochemistry wrong. A novice cannot make this evaluation regardless of their 'critical thinking skills.'"

This became the two-column comparison in slide 16, translated to German.

---

### 2.5 Part 4: The Productivity-Learning Paradox (~45 min)

**Purpose:** Present the core evidence that AI helps performance but can harm learning.

| Slide | Content | Source |
|-------|---------|--------|
| 20 | Central paradox statement | Jose 2025 |
| 21 | Bastani math study | Cognitive Cost report |
| 22 | Neurological evidence | Kosmyna 2025 |
| 23 | Desirable difficulties | Bjork 2011 |
| 24 | Generation effect | Slamecka 1978 |
| 25 | Historical analogues | Dahmani 2020, Sparrow 2011 |
| 26 | Why experts benefit, learners don't | Synthesis |
| 27 | Think-Pair-Share | 15 min |

**Design choice for slide sequence:**

1. **State the paradox** (20): Frame the cognitive dissonance
2. **Show behavioral evidence** (21): Bastani study
3. **Show neurological evidence** (22): MIT study
4. **Explain the mechanism** (23-24): Desirable difficulties and generation effect
5. **Provide historical context** (25): GPS, calculators, Google
6. **Synthesize** (26): Expert vs. learner comparison

This sequence moves from "what happens" to "why it happens" to "this isn't new."

**Specific data extraction:**

From the Cognitive Cost report, specific numbers were extracted:

- "48% more problems solved correctly"
- "17% worse on subsequent unassisted tests"
- "d = 0.40 across 86 studies" (generation effect)

These precise figures add credibility and are memorable.

---

### 2.6 Part 5: Implications and Synthesis (~30 min)

**Purpose:** Draw out consequences without prescribing specific solutions.

| Slide | Content | Source |
|-------|---------|--------|
| 28 | The uncomfortable truth | Synthesis |
| 29 | Mind-extending vs. mind-replacing | Clark 2025 |
| 30 | Sequencing question | Implication |
| 31 | Equity dimension | Trucano 2024 |
| 32 | What we don't know | Cognitive Cost report |
| 33 | Closing provocations | Direct quotes |
| 34 | Open discussion | 15 min |

**Design choice:** Prescriptive solutions were deliberately avoided because:

1. The user requested focus on theory, not practical strategies
2. The evidence base for specific interventions is weak (slide 32)
3. Solutions are context-dependent; university instructors need to determine what works in their contexts

**Quote selection for closing:**

Three quotes from the Cognitive Cost report were selected that escalate in their implications:

1. "If AI assistance during education impairs independent capability, students may graduate less prepared..."
2. "The productivity gains during education would come at the cost of capability thereafter."
3. "Whether this tradeoff is acceptable depends on assumptions about the future that educators cannot verify."

These are intentionally provocative because the goal is to stimulate discussion, not provide closure.

---

## 3. Translation and Localization Decisions

### 3.1 Swiss German Conventions

Following project guidelines (CLAUDE.md):

- "ss" instead of "ß" (e.g., "weisst" not "weißt")
- Informal "du" form in discussion prompts
- No emojis

### 3.2 Key Term Translations

| English | German | Rationale |
|---------|--------|-----------|
| Cognitive offloading | Kognitives Auslagern | Standard translation |
| Desirable difficulties | Erwünschte Schwierigkeiten | Direct translation preserves concept |
| Expertise reversal effect | Expertise-Umkehr-Effekt | Hybrid preserves recognition |
| Mind-extending/replacing | Kognition erweitern/ersetzen | Verb form more natural in German |
| Cognitive debt | Kognitive Schulden | Maintains metaphor |

### 3.3 Retained English Quotes

Key quotes were retained in English for several reasons:

- Academic precision (translations can introduce ambiguity)
- The audience (university instructors) is comfortable with English
- Some concepts (like "critical thinking") don't translate cleanly

---

## 4. Visual and Structural Decisions

### 4.1 Color Coding

Following the project's custom callout system:

| Color | Hex Code | Use |
|-------|----------|-----|
| Magenta | #A3195B | Section headers (attention, action) |
| Gold | #D4A03E | Discussion slides (reflection, insight) |
| Grey | #666666 | Pause slide (neutral) |

### 4.2 Column Layouts

Two-column layouts were used for comparisons:

- Expert vs. novice capabilities (slides 6, 16, 26)
- With AI vs. without AI results (slide 21)
- Three-column for neurological evidence (slide 22)

**Rationale:** Side-by-side comparisons make contrasts visually immediate.

### 4.3 Incremental Reveals

`:::` {.incremental} and `. . .` (pause) markers were used extensively for:

- Lists that build toward a conclusion
- Data followed by interpretation
- Setup followed by punchline

**Rationale:** Controls pacing and prevents cognitive overload from displaying too much at once.

### 4.4 Timer Durations

| Discussion Type | Duration | Rationale |
|-----------------|----------|-----------|
| Brief discussion | 5 min (300s) | Quick activation, not deep reflection |
| Think-Pair-Share | 10-15 min (600-900s) | Full cycle: think (3 min), pair (4 min), share (8 min) |
| Coffee break | 15 min (900s) | Standard workshop break |
| Open discussion | 15 min (900s) | Allow for deeper engagement at conclusion |

---

## 5. Bibliography Construction

### 5.1 Existing References Used

The following references already existed in `bibliography.bib`:

| Citation Key | Source |
|--------------|--------|
| `andersonAcquisitionCognitiveSkill1982` | ACT-R theory |
| `bastaniGenerativeAICan2024` | Math study |
| `bjorkMakingThingsHard2011` | Desirable difficulties |
| `clarkExtendingMindsGenerative2025` | Extended mind thesis |
| `kalyugaExpertiseReversalEffect2009` | Expertise reversal |
| `kosmynaYourBrainChatGPT2025` | Cognitive debt study |
| `swellerCognitiveLoadTheory2024` | CLT |
| `willinghamCriticalThinkingWhy2008` | Critical thinking |

### 5.2 References Added

Six new entries were added to support claims not covered by existing references:

| Citation Key | Source | Used For |
|--------------|--------|----------|
| `joseCognitiveParadoxAI2025` | Frontiers in Psychology | Paradox framing |
| `dahmaniHabitualUseGPS2020` | Scientific Reports | GPS analogy |
| `slameckaGenerationEffect1978` | J Exp Psych | Generation effect |
| `sparrowGoogleEffectsMemory2011` | Science | Google Effect |
| `trucanoThirdDigitalDivide2024` | Brookings | Equity dimension |
| `sieglerDevelopingConceptualUnderstanding2017` | J Ed Psych | Calculator effects |

---

## 6. What Was Deliberately Excluded

### 6.1 From the Reports

| Excluded Content | Reason |
|------------------|--------|
| Detailed methodology discussions | Too technical for audience and purpose |
| Effect size confidence intervals | Simplified to point estimates |
| Meta-analysis heterogeneity details | Mentioned uncertainty but didn't elaborate |
| Specific AI tool comparisons | Focused on general phenomenon, not specific products |

### 6.2 From the Intermediate Workshop

| Excluded Content | Reason |
|------------------|--------|
| Make-it-Stick strategies | User explicitly requested focus on theory |
| Agent design activities | Not appropriate for this presentation's goals |
| Detailed prompting guidance | Outside scope |

### 6.3 Potential Topics Not Included

| Topic | Reason for Exclusion |
|-------|---------------------|
| Solutions and interventions | Weak evidence base; context-dependent |
| Detection and academic integrity | Different topic |
| Specific discipline applications | Would require discipline-specific knowledge |

---

## 7. Verification of Argument Coherence

### 7.1 Logical Flow Check

```text
Premise 1: Learning requires cognitive effort (CLT, desirable difficulties)
Premise 2: AI reduces cognitive effort (by design)
Premise 3: The type of effort reduced matters (germane vs. extraneous)
Premise 4: For learners, AI often reduces germane load
Premise 5: Experts can strategically offload extraneous tasks
─────────────────────────────────────────────────────────────────
Conclusion: Same tools have opposite effects by expertise level
```

Each premise is supported by evidence from the reports.

### 7.2 Evidence-Claim Alignment

| Claim | Evidence | Strength |
|-------|----------|----------|
| AI improves task performance | Meta-analyses, Bastani | Strong |
| AI can harm learning | Bastani, neuroimaging | Moderate-strong |
| Expertise moderates effects | Meta-analysis of expertise reversal | Strong |
| Critical thinking is domain-specific | Willingham review, transfer studies | Strong |
| Historical tools show same pattern | GPS, calculator studies | Moderate |

---

## 8. File Structure

### 8.1 Files Created/Modified

| File | Action | Purpose |
|------|--------|---------|
| `slides/ai-higher-ed/index.qmd` | Replaced | Main presentation content |
| `bibliography.bib` | Appended | Added 6 new references |

### 8.2 Presentation Statistics

| Metric | Value |
|--------|-------|
| Total lines | ~700 |
| Number of slides | ~34 |
| Discussion segments | 6 |
| Total discussion time | ~65 min |
| Bibliography citations | 14 |

---

## 9. Summary

The presentation was constructed through:

1. **Source synthesis**: Extracting key arguments and evidence from 6 documents
2. **Narrative design**: Three-act structure building toward the central paradox
3. **Evidence selection**: Prioritizing memorable, quantified findings
4. **Pedagogical structuring**: Prerequisite concepts before conclusions
5. **Discussion integration**: Strategic pauses for reflection
6. **Localization**: German translation with Swiss conventions

The result is a ~3.25-hour workshop that provides university instructors with a theoretically grounded, evidence-based framework for understanding why AI tools designed for experts may not benefit learners.

---

## Appendix: Presentation Timing Overview

| Section | Duration | Cumulative |
|---------|----------|------------|
| Teil 1: Was KI heute kann | 30 min | 0:30 |
| Teil 2: Wie Expertise entsteht | 45 min | 1:15 |
| Teil 3: Kritisches Denken | 30 min | 1:45 |
| Pause | 15 min | 2:00 |
| Teil 4: Produktivitäts-Lern-Paradox | 45 min | 2:45 |
| Teil 5: Implikationen | 30 min | 3:15 |
| **Total** | **~3:15** | |
