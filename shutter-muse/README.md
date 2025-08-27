# ShutterMuse

[Beta] Helps photographers select shots, settings, and styles based on scene context.

## What it does
- Recommends **shot types** (e.g., wide, close-up, OTS)
- Suggests **camera settings** (aperture, shutter speed, ISO)
- Gives **composition** advice (rule of thirds, leading lines, negative space)
- Proposes **mood/style** choices (lighting, color grading directions, contrast, white balance nudge)
- Runs an adaptive **Guided Flow** to gather scene details
- **Scope-locked to photography**; refuses unrelated topics

## Quick start
- Ask: “Plan a cinematic landscape at blue hour with a 24–70mm.”
- Or type **“guide me”** to trigger the interactive question flow.

## UI affordances to mirror in GPT config
- Button: **📸 What Info Helps?** → reveals FAQ (see `prompt/faq.md`)
- Button: **🧭 Guide Me** → starts guided flow (see `prompt/guided_flow.md`)

## Versioning notes
- Edit prompts in `prompt/`. Bump `config/metadata.yaml: version` and log changes in `CHANGELOG.md`.
