---
name: thought-experiment-architect
description: Assists in building interactive, adventure-based coding challenges (Thought Experiments) for the AutoNateAI platform. Use when you need to brainstorm, draft, or refine high-stakes edutainment content involving 3-6 coding tasks, Mermaid diagrams, and 48-hour solution protocols.
---

# Thought Experiment Architect

This skill guides the creation of **Mission Campaigns**—long-form, high-stakes coding adventures that transform LeetCode/HackerRank patterns into industrial reality.

## The Gold Standard: Operation Silicon Deadlock
Every new mission MUST emulate the technical and narrative depth of **Operation: Silicon Deadlock**.
*   **Narrative:** High-stakes, hyper-local (e.g., GVSU vs. Davenport), and culturally relevant (e.g., Global Silicon Shortage).
*   **Depth:** 1200+ words of immersive storytelling across 5 unnumbered sections.
*   **Visuals:** 9 character-consistent, full-frame 16:9 Disney/Pixar cinematic images.
*   **Interaction:** Acronym-aware `<CardSlam />` hook and 6 incremental coding tasks.

## Mandates for the Architect

### 1. Immersive Setup
*   **The Card Slam:** EVERY page MUST start with the `<CardSlam />` component. Use the acronym-aware `toTitleCase` helper for the question.
*   **Narrative Headers:** **NEVER** include "Act I", "Act II", etc. Use immersive titles like "The Briefing" or "Field Operations."
*   **Cinematic Briefing:** Act I MUST include a full-frame 16:9 image showing the high-stakes background situation.

### 2. High-Density Captivating Visuals
*   **The 9-Graphic Protocol:** **STRICTLY MANDATORY**. Generate exactly **9 cinematic images** (16:9, full-frame, Disney/Pixar style).
*   **Sequential Consistency:** Each generation must use the previous image as a reference to lock character identities (Maya, Leo, Aris) and environments.
*   **Wordless Meme Thumbnail:** Generate a cinematic, text-free OG image (`og-mission-name.png`) for social previews.

### 3. Technical & Automation
*   **Trigger Protocol:** Start with a LeetCode/HackerRank question and optimal solution.
*   **Starter Rig:** Use `gh` CLI to create a public repo with `orchestrator.py`, `README.md`, and mission data.
*   **Mobile UX:** Ensure all code blocks use the `.markdown pre` scaling classes defined in `custom.css`.

## The 5-Act Epic Structure (Section Headers)

1.  **The Briefing:** Hook, Background Visual, Crew Introduction (Maya, Leo, Aris), and the Technical "Intel."
2.  **The Tech Tree:** Interconnected Mermaid dependency graph and topological epiphany visual.
3.  **Tactical Schematics:** Architectural blueprints and the GitHub Starter Rig link.
4.  **Field Operations:** 3-6 coding tasks with "Expected Scan" outputs and dramatic story visuals.
5.  **The 48-Hour Protocol & Debrief:** Extended narrative on real-world impact and CTA for 1:1 Strategy Sessions.

## Phase 1: Discovery (Collaborative Plotting)
1.  **Ingest:** LeetCode question + Optimal Code.
2.  **Search:** Web search for current local/global news to hook the plot.
3.  **Brainstorm:** Present character archetypes and 9 storyboard beats for approval.
