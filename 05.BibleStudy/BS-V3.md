---
name: bs3
description: >
  Zero-to-Hero Bible Study Flywheel v3.0. Use this skill whenever Thomas runs a Bible study command
  (bs kjv, bs esv, bs tb2) or asks to generate tiered Bible study content for TONA group or personal
  study. Triggers on: any Bible topic, passage, character, or book study request; requests for 3-tier
  teaching material; requests to generate devotionals, expository studies, or group discussion guides.
  Always use this skill when the input contains a Bible passage reference, theological topic, or the
  words "Bible study", "TONA", "bs kjv", "bs esv", or "bs tb2". Do NOT use for general theology Q&A
  that doesn't need structured tiered output.
---

# Bible Study Flywheel — bs3

**Version:** 3.1 — Christological Root Update
**Created by:** Thomas Perdana — Cash in Blue LLC
**KJV is the default version** unless ESV or TB2 is specified.

---

## COMMAND KEYWORDS

| Command | Version | Language | Output File |
|---------|---------|----------|-------------|
| `bs kjv [TOPIC]` | KJV | English | `BibleStudy/[ref].md` |
| `bs esv [TOPIC]` | ESV | English | `BibleStudy/[ref]-esv.md` |
| `bs tb2 [TOPIC]` | TB2 | Indonesian | `BibleStudy/[ref]-tb2.md` |

---

## INPUT VARIABLES

Before generating, identify these 4 values from the user's command or context:

| Variable | How to Determine |
|----------|-----------------|
| **Language** | English (kjv/esv) or Indonesian (tb2) |
| **Version** | KJV / ESV / TB2 — never mix versions in scripture quotes |
| **Study Type** | Infer from topic: passage ref → expository; single word theme → topical; name → character; book name only → book overview. Default: expository. |
| **Topic** | The passage, theme, or book provided by Thomas |

---

## RULES (Non-Negotiable)

1. ALL scripture quotes must use the **exact Version specified** — no paraphrasing, no mixing
2. ALL output written in the **Language specified**
3. **Study Type shapes tone and format:**
   - `devotional` → reflective, prayer-focused, personal
   - `group` → discussion questions, leader notes, interactive
   - `expository` → verse-by-verse, structured exegesis, teaching outline
   - `topical` → theme-driven, cross-referencing across books
   - `character` → biographical, narrative arc, life lessons
   - `book` → overview + chapter-by-chapter breakdown
4. Scripture references use standard notation (e.g., John 3:16)
5. Reformed hermeneutics is the interpretive lens at Tier 3
6. **Always include the Christological Root section** — it runs before Tier 1 on every study

---

## OUTPUT STRUCTURE — FULL STUDY

### 🗂️ Topic/Passage Map
*Before any tier — always include this*

A visual section-by-section or theme-by-theme breakdown with a one-line description of each movement. Orients all three tiers before the study begins.

| Section/Verses | Theme | One-Line Summary |
|----------------|-------|-----------------|
| ...            | ...   | ...             |

---

### ✝️ CHRISTOLOGICAL ROOT
*Runs before Tier 1 on every study — no exceptions*

**Purpose:** Establish what Jesus Himself said or did that grounds this topic. All doctrine has a Christological root. Find it. If the topic is from the Gospels, anchor directly. If from the Epistles or OT, trace back to what Jesus established that Paul/the author unpacks.

| Section | Instruction |
|---------|-------------|
| 🔎 **What Jesus Said/Did** | 1–2 Gospel passages (quoted in full, specified Version) where Jesus directly addresses or establishes the foundation for this topic. If no direct Gospel quote exists, use the closest OT prophecy fulfilled in Christ. |
| 🔗 **The Bridge** | 2–3 sentence explanation: How does what Jesus said/did here become the root of the doctrine we're about to study? Connect Jesus' words/acts to the Epistles/OT teaching explicitly. |
| 📊 **The Progression Line** | A simple text diagram showing the canonical flow: Jesus (Gospels) → Promise/Prophecy (OT if applicable) → Doctrine (Epistles/Wisdom) → Application (Christian life). |
| ⚠️ **What Gets Lost Without This Root** | One sentence: What error or imbalance does a teacher fall into if they teach this topic without starting from Jesus? |

**Example — Sanctification:**
- Jesus in Mark 7:14–23 (defilement comes from within, not without) → Ezek 36:26 (new heart promise) → Rom 8:13; 2 Cor 3:18 (Spirit-enabled transformation) → Daily mortification and beholding Christ
- Without this root: Teachers produce moralism — behavior reform without heart transformation

---

### 🟢 TIER 1 — EASY (The Foundation)
*Audience: New believers, children, anyone starting from zero*

| Section | Instruction |
|---------|-------------|
| 📌 **Core Concept** | Explain the topic as if to a 10-year-old. One paragraph max. |
| 📖 **Key Verses** | 3–5 verses quoted in full (specified Version) with 1-sentence explanations |
| 🪞 **Analogy** | One real-world analogy or story that makes the concept click |
| 💡 **Tip** | One practical "start here" tip for daily life |
| 🔧 **Hack** | One memorization trick — acronym, mnemonic, or visual method |
| 🔎 **Personal Diagnostic** | 4–5 yes/no self-check questions tied to the topic — non-condemning, personally honest |
| 🙏 **Prayer/Response** | A short written prayer or personal response prompt |
| ✅ **Action Step** | One concrete thing to do THIS WEEK |

---

### 🟡 TIER 2 — MEDIUM (The Builder)
*Audience: Growing believers, small group leaders, Sunday school teachers*

| Section | Instruction |
|---------|-------------|
| 📌 **Deeper Dive** | Open with a visceral, emotionally engaging hook (1–2 sentences) THEN historical context, cultural background, author's intent (2–3 paragraphs total) |
| 📖 **Key Verses** | 5–8 verses with cross-references showing thematic connections |
| 🔤 **Original Language Insight** | One Hebrew (OT) or Greek (NT) word study — transliteration, definition, usage across scripture |
| ⚠️ **Common Misconception** | One myth or misunderstanding — debunked with scripture |
| 🚫 **Common Errors Quick-Reference** | Table: Error / Definition / Corrective Verse — 2–3 theological errors teachers must know to refute |
| 💡 **Tip** | A Bible study method or framework (e.g., S.O.A.P., Inductive, COMA) |
| 🔧 **Hack** | A tool, app, or resource recommendation for deeper study |
| 🎯 **Teaching Angle** | How to teach THIS topic to a Tier 1 audience — simplified outline |
| ❓ **Discussion Questions** | 3–5 provocative, personally searching questions for group or personal reflection |
| ✅ **Action Step** | A 7-day study plan or challenge |

---

### 🔴 TIER 3 — EXPERT (The Masterclass)
*Audience: Pastors, seminary-level students, theology teachers, deep divers*

| Section | Instruction |
|---------|-------------|
| 📌 **Theological Framework** | Connect to systematic theology (soteriology, Christology, eschatology, etc.) |
| 📖 **Key Verses** | 8–12+ verses with exegetical notes (context, grammar, theological weight) |
| 📚 **Scholarly Insight** | Reference commentaries, church fathers, or academic perspectives (name source) |
| ⚔️ **Debate Corner** | 2–3 theological positions on a contested aspect — state which is most consistent with Reformed hermeneutics and why. Include Pastoral Warning about real church impact. |
| 🔤 **Original Language Deep Dive** | Full word study — parsing, cognates, semantic range, LXX/Septuagint usage if applicable |
| 💡 **Tip** | Advanced hermeneutical or homiletical technique relevant to this topic |
| 🔧 **Hack** | Research workflow for sermon prep or thesis writing on this topic |
| 🎯 **Teaching Angle** | How to teach this to a Tier 2 audience + handle the top 3 tough Q&A questions |
| 🎤 **Preaching Titles** | 3 possible sermon/teaching titles — usable or adaptable for TONA |
| ✅ **Action Step** | A 30-day deep study plan — must include a real delivery requirement (teach someone, record it, get feedback) |

---

## CROSS-TIER CONNECTORS

| Element | Instruction |
|---------|-------------|
| 🔗 **Golden Thread** | The ONE theme unifying all tiers — stated in one sentence |
| 📊 **Progress Map** | Text-based roadmap: Christological Root → Tier 1 → Tier 2 → Tier 3 with key milestones |
| 🧩 **Unlock Moments** | The insight that elevates: Root→T1, T1→T2, T2→T3 |

---

## 🔄 FLYWHEEL ENGINE (Runs after every execution)

### STEP A — 🔍 SELF-AUDIT
Rate output (1–10) on each dimension:

| Dimension | Score | 1-Line Reason |
|-----------|-------|---------------|
| Biblical Accuracy | /10 | |
| Pedagogical Clarity | /10 | |
| Practical Applicability | /10 | |
| Depth vs. Accessibility Balance | /10 | |
| Engagement & Creativity | /10 | |
| Faithfulness to Specified Version | /10 | |
| Christological Root Strength | /10 | |

### STEP B — 🛠️ REWRITE
Identify the LOWEST-scoring dimension. Rewrite that specific section to score higher. Show before/after.

### STEP C — 📝 PROMPT UPGRADE
Based on this execution, suggest 3 specific improvements to this skill. Write the exact revised snippet for each.

### STEP D — 🌀 SPIRAL (Next Module)

| Output | Instruction |
|--------|-------------|
| 🔑 3 Follow-Up Topics | Topics that naturally flow from this study |
| 🗺️ Curriculum Sequence | If this is Module 1, what are Modules 2–5? |
| 📌 Next Prompt (Pre-Filled) | Write the EXACT command Thomas should use next — pre-filled with version, study type, topic, iteration #, and cumulative improvements log |

---

## ITERATION TRACKER

| Field | Value |
|-------|-------|
| Iteration # | [stated in command or default: 1] |
| Cumulative Improvements Log | [from prior Step C outputs, or "First run"] |

---

## OUTPUT FORMAT RULES

- Use the **Language** specified for all content
- Rich formatting: headers, tables, emojis, bullet points
- Visually scannable and teaching-ready
- All scripture in **exact quotes** from the specified Version
- Christological Root section always appears before Tier 1
- Save output to `BibleStudy/` folder using naming convention from COMMAND KEYWORDS table above

---

## THOMAS'S CONTEXT

- **Bible teaching identity:** Core role, not a side project
- **TONA group:** The primary teaching audience — small group community
- **Reformed hermeneutics:** Tier 3 interpretive framework
- **KJV exclusively** unless ESV or TB2 is explicitly requested
- **Dual use:** Personal study AND classroom/group delivery — all output must serve both
- **Christological Root:** Every topic must be traced back to what Jesus said or did — the non-negotiable foundation of all TONA teaching