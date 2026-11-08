# Omni Flash Production Prompt Contract

Use this A1–A5 contract after approval of the current Phase A. Apply [story-led directing](directing-craft.md), `style-catalog.md` and `voice-continuity.md` without replacing each style's drawing or complete voice profile. Flow Omni 1.2 Flash with ten-second source generations is the default target; inspect the live model label, mode, ratio, resolution, available duration and credit quote before submitting. A source clip is not an editorial shot: preserve the requested film duration and actual speech, and plan trims, handles and a flexible source count from the approved storyboard. Never round the film to a multiple of ten or assume target output settings are guaranteed.

Style 3 (Prehistoric Hand-Drawn / Dark Comedy): read `prehistoric-dark-comedy.md` and apply its override rules. Repeat the full approved cast descriptions for all visible roles, white filled heads, expressive cartoon faces, hair/clothing, earthy setting and layout in every prompt. Do not apply generic face/hair/texture bans or idle bans to its deliberate reaction beats. Use story-appropriate music instead of mandatory piano. Explicitly identify intended time jumps; otherwise match adjacent states. Technical output specs are targets, not guarantees of interface capabilities.

Style 4 (Cozy Storytelling / 治愈故事风): read `cozy-storytelling.md`. Repeat full character and voice anchors and use the story-appropriate approved setting for each shot. Name intentional location or time cuts and connect the story through action, prop or screen direction; do not force a new location for each generated source. Do not inherit Style 1's no-face/filled-body bans or require hand-drawn/paper aesthetics. Keep movable-object appearance separate from initial positions and timed state changes.

Style 5 (Historical Cartoon / 历史卡通风): read `historical-cartoon.md` for its standalone prompt order and overrides. Repeat the full frozen drawing anchor, visible cast cards and approved era pack in each relevant clip; repeat the complete `voice-continuity.md` block in clips that generate narration. Keep connected short white necks, expressive individual faces, solid oval eyes, thin black exposed limbs and small solid black mitten-shaped palms continuous with the wrists, one subtle integrated thumb lobe, no individual fingers, finger separations, white fills or gloves, with historical costume and colored painterly scenery. Do not inherit Style 1's hollow-head/no-face/no-clothes contract or generic piano, three-color, four-device and no-idle requirements. Follow its era score, physical beats and planned cuts; do not shorten approved anchors to meet an arbitrary character budget.

## Production package order

Deliver these sections in order:

1. Global continuity block
2. One standalone English prompt for each planned ten-second source generation, with a flexible source count derived from the approved story and edit
3. Stitching guide
4. Voice and music continuity note

## Global continuity block

State the chosen aspect ratio (`16:9` or `9:16`), target duration, selected visual style (Style 1 Classic, Style 2A Studio Tech, Style 2B Cinematic Story, Style 3 Prehistoric, Style 4 Cozy Storytelling, or Style 5 Historical Cartoon), character anchor design, palette or environment definition, narrator identity, audio arc, and continuity strategy. Treat this block as a review summary; each prompt still repeats all critical visual locks and applicable audio locks.

## Standalone prompt order

Write every prompt in this order:

1. Output specification: Flow Omni 1.2 Flash, ten-second source target and chosen aspect ratio (`16:9` or `9:16`); include resolution, frame rate and audio settings only as supported by the current interface and approved plan
2. Environment and background definition:
   - For Style 1 Light: flat, uniform, digitally pure-white canvas with no shading or 3D depth
   - For Style 1 Dark: flat, uniform, pitch-black canvas with pure white line art
   - For Style 2A (Studio Tech): modern bright white studio space with subtle light-gray perspective grid lines on the floor plane, high-key lighting, clean white negative space, sleek glowing cyan/blue glass elements
   - For Style 2B (Cinematic Story): rich full-color cinematic environment with volumetric lighting and depth of field
   - For Style 4 (Cozy Storytelling): full-color 2D cartoon environment and a story-appropriate setting, with purposeful wide/close/moving shots; a new source segment does not require a scene change
3. Character lock:
   - For Style 1: repeat the concise frozen character anchor from `style-catalog.md`, including the chosen polarity and expression setting; no "same character" shortcuts, numeric anatomy recipes, skeleton/rig definitions or pen paths. Keep the circular head hollow, proportions and line weight stable, and only the current pose of each of the two arms and two legs. A raised arm replaces its old lowered line. Keep accents on props/graphics, never recolor the figure. Do not let action or camera wording redefine the drawing; preserve rich motion and effects separately.
   - For Style 2 (Modern Beanie Zeke):
     - Repeat this full default anchor in every standalone source prompt: `A minimalist 2D animated stick figure wearing a bright red beanie (smooth knit, no pom-pom) and a yellow t-shirt, with simple black stick limbs and shorts. Simple black lines, vibrant colors, smooth 2D animation style.`
     - If the user approved a different outfit or cast, freeze and repeat that complete approved anchor instead; never abbreviate it to “same character” or an ellipsis.
   - For Style 4: repeat its full frozen character anchor from `cozy-storytelling.md`, including white head/torso fill, dark limbs and simple facial marks. Location and expression changes do not redesign the character.
4. Palette and accent roles (expressed only with ordinary color names, no hex or technical codes)
5. Composition strategy for the chosen ratio (`16:9` or `9:16`)
6. First-frame state inherited from the previous clip
7. The story-specific primary action or meaningful reaction, timing where useful, physical contact and resulting state tied to the spoken idea; use purposeful pauses and avoid a fixed three-beat formula
8. For source-generated voice, quote the approved audio-only dialogue assigned to that usable source range. For separately generated or accepted narration, keep the exact words and timestamps in the edit plan and omit narration and narrator direction from the visual-generation prompt.
9. For source-generated voice, repeat the complete frozen profile from `voice-continuity.md` in each applicable prompt. For independent voice, retain the approved provider, voice and profile in the production record; never recast an accepted track.
10. Story-appropriate music and synchronized SFX; keep speech intelligible and the selected musical motif continuous, whether generated or assembled separately.
11. Final-frame transition state inherited by the next clip
12. Negative constraints (including style-specific clutter/deformation bans)

Make each prompt self-contained and usable without any external context.

## Style language

Direct purposeful visual change without character drift:

> Select story-relevant action, framing, reaction and timing while preserving the approved stick-figure design, constant line weight and temporal continuity.

Avoid `rapid style changes`, which can invite model changes to drawing style, line weight, or character design.

## Timed visual sequence & motion dynamics

Translate the approved editorial purpose into a legible action or reaction, with clear initial and final states. Timing follows the story and the selected usable interval; one generated source can support more than one editorial cut. A deliberate reaction or hold is valid when it contributes meaning. Avoid asking a model to combine several risky contacts or object transfers solely to fill ten seconds.

### Anti-Stutter & Anti-Lag Guidelines:
- Do not use abstract liquid or object shape morphing (e.g., stairs melting into a clock), as these cause diffusion latent jitter and frame drops.
- Drive motion with concrete character actions (leaping, touching glass, drawing luminous lines, opening heavy doors).
- A still moment can carry a reaction or suspense; avoid meaningless idle filler rather than banning all pauses.

## Dialogue and visual text

When source-generated narration is chosen and available, quote the approved narration assigned to the source exactly once as audio-only dialogue:
```text
Audio voiceover only, strictly no speech bubbles, no dialogue boxes.
```
Instruct the model not to add, omit, paraphrase, repeat, reorder, caption, subtitle, or visually transcribe words. When independent narration is chosen, keep the script outside motion prompts and align the accepted track in post. Preserve exact narration across editorial cuts; do not synthesize duplicated words merely because source clips overlap.

Default every generated clip to no visible words, letters, numbers, captions, subtitles, interface copy, palette labels, production annotations, logos, or watermarks. Require icon-only message bubbles, content cards, clocks, meters, and notifications. Put optional approved phrases in a separate post-production overlay list outside the prompts.

## Palette notation

Use ordinary descriptive color names such as vivid red, electric blue, or warm gold. Never put hexadecimal, RGB, HSL, Pantone, or other technical color notation in a generation prompt. Models may reproduce prominent notation literally as unwanted interface text.

## Audio continuity contract

Use the shared contract in `voice-continuity.md` for A1–A5. Choose voices per video, not per clip. Explicit user voice and independent-audio choices prevail; repeat the full voice and music instructions in applicable source-generated audio prompts, not in visual-only prompts:

1. **Narrator Lock**: Resolve one complete approved profile, then repeat its frozen block verbatim in each source-generated narration prompt. Use the accepted male block or build another coherent profile; do not force all videos into one voice. For an independent narrator, keep the approved voice and existing recording unchanged and specify the track once in the edit plan. Separate voice identity/delivery/recording treatment from the emotional and musical arc; no scene-specific timbre changes or switches into character dialogue unless explicitly approved.
2. **BGM Lock**: The opening establishes the chosen style-appropriate musical motif; subsequent cues preserve its approved instrumentation and continuity, with motivated SFX. Do not force the historical piano example into styles or stories that require another score.

## Negative contract

Forbid:

- photorealism and unwanted 3D humanoid rendering
- facial features (pupils, realistic eyes, lips) or hair unless approved
- extra limbs, malformed anatomy, disconnected lines, or changed proportions
- broken or changing line weight
- **For Style 1**: do not reject allowed occasional simple line expressions as character drift; filled heads, sudden head/body proportion changes, duplicated/retained limb poses, body silhouettes, separate hand/foot shapes and detached body lines remain failures. Inspect actual footage at reaches, releases, turns and walking poses, and compare clips. State the scope of inspection: sparse keyframes cannot prove the absence of brief errors.
- inverted theme polarity or unexplained colors
- unintended characters or irrelevant spectacle
- visible words, letters, numbers, technical color notation, palette labels, interface copy, captions, subtitles, logos, or watermarks
- altered, omitted, repeated, reordered, or added dialogue
- speech bubbles, comic dialog balloons, or visual text boxes
- **For Style 2A specifically**: `strictly minimalist studio aesthetic, no circuit board textures, no sci-fi wall panels, no spaceship corridors, no cracked concrete, no grunge textures`
- **For Style 2B specifically**: `no photorealistic human skin, no 3D humanoid CGI models, no chaotic line glitches`

## Stitching guide

List planned source clips and editorial cuts separately. For every cut, specify the outgoing and incoming action/prop/direction or the approved location/time change. Include candidate usable ranges and any necessary audio crossfade; inspect actual generated joins rather than assuming requested wipes landed on a boundary. Style 4 may change scenery intentionally or remain in one story-appropriate setting.

## Audio continuity note

Start with prompt-level consistency, rather than immediately routing voice drift to external dubbing:

1. For source-generated narration, check applicable prompts repeat the frozen voice block without conflicting directions; for independent narration, check the recording and its intended timeline instead. Compare actual audio by listening, not from screenshots.
2. If authorized, retest a voice-only change while holding visual instructions, dialogue, music and generation settings fixed. User-accepted improvement in the three-clip Style 2A Hope test supports this approach, not a guarantee for every profile or style.
3. Voice/audio references when supported, or one continuous external English VO/BGM track during assembly, remain optional further controls if exact matching is required or prompt-first correction is insufficient.

## Phase B checks

- The user approved the current Phase A.
- Each planned source generation has one standalone prompt; the source count and final shot count follow the approved edit rather than duration divided by ten.
- Each prompt repeats ratio (`16:9` or `9:16`), style/theme, character, palette, applicable audio, transition and negative locks. An independent accepted voice remains in the edit plan rather than a visual-only motion prompt.
- Style 1 prompts repeat one identical full character block and contain no contradictory appearance instructions. Simple-expression allowance agrees with the negative constraints. Generated consistency is checked separately from prompt compliance.
- Each prompt gives a legible story-specific action or reaction, relevant timing and resulting state without mandatory beats or decoration quotas.
- Editorial cuts connect through a planned action/prop/direction or a story-appropriate location/time cut; the same room may recur when the story calls for it.
- The delivered narration exactly matches the approved text; source-generated segments contain only their assigned words.
- Dialogue is explicitly audio-only and is never displayed visually.
- Standalone prompts contain no hexadecimal, RGB, HSL, Pantone, or other technical color notation.
- Style 2 prompts feature the verified character anchor, BGM continuity lock, and anti-clutter negative constraints.
- Source-generated narration repeats an identical complete voice block per video or approved speaker; independent narration preserves the approved provider, voice and recording in the edit. No unresolved profile fields or contradictory vocal directions remain. Actual audio acceptance is recorded separately from prompt compliance.
- Generated scenes contain no visible writing; optional overlay phrases are listed separately for post-production.
