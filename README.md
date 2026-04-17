# Adaptive-Teaching

An evidence-based AI teaching skill that transforms any frontier AI model (Claude, GPT, Gemini) into a cognitive-science-grounded tutor. Built from peer-reviewed research — Dunlosky (2013), Sweller CLT (2024), Hattie Visible Learning (2023+) — covering 169,179 participants across 242 studies.

## What It Does

Installs a structured 6-phase teaching protocol into any AI model, replacing default "explain and summarize" behavior with the methods that research proves actually build durable memory and deep understanding.

## The Protocol

Every teaching interaction follows this sequence:

1. **Diagnose** — Identifies prior knowledge and learner profile before teaching anything
2. **Activate** — Connects new concepts to what the learner already knows
3. **Model** — Delivers a fully worked example with narrated reasoning
4. **Guide** — Fades scaffolding progressively as the learner takes over
5. **Retrieve** — Forces active recall instead of passive re-reading
6. **Feedback** — Corrects errors by explaining the *why*, not just the right answer
7. **Metacognition** — Ends every segment with "why does this work / where does it break?"

## Core Research Findings Embedded

- Retrieval practice + spaced practice: effect size 0.70–1.0+ (the two highest-impact learning techniques known)
- Cognitive Load Theory (Sweller 2024): one concept at a time, integrated examples, no split attention
- Field Dependence–Independence: adapts scaffolding to analytical vs. contextual learners
- Learning styles (VARK) explicitly blocked — debunked across hundreds of studies, zero benefit

## Domain Coverage
| Domain | Examples | Key Strategy |
|--------|----------|--------------|
| Abstract/Conceptual | Math, Physics, Logic | Concrete → abstract, analogies before notation |
| Procedural/Skills | Coding, Music, Design | Deliberate practice, decompose → automate → generalize |
| Factual/Declarative | History, Law, Vocabulary | Spaced flashcard retrieval, teach relationships not facts |
| Creative/Open-Ended | Writing, Entrepreneurship | Constraints + iteration cycles + psychological safety |
| Emotional/Social | Communication, Leadership | Role-play + reflection + personal relevance |

## What It Prevents

| ❌ Default AI Behavior | ✅ Replaced With |
|---|---|
| "Does that make sense?" | Active recall prompt |
| Wall-of-text explanation | One concept + immediate comprehension check |
| Re-reading the answer | Retrieval practice |
| Vague praise | Specific, targeted feedback |
| Matching learning styles | Universal multimodal delivery |
| Moving forward when unclear | Diagnose confusion point, re-explain |

## File Structure
adaptive-teaching-skill/
├── SKILL.md              # Core protocol — 6-phase teaching loop, domain strategies,
│                         # cognitive load rules, bad-pattern blocklist
└── references/
└── research-base.md  # Full science: effect sizes, theory comparison,
# learner profiles, myths debunked, domain roadmaps
## Installation

Download `adaptive-teaching-skill.skill` and install it into your Claude.ai Projects or compatible AI environment.

## Research Base
- Dunlosky et al. (2013) — Foundational review of 10 learning techniques
- Donoghue & Hattie (2021) — Meta-analysis of 242 studies, 169,179 participants
- Sweller (2024) — Cognitive Load Theory update with individual differences
- Hattie Visible Learning (2023+) — 2,100+ meta-analyses
- Pashler et al. (2008/2025) — Definitive debunking of learning-styles matching

## Best Used For
Self-directed learners, students, developers learning new stacks, anyone using AI as a tutor who wants retention — not just answers.

## Limitation
The skill structures each session optimally but cannot enforce spaced repetition across days autonomously. For long-term retention across weeks, pair with an external spaced repetition tool (e.g., Anki).
