---
name: animate
description: Generate 10 distinct viral animation styles from a single master scene prompt in Claude and Antigravity without credit limits.
version: 1.0.0
author: Karan Kumaar (@krn.tips)
license: MIT
---

# Animate Skill: Single-Prompt Multi-Style Animation Engine

This skill equips Claude and Antigravity with a deterministic prompt expansion workflow to generate 10 unique visual animation styles while strictly preserving character likeness, pose dynamics, color harmony, and composition layout.

## 🚀 The Core Philosophy: Anchor & Transform
Instead of burning credits on multi-shot diffusion seeds that produce inconsistent characters, this workflow uses a two-phase architecture:
1. **The Anchor Phase:** Generate an unstyled, high-clarity 9:16 master scene image.
2. **The Style Modulation Phase:** Pass the anchor image reference to Claude/Antigravity with specialized style directives to redraw and animate into 3-second seamless loops.

---

## 📋 Master Scene Prompt (Run First)
`	ext
Make a 9:16 image: a young man with short curly dark hair in a red hoodie, blue jeans and white sneakers, mid-jump with both arms up and a big smile, holding a small black camera in one hand, a ginger cat leaping in the air beside him, a striped red and cream hot-air balloon and a round yellow sun in a bright blue sky with puffy white clouds, a rounded green hill below. Full body, centered in the frame, lots of sky around him. Clean flat vector illustration, simple shapes, soft shading. No text, no letters, no logos.
`

---

## 🎨 The 10 Animation Style Modifiers

### 01. Pixel Art
`	ext
Redraw my scene from the last image in pixel art: 16-bit pixel art, chunky visible pixels, a limited bright palette, like a retro platformer game. Keep the same man, cat, pose and layout. No text. Then animate it into a 3 second clip: he bounces in the air with his arms up, the cat kicks its paws, the clouds and the balloon drift. The camera stays still.
`

### 02. PS2 Style
`	ext
Redraw my scene from the last image in PS2 style: a real early-2000s PlayStation 2 3D game, blocky low-polygon 3D models with visible polygon edges, muddy low-resolution textures, a 3D world with depth and distance fog, a game screenshot look. Keep the same man, cat, pose and layout. No text. Then animate it into a 3 second clip: he bounces in the air with his arms up, the cat kicks its paws, the clouds and the balloon drift. The camera stays still.
`

### 03. Comic Art
`	ext
Redraw my scene from the last image in comic art: bold comic book art, thick black ink outlines, halftone dots, speed lines and an empty starburst behind him. Keep the same man, cat, pose and layout. No text. Then animate it into a 3 second clip: he bounces in the air with his arms up, the cat kicks its paws, the clouds and the balloon drift. The camera stays still.
`

### 04. Lego Style
`	ext
Redraw my scene from the last image in lego style: everything built from plastic toy bricks, a toy minifigure man and cat, studs on every surface. Keep the same man, cat, pose and layout. No text. Then animate it into a 3 second clip: he bounces in the air with his arms up, the cat kicks its paws, the clouds and the balloon drift. The camera stays still.
`

### 05. Claymation
`	ext
Redraw my scene from the last image in claymation: stop-motion claymation, plasticine with fingerprints and soft studio light. Keep the same man, cat, pose and layout. No text. Then animate it into a 3 second clip: he bounces in the air with his arms up, the cat kicks its paws, the clouds and the balloon drift. The camera stays still.
`

### 06. Paper Cutout
`	ext
Redraw my scene from the last image in paper cutout: layered paper cutout craft, cut card stock in layers with soft drop shadows. Keep the same man, cat, pose and layout. No text. Then animate it into a 3 second clip: he bounces in the air with his arms up, the cat kicks its paws, the clouds and the balloon drift. The camera stays still.
`

### 07. Retro Anime
`	ext
Redraw my scene from the last image in retro anime: 1990s cel anime, hand-painted watercolor sky, cel shading, a little film grain. Keep the same man, cat, pose and layout. No text. Then animate it into a 3 second clip: he bounces in the air with his arms up, the cat kicks its paws, the clouds and the balloon drift. The camera stays still.
`

### 08. Low Poly 3D
`	ext
Redraw my scene from the last image in low poly 3D: low poly 3D, flat-shaded faceted shapes, soft pastel lighting. Keep the same man, cat, pose and layout. No text. Then animate it into a 3 second clip: he bounces in the air with his arms up, the cat kicks its paws, the clouds and the balloon drift. The camera stays still.
`

### 09. Risograph
`	ext
Redraw my scene from the last image in risograph: a two-color risograph print in fluorescent pink and blue ink, grainy texture, slight misregistration. Keep the same man, cat, pose and layout. No text. Then animate it into a 3 second clip: he bounces in the air with his arms up, the cat kicks its paws, the clouds and the balloon drift. The camera stays still.
`

### 10. Miniature Diorama
`	ext
Redraw my scene from the last image in miniature diorama: a tilt-shift miniature diorama, tiny handmade model figures on a tabletop set, shallow depth of field. Keep the same man, cat, pose and layout. No text. Then animate it into a 3 second clip: he bounces in the air with his arms up, the cat kicks its paws, the clouds and the balloon drift. The camera stays still.
`

---

## ⚙️ Best Practices for Zero Inconsistency
- **Keep Camera Fixed:** Always instruct The camera stays still to prevent AI video models from spinning or warping backgrounds.
- **Negative Prompt Injection:** No text, no letters, no logos, no watermarks, no distorted faces.
- **Duration Tuning:** Keep video clips to 3.0s - 4.0s for loopability.

Created by **Karan Kumaar (@krn.tips)**. Share and build in public!