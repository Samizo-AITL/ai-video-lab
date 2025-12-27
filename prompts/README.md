# Prompts Index

This directory contains **reproducible prompt patterns**  
for AI-generated videos used in **education, research, and technical presentations**.

The primary goal is **stability and correctness**,  
**not creativity, storytelling, or visual novelty**.

AI-generated video in this repository is treated as **contextual support**,  
never as a source of factual information.

---

## Prompt Categories

### 1. Abstract / Mood

Prompts in this category are used to create **non-informational background motion**.

Typical use cases:
- lecture introductions
- presentation openings
- section transitions
- atmosphere setting only

Files:
- `abstract_intro.md`
- `tech_mood.md`
- `research_lab.md`

Constraints:
- no text
- no numbers
- no symbols
- short duration only (typically 3–10 seconds)
- no identifiable objects or readable elements

Notes:
- These videos must not convey meaning by themselves.
- They exist solely to prepare visual context for human-delivered content.

---

### 2. Image to Video

Prompts in this category animate **existing static visuals**  
while preserving their informational integrity.

Typical use cases:
- schematic diagrams
- conceptual figures
- static illustrations
- slides converted to subtle motion

Files:
- `image_to_video_basic.md`

Constraints:
- original structure must not change
- geometry must remain intact
- motion must be minimal and non-distracting
- discard output if layout, proportions, or topology are altered

Notes:
- Accuracy originates from the source image.
- The AI model must not invent, simplify, or reinterpret structure.

---

## Generated Samples

The following samples are included as **reference outputs**  
to document achievable quality and behavior.

### `abstract_lab_01.mp4`

- Model: Runway **Gen-4 Turbo** (Image → Video)
- Duration: 5 seconds
- Aspect ratio: 16:9
- Visual focus: abstract laboratory environment, blue/white tone
- Motion: slow, stable, cinematic forward movement
- Intended use:
  - lecture introduction
  - research presentation opening
  - neutral technical atmosphere

Location:

samples/output/abstract_lab_01.mp4


---

## General Principles

- AI video provides **context**, not content.
- Information must originate from:
  - spoken explanation
  - static images
  - diagrams
  - text or equations outside the video
- If the correctness of an animation cannot be guaranteed, **do not animate**.
- Visual clarity is prioritized over visual appeal.

---

## Status and Maintenance Policy

This prompt set is considered **stable**.

New prompts should be added only if:
- they introduce a clearly new category, or
- they are required by a concrete educational or research use case.

Experimental or exploratory prompts must not be added here.

---

*This directory is intentionally conservative by design.*



