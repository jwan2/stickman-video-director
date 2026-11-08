---
name: directing-stickman-videos
description: "Turn topics, requirements, articles or scripts into stickman videos. Director mode creates approved storyboards and standalone video prompts; Autopilot mode produces narrated, captioned illustration-and-micro-animation videos through configured generation tools and a local renderer. Also guide installation handoff, first use and setup of this specific Skill."
---

# Directing Stickman Videos

## Two modes, one Skill

Keep the existing installation/name. Honor known choices; ask one short question if the requested deliverable is ambiguous. Before planning, read [mode execution boundaries](references/mode-execution-boundaries.md), then the selected route:

- **A · Director / A1–A5:** approved proposals and standalone video prompts. A1 maps to Style 1 light/dark, A2 to Style 2/2A/2B, A3–A5 to Styles 3–5. Follow the contract below.
- **A6 · Amber Noir:** read [A6](references/amber-noir.md) when selected, before planning; bypass the A1–A5 contract below. It owns reference-guided execution, independent narration and finishing; Gemini Puck is the default only when the user has not chosen another voice.
- **B · Autopilot:** read [Autopilot](references/autopilot.md), then B1 [Minimal Line Art](references/b1-minimal-handdrawn.md), B2 [Colorful Hand-Drawn](references/b2-colorful-handdrawn.md), or B3 [Retro TV](references/b3-television.md). A finished local video includes narration, semantic captions, illustrations, meaningful motion and SFX. Inspect B3's bundled implementation examples before authoring; original-video excerpts are not redistributed. Disclose missing private-original comparison rather than treating accepted examples as the style authority.
- **B4 · Survival Thriller:** read [B4](references/b4-survival-storytelling.md), [audio direction](references/b4-audio-direction.md), [opening direction](references/b4-opening-direction.md) and [production check](references/b4-repeatability-check.md). Preserve the white-glove reference lock; limb animation is not a completion requirement. Apply the first-three-second visual escalation gate and, for horror, the story-led horror visibility gate. Use fixed Brian, first-frame sound/early narration, a subtle continuous bed and causal SFX. Select B4 in the shared installed runtime. No silent title pad, automatic narrator substitution or alias to another style.

A and B share installation, not production contracts. The rules from **A · Director** to the end apply only to A1–A5, not to A6 or any B style. Each B owns its visuals, captions, voice, pacing and SFX; never default to B1 or import A's setup, ten-second clips, approval or visible-text rules. Preserve unrelated styles when revising one route.

For **A1–A6**, read [story-led directing](references/directing-craft.md) before planning. Default new Flow visual generation to the UI model **Omni 1.2 Flash**, one 10-second source clip per generation, at the user's requested ratio; 720p is the starting target. Verify the live model name, supported input mode, duration, resolution, output count and current price before submission. Ten seconds is this skill's default source-clip setting, not the model's maximum, a required final shot length, or a reason to round the requested film duration. Choose source count and editorial cuts by story, usable footage and actual voice timing. Honor explicit user choices, reuse accepted footage/audio and do not silently switch providers or models. This Flow default does not apply to B.

B supports topics, promotion briefs, posts, articles and scripts. English narration is default; explicit language/voice choices prevail. Use the selected native named TTS voice without added voice/style descriptions by default; B4 permits story-motivated secondary-role acting, not automatic narrator tuning. Read the required [story-led sound system](references/autopilot-sound-system.md). Never automatically revoice accepted media.

All B captions are semantic and single-line: preserve meaning, tight grammatical groups and actual speech pauses; split overlong cues into successive semantic units, not mechanical word counts or smaller type. Check encoded frames and sidecars under the [common caption gate](references/autopilot-production-qa.md#natural-captions-and-semantic-sound). A is unchanged.

## First use and next steps

Read [first-use and stage guidance](references/getting-started.md) after verified installation or on first invocation. Use the conversation/requested guidance language independently of video language or README edition. Reuse choices; do not replay welcome or add approvals. Follow **A5 proactive character guidance** and **Optional A character references** there without changing voice rules.

Read [optional finishing](references/thumbnail-publishing-kit.md) after final-video approval or a packaging request; offer once, never block delivery.

## A · Director

## Core contract

Turn one source into a confirmed director's proposal and then standalone prompts for the planned 10-second Omni 1.2 Flash source clips. Shape a story-specific hook, progression and payoff without promising an outcome metric or forcing an ending. Distinguish editorial shots from generated source clips; estimate source count from the duration and refine it for cuts, handles, action complexity and actual speech.

## Setup gate

Require these before planning:

- source material
- aspect ratio: `16:9` or `9:16`
- target duration (for example `30s`, `54s`, `60s`, `3min`; default `60s` if unspecified)
- visual style and theme:
  - `Style 1 (Classic Minimalist)`: light (white background, black figure) or dark (black background, white figure)
  - `Style 2 (Modern Beanie Zeke)`:
    - `Style 2A (Modern Studio Tech)`: pure white high-key studio, subtle light-gray perspective grid, floating cyan/blue glass UI
    - `Style 2B (Cinematic Story)`: full-color narrative environments, cinematic lighting & depth
  - `Style 3 (Prehistoric Hand-Drawn / Dark Comedy)`: expressive white filled heads, black stick limbs, animal-hide costumes and earthy prehistoric settings; story-specific casting
  - `Style 4 (Cozy Storytelling / 治愈故事风)`: expressive minimalist white-filled characters with dark stick limbs in full-color 2D cartoon environments; varied story locations and cinematic shot changes
  - `Style 5 (Historical Cartoon / 历史卡通风)`: white heads with connected short white necks, expressive faces, black stick limbs and compact fingerless palms, period dress and cel-shaded historical settings

If aspect ratio or visual style is missing, ask for all missing items in one concise message and stop. If duration is omitted, default to 60 seconds. Preserve a user-specified duration even when it is not divisible by 10. If a user specifies only light or dark theme, default to Style 1. Never select an aspect ratio or style silently. Do not re-ask choices already supplied.

Urgency, generation cost, client pressure, and requests to "pick normal settings" do not waive this gate.

## Workflow

1. Read `references/directing-craft.md`, `references/storyboard-template.md`, `references/style-catalog.md` and `references/voice-continuity.md`. Build a story-specific visual hook, causal progression and payoff with purposeful changes of shot, perspective and audience understanding. Choose a structure suited to the source; do not force a five-stage arc or generic call to action. Produce Phase A in the user's language, with English VO and a reference translation.
2. Stop after the director's proposal and request explicit approval.
3. If the user changes ratio, duration, style, theme, narration, scene structure, or global direction, recompose Phase A and request approval again.
4. Only after approval of the current Phase A, read `references/omni-flash-prompt-contract.md` and produce Phase B.
5. Use `references/examples.md` only when a concrete end-to-end example would resolve ambiguity.

Topic approval, schedule pressure, or approval of an older draft is not approval of the current Phase A.

## Output rules

For Style 3, read `references/prehistoric-dark-comedy.md` before planning. Its casting, story rhythm, palette and continuity rules override the generic no-idle, device-count and five-stage discussion-ending rules below. Use setup → escalation → ironic payoff for narrative shorts; do not force a discussion question into a visual punchline. This is a visual storytelling style, not a claim about actual prehistory.

For Style 4, read `references/cozy-storytelling.md` before planning and prompt assembly. Choose recognizable settings and vary meaningful viewpoints as the story requires; do not force a new location for every source clip. Preserve characters, drawing grammar, important props, movement direction and narrator. Name location cuts and any time jumps in Phase A. This is full-color cartoon storytelling, not a hand-drawn/sketchbook mode and not a claim of photorealistic 3D backgrounds.

For Style 5, read `references/historical-cartoon.md` before planning and prompt assembly. Keep its drawing grammar fixed while changing the era pack. Confirm story-specific cast cards, setting, palette, props and exact narration in Phase A; repeat the full approved style and visible cast descriptions in every Phase B prompt. Its historical palette, music, physical-action pacing and story ending override generic three-color, mandatory-piano, device-count, no-idle and discussion-ending rules below. Apply the existing shared voice contract; do not apply this style's character rules to Styles 1–4.

- Give the opening a visible reason to care, develop a specific question or conflict, and provide the story's intended payoff or deliberate unresolved ending. Preserve the user's script and factual qualifications; a hook is not permission to invent claims.
- Fit narration to the requested film duration and natural speaking pace, rather than forcing a fixed word count into each source clip. Use actual speech timing when available.
- For every editorial shot record its narrative job, visible before/action/after state, composition, relevant audio and connection to its neighbors. Choose visual changes and holds for meaning; no mandatory device count, fixed beat intervals or decorative motion quota.
- Keep character proportions, line weight, style, and narrator consistent across all clips.
- For Style 1, freeze the concise character anchor from `references/style-catalog.md` and repeat it verbatim in every clip. Keep two arms and two legs, one current pose per limb, stable proportions and uniform medium line weight; a moving arm replaces its previous pose rather than adding another arm. Keep the figure monochrome and saturated accents on props/graphics. Do not replace the anchor with "same character", ellipses, numeric anatomy recipes, skeleton/path instructions or clip-specific appearance descriptions. Occasional simple line expressions are allowed; the head remains hollow. Keep rich actions and effects separate from character design. Treat generated consistency as a visual acceptance check, not a guarantee from repeated text.
- For Style 1, limit the video to three saturated accent colors named with ordinary descriptive words (e.g. vivid red, electric blue, warm gold). For light theme, enforce a flat, digitally pure-white canvas with no textures, gradients, or 3D depth.
- For Style 2 (Modern Beanie Zeke), enforce character consistency:
  - Default anchor, repeated in full in every standalone source prompt: `A minimalist 2D animated stick figure wearing a bright red beanie (smooth knit, no pom-pom) and a yellow t-shirt, with simple black stick limbs and shorts. Simple black lines, vibrant colors, smooth 2D animation style.`
  - If the user chooses different clothes or a different cast, freeze and repeat the approved full character anchor instead of silently restoring the default. A reference helps consistency but does not guarantee it.
  - No detailed eyes, pupils, or photorealistic features (avoids bug-eye deformation).
- For Style 2A (Modern Studio Tech), enforce: `in a modern bright white studio space with subtle light-gray perspective grid lines on the floor plane. High-key studio lighting, clean white negative space, sleek glowing cyan and electric blue glass holographic UI elements.` Always include negative constraint: `STRICTLY MINIMALIST, NO CIRCUIT BOARD TEXTURES, NO SCI-FI WALL PANELS, NO CRACKED CONCRETE.`
- For Style 2B (Cinematic Story), specify full-color narrative setting and cinematic lighting while preserving the 2D animated stick-figure character design.
- For Style 4, freeze each approved character's complete anchor and repeat it in every clip where that role appears. Separate static design from first-frame positions, timed prop transfers and final states; changing scene does not reset prop ownership or the narrator. Read its reference for shot variety and visual acceptance checks.
- For all styles, avoid unwanted abstract liquid/shape morphing. Use concrete story-driven action and reactions, including a deliberate hold when it communicates meaning. Simplify difficult contact or break it across shots rather than overloading a single source clip.
- For A1–A5, apply `references/voice-continuity.md`: choose one complete video-level voice profile in Phase A. For source-generated narration, repeat its full frozen English block in each applicable prompt. For an accepted or requested independent voice track, preserve the exact provider, voice and recording in the edit plan and leave narrator instructions out of visual-only prompts. A scene/style/character change must not recast the narrator. Keep a chosen music motif continuous where music is used, honoring the style and user choice.
- Treat narration as audio-only (`Audio voiceover only, strictly no speech bubbles, no dialogue boxes`). For source-generated narration, quote the exact assigned dialogue and forbid alteration, repetition, captions, subtitles or visual transcription. For independent narration, keep its exact words and actual timings in the edit plan instead of the motion prompt.
- Never place technical color notation (hex, RGB, Pantone) inside generation prompts.
- Default generated clips to no visible words, letters, numbers, or interface copy. Put optional two-to-five-word overlays in a separate post-production note.
- Match every clip ending to the next clip opening through action, an important prop, screen direction or a planned cut. Style 4 uses deliberate scene changes or approved time jumps; it does not require the same background in adjacent clips.
- Do not invent unsupported facts, statistics, quotations, or product claims.

## Revision rules

Recompose rather than rename:

- `16:9`: stage action across left, center, and right; use lateral tracking and negative space.
- `9:16`: use depth, stacked motion, vertical reveals, and interface-safe placement.

Theme, ratio, duration, or style changes require a fresh visual balance check. A global change invalidates prior approval.

## Final check

Apply the checklist in the loaded reference. Repair any failed condition before responding.
