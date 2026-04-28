# aiq-research-mirror

Public mirror of research methodology and plan templates used by the `aiq-research` Claude skill at ApartmentIQ.

## Why this repo exists

The Claude skill fetches these templates at runtime via `curl` when generating research plans. A public repo lets the skill resolve template URLs anonymously without an auth dance inside the skill itself.

## Source of truth

These files are mirrored from the private Workshop vault (`03 Resources/Research/`) maintained by Josh Dean. **Do not edit files in this repo directly**—a GitHub Action overwrites this repo on every push to the source. Edit in the vault; the mirror updates automatically.

## Contents

- `Methods.md`—the four-lens decision framework (Discovery, User Test, Feedback, Experiment) with NN/g-aligned criteria for whether and how to research
- `Discovery/`—`Discovery.md` (plan template), `Discovery Results.md`
- `User Test/`—`User Test.md` (plan template), `User Test Results.md`
- `Feedback/`—`Feedback.md` (plan template), `Feedback Results.md`, `Question Rationale.md` (per-question NN/g rationale)
- `Experiment/`—`Experiment.md` (plan template), `Experiment Results.md`

## Foundations

The four-lens taxonomy and qualitative templates draw from Christian Rohrer's *Landscape of User Research Methods* (NN/g). The Experiment template's rigor framework draws from Ron Kohavi's *Trustworthy Online Controlled Experiments*, since NN/g focuses on A/B testing's role alongside UX research rather than its statistical methodology.
