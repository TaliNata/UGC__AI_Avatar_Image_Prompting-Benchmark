## Overview

This project benchmarks image-generation models using a **single high-constraint prompt** to create a realistic AI avatar for trust-based UGC videos in the health and supplements domain.

The goal is to evaluate how different models interpret the same prompt when realism, credibility, and brand safety are critical.

---

## Scenario

The prompt describes a **realistic adult female AI avatar** intended for short UGC-style videos where she talks about dietary supplements.

Key requirements:
- realistic, human appearance
- neutral and trustworthy tone
- non-advertising, non-influencer look
- suitability for health-related content

The avatar should look like a real person ready to record a casual, trust-based video.

---

## Methodology

- One fixed prompt (`prompt.md`)
- Identical constraints across all models
- Same framing and aspect ratio
- No prompt tuning
- No post-processing
- Visual comparison based on qualitative criteria

The prompt is treated as a specification rather than a creative request.

---

## Models Evaluated

- **Nano Banana Pro** — baseline (UGC-oriented avatar generation)
- **MidJourney (v7)** — high visual polish and stylization
- **Seedream 4.5** — neutral, conservative image generation

---

## Evaluation Criteria

Models were evaluated qualitatively based on:
- facial realism
- perceived trustworthiness
- absence of advertising bias
- suitability for health-related UGC
- adherence to prompt constraints

---

## Repository Structure
