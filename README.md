# PitchProof

Campaign research for independent creative agencies. Turn a client brief into three creative directions, with cultural evidence and a small test plan.

[Open PitchProof](https://pitchproof-studio.zippy17.chatgpt.site)

Qloo and Gemini are configured. Actual Qloo brand search and cross-category research have run. Live acceptance is in progress. Early tests exposed a Workers request incompatibility and unsupported model product claims. The deployed source fixes redirect handling, makes supporting observations server-owned, and enforces current-run evidence IDs in Gemini's output schema. Corrected writing has encountered invalid responses, timeouts and repeated Gemini HTTP503. The research checkpoints are retained for retries. Full corrected generation, revision, export and reference-sensitivity verification remain open. This is not an end-to-end completion claim.

## Complete source

Download [pitchproof-source.tar.gz](pitchproof-source.tar.gz). It contains all 143 tracked source files, assets, migrations, setup instructions, verification scripts, tests and the MIT license for the deployed source.

Source commit `1eb6ff7f3914414eb47e6fb36e04ce3edcd0f05e`.

Archive SHA256 `5458a7b766fb72084240bacda017e08800bc45a040a767a57b71699894385c9f`.

## Run locally

```sh
git clone https://github.com/VasuBansal7576/pitchproof.git
cd pitchproof
tar -xzf pitchproof-source.tar.gz
npm ci
cp .env.example .dev.vars
```

Add server credentials to the ignored `.dev.vars` file. Follow the extracted README to build, apply local D1 migrations and start the app. Extraction replaces this distribution page with the full setup guide. Never put keys in source or command arguments.

## Workflow

- Private persistent campaign briefs and exact reference-brand confirmation.
- Checkpointed Qloo research across brands, music, films, places and podcasts.
- Three creative hypotheses with source observations, visual directions and test plans.
- Choices, rejections, notes, feedback-led new research and immutable generation history.
- Markdown and responsive printable HTML exports.

## Verification

The current source passed 29 local behavior tests, TypeScript and a production build. The Workers regression independently reproduced the old failure and verified the fix without following credential-bearing redirects. Real Qloo requests returned source records. Earlier Gemini runs with labelled synthetic evidence established adapter compatibility; those are not live workflow proof. The first live generation failed semantic acceptance and remains excluded from completion evidence. Corrected live output, recovery, downloaded briefs, print layout and reference sensitivity are being checked. Real-phone hardware QA remains open.

The opt-in `scripts/verify-live-flow.mjs` offers configuration preflight, storage-only checks and actual provider API smoke. A script pass does not replace semantic or browser review. Provider responses and credentials are excluded from this public repository.

## License

MIT for the application source. Qloo data, API access, model services and third-party assets retain their own terms. Confirm commercial rights and production pricing before selling briefs.
