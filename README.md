# Children's Music Video Workflow

A personalized workflow for producing original, child-friendly animated songs with [CloneVoice.ai](https://www.clonevoice.ai), [Artistly.ai](https://artistly.ai), and [VideoExpress.ai](https://www.videoexpress.ai).

## Workflow

1. **Intake** — Provide the song/story idea and choose the project-wide aspect ratio: Landscape 16:9 or Vertical 9:16.
2. **Plan** — Freeze age-appropriate lyrics, the song direction, and a lyric-mapped storyboard before generating visuals.
3. **Make the song** — Generate the complete song once in CloneVoice, then check it as far as the available tools allow.
4. **Build the storyboard** — Create one distinct Artistly design for each planned scene, with consistent character identity and wardrobe.
5. **Animate** — Create one VideoExpress clip per accepted design, preserving scene action and aspect ratio.
6. **Assemble and export** — Put the clips in story order, add the song once, align opening and ending, save the project, and submit the export.
7. **Verify** — Confirm the export status and report only checks actually performed.

## Start here

Copy the full [SYSTEM_PROMPT.md](SYSTEM_PROMPT.md) into your production agent's instructions. Then provide a request such as:

> Create a children's music video about healthy daily habits. Use Landscape 16:9. Make the song gentle medium pace, with clear, simple lyrics for young children and warm animated visuals.

You must specify the theme and aspect ratio. Duration, child age range, language, tempo, voice type, mood, and art direction can be added when desired; sensible defaults are documented in the prompt.

## Project structure

- `SYSTEM_PROMPT.md` — Current copy-ready children's music video workflow.
- `UPSTREAM_SYSTEM_PROMPT.md` — Original history-narrative prompt retained for reference.
- `README.md` — Workflow overview and startup instructions.
- `WORKFLOW_LEDGER_TEMPLATE.md` — Fillable checkpoint for resumable runs.

## Safety and honest status

Keep generated projects private. Do not publish, share externally, buy upgrades, change account security, or clone a real person's voice without the necessary specific authorization and consent. A queued export is not a completed downloadable file. Report the exact visible status and do not claim playback or audio checks that were not actually performed.

This repository is a personal adaptation of [ai-playbooks/clonevoice-videoexpress-2d-narrative-workflow](https://github.com/ai-playbooks/clonevoice-videoexpress-2d-narrative-workflow). The upstream project remains unchanged.
