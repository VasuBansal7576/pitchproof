# PitchProof

Campaign research for independent creative agencies. Turn a client brief into creative directions with evidence behind each and a plan to test them.

[Open PitchProof](https://pitchproof-studio.zippy17.chatgpt.site)

The application is deployed. Gemini is configured and passed real structured synthesis, feedback planning and revision using explicitly synthetic local evidence. Qloo access remains pending. Actual Qloo research and the complete live workflow are unavailable until Qloo issues a key. Missing access never produces fabricated research in the app.

## Complete source

Download [pitchproof-source.tar.gz](pitchproof-source.tar.gz). It contains all 142 tracked source files, assets, migrations, setup instructions, verification scripts, tests and the MIT license for the deployed source.

Source commit `234ecddd9efa7ce99c5608af82bfd7c55b797fa6`.

Archive SHA256 `752bbb8efef64003192df5565cb848d28077b82f2fd3b3f27c3e0174e9ed5ec4`.

## Run locally

```sh
git clone https://github.com/VasuBansal7576/pitchproof.git
cd pitchproof
tar -xzf pitchproof-source.tar.gz
npm ci
cp .env.example .dev.vars
```

Add server credentials to the ignored `.dev.vars` file. Follow the extracted README to build, apply local D1 migrations and start the app. Extraction replaces this distribution page with the full setup guide. Never put keys in source or command arguments.

## Included workflow

- Durable private campaign projects and independently saved new-campaign drafts.
- Correctable exact Qloo reference-brand confirmation.
- Checkpointed cross-category research with complete collected evidence and provenance.
- Three campaign directions with validated citations, visual treatments and test plans.
- Direction decisions, feedback-led new research, preserved history and separate agency notes.
- Markdown and responsive printable HTML exports.
- Responsive workspace, resumable operations and explicit provider status.

## Verification

The application passed type checking, 27 behavioral tests using local D1 and controlled provider responses, and a production build. Three real Gemini requests verified structured synthesis, feedback research planning and revision with clearly labelled synthetic evidence. Actual hosted storage checks passed persistence, owner isolation, command replay, stale-version rejection, cross-origin rejection and export readiness. Browser checks cover the repaired draft, cancellation, navigation, decisions and narrow-screen error recovery. Synthetic HTML and Markdown exports were inspected; four printed A4 pages were reviewed. Real Qloo responses, full live campaign completion, semantic citation fidelity and reference sensitivity remain unverified. Real-phone hardware testing remains open.

The source includes opt-in `scripts/verify-live-flow.mjs` for configuration preflight, storage-only checks or actual provider smoke tests. Read the extracted README for modes and limits. A script pass never replaces semantic and browser review.

## License

MIT for the application source. Qloo data, API access, model services and third-party assets retain their own terms. Confirm commercial rights and production pricing before selling briefs.
