# Workflow Documentation

This document describes the end-to-end workflow used to create the AI-generated
cinematic short film *Half of Me*. The focus of this project was on AI system
orchestration, prompt design, and human-in-the-loop refinement rather than
model training or low-level implementation.

---

## 1. Concept & Narrative Definition

The workflow begins with a high-level narrative concept focused on identity,
split consciousness, and psychological transformation. The goal was to create
a short cinematic experience rather than a traditional story or technical demo.

Key constraints defined at this stage:
- Dark psychological sci-fi tone
- Minimal exposition, strong visual symbolism
- Dual perspectives and fragmented identity
- Short runtime (3–5 minutes)

These constraints guided all downstream AI interactions.

---

## 2. Script Generation (LLM)

A large language model was used to generate the narrative structure and story
content based on carefully designed prompts.

Focus areas:
- Scene-based storytelling
- Gradual escalation of tension
- Emotional continuity across scenes
- Avoidance of excessive technical jargon

The generated story served as a *draft narrative layer*, which was later refined
and adapted for voiceover use.

Relevant prompts are documented in:
`prompts/story_prompt.md`

---

## 3. Voiceover & Narration Design

The narrative was converted into a cinematic voiceover script using a dual
narration approach, representing two fragmented identities.

Design choices:
- Separate voices for Elias and Jonah
- Occasional overlapping dialogue to reinforce dissociation
- Minimal narration to preserve ambiguity
- Controlled pacing to align with visual transitions

AI-based voice synthesis tools were used to generate narration audio.
The output was reviewed and selectively regenerated to improve tone,
clarity, and emotional delivery.

Relevant prompts are documented in:
`prompts/narration_prompt.md`

---

## 4. Scene & Video Generation

Individual video clips were generated using AI-based video generation tools.
Each clip corresponded to a specific scene or symbolic moment in the narrative.

Visual constraints included:
- Dark, low-saturation color palette
- Abstract or symbolic imagery
- Slow camera motion
- Dream-like transitions

Multiple generations were evaluated per scene to manage variability and
inconsistency inherent in generative video systems.

Relevant prompts are documented in:
`prompts/scene_generation_prompt.md`

---

## 5. Output Coordination & Synchronization

Generated assets (script, narration, and video clips) were treated as independent
outputs that required coordination.

At this stage:
- Narration timing was aligned with visual pacing
- Scene order was adjusted to improve narrative flow
- Redundant or conflicting visuals were removed

This step was critical in transforming isolated AI outputs into a cohesive
cinematic sequence.

---

## 6. Limitations Analysis

Generative AI limitations were explicitly evaluated, including:
- Visual inconsistency between clips
- Temporal continuity issues
- Mismatch between narration tone and visuals
- Lack of fine-grained control over motion and expression

Understanding these constraints informed decisions about where human
intervention was necessary.

---

## 7. Human-in-the-Loop Editing

Final refinement was performed manually using CapCut.

Human intervention included:
- Trimming and sequencing video clips
- Adjusting timing to match narration
- Removing artifacts and visually inconsistent segments
- Ensuring narrative coherence and emotional impact

This stage ensured that the final output met cinematic and storytelling goals.

---

## 8. Final Output

The final result is a short cinematic film created through the orchestration
of multiple AI systems combined with human judgment and refinement.

This project demonstrates:
- Multi-step AI workflow design
- Prompt engineering and constraint management
- Coordination of independent AI outputs
- Practical understanding of human-in-the-loop AI systems

The final video is linked in `output.md`.
