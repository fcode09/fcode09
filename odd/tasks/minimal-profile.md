# Minimal bilingual GitHub profile

## Objective
Replace the long profile with a compact, personal, futuristic full-stack introduction.

## Authorized scope
- README.md: English introduction, collapsible Spanish translation, shared confirmed stack, LinkedIn only.
- assets/header.svg: static graphite/cyan geometric header with Freddy Quea and Full-stack Developer.
- odd/tasks/minimal-profile.md: implementation progress and evidence.
Preserve workflows and unrelated untracked .atl/. No remote operations or publishing.

## Decisions
Confirmed stack: TypeScript, Go, Python, Dart; Angular, NestJS, Flutter; Docker and DevOps (practices, not framework).
No stats, animations, trophies, visitor counter, placeholder projects, or unconfirmed claims.
Delivery: ask-on-risk; estimated 330 authored changed lines, one coherent work-unit commit on feat/minimal-profile.
RDD: off (global); do not start native review or ask for review consent.

## Tasks
- [ ] T1 — Profile and local SVG implemented and checked; closure awaits commit identity. Route: direct inline by explicit user override ("usa el agente actual") after unavailable delegated model.

## Acceptance and verification
- English bio: I build web and mobile apps, automations, and AI tools.
- Spanish details: Sobre mí · Español; Desarrollo aplicaciones web y móviles, automatizaciones y herramientas de IA.
- LinkedIn: https://www.linkedin.com/in/freddy-quea/.
- Local SVG, accessible alternate text, readable desktop/mobile layout and dark/light presentation.
- Run git diff --check; parse SVG as XML; inspect README content/link structure and no remote image dependencies.
- Render SVG locally if installed tools permit; report any unavailable GitHub/mobile rendering checks honestly.
- TDD exception: passive Markdown/SVG content, no meaningful application RED test or runtime boundary.
- Rollback boundary: README.md and assets/header.svg only; no application APIs or dependencies change.

## Progress
Implemented on feat/minimal-profile. Delegation blocker resolved by the user's explicit current-agent override.
- README reduced to 20 lines with English bio, Spanish details, shared stack and LinkedIn.
- Static SVG added with no scripts, animation, remote resources or dependencies.
- `git diff --check`: PASS after replacing Markdown double-space breaks with explicit br tags.
- Python XML/content checks: PASS (SVG structure, no active/external elements, bilingual text, stack exactly once, single LinkedIn destination, local image path).
- `rsvg-convert -w 800 assets/header.svg -o /tmp/fcode09-header-desktop.png`: PASS; image visually inspected.
- `rsvg-convert -w 320 assets/header.svg -o /tmp/fcode09-header-mobile.png`: PASS; image visually inspected.
- Text contrast against lightest banner background: name 16.31:1; role 12.33:1. Banner is opaque and independent of surrounding theme.
- Full GitHub rendering, browser interaction and remote LinkedIn reachability: not tested; no remote operations authorized/performed.
- Existing workflows and untracked .atl/ preserved. No application test runner applies.
- RDD: disabled/unmanaged; no native review started.
- Work-unit commit: blocked by missing Git author identity (user.name/user.email). No identity guessed or configured. Initial staged diff: 88 additions + 176 deletions = 264 authored changed lines, below delivery threshold.

## Next step
Ask the user for Git author name/email and local configuration authorization; then commit, record its identity and close T1. Publishing remains the user's decision.
