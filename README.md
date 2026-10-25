# PitchProof

Campaign research for independent creative agencies. Turn a client brief into three creative directions, with cultural evidence and a small test plan.

[Open PitchProof](https://pitchproof-studio.zippy17.chatgpt.site)

Qloo and Gemini are configured. The real-provider baseline API workflow has passed initial research, three directions, feedback-led new research, revision, persistence and HTML/Markdown exports. The live browser campaign also passed decisions, notes, reload and 390px interaction checks. Independent semantic review drove fixes for requested research categories, source-traceable visual references and unverified-feature test controls. Full final acceptance remains open while alternate-reference synthesis encounters Gemini rate limits and final verification is completed. This is not an end-to-end completion claim.

## Complete source

Download [pitchproof-source.tar.gz](pitchproof-source.tar.gz). It contains all 143 tracked source files, assets, migrations, setup instructions, verification scripts, tests and the MIT license for the deployed source.

Source commit `8f4d513e381a70de286b090e365b853f826f9d2c`.

Archive SHA256 `64535d2659b92e6bbf03442ed8e547e66dad459e7456e6a3d345dc3745492b47`.

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

The current source passed 30 local behavior tests, TypeScript and a production build. The model serving schema avoids state-heavy length constraints while the server retains every validation bound. Supporting observations are server-owned and cited to actual Qloo records. Visual inspirations use retrieved names or genuinely confirmed input brands. Explicit positive research-category requests are preserved. Completed actual-provider receipts and private campaign artifacts remain outside this repository. Real-phone hardware QA, commercial API rights and paying-customer validation remain open.

The opt-in `scripts/verify-live-flow.mjs` offers configuration preflight, storage-only checks and actual provider API smoke. A script pass does not replace semantic or browser review. Provider responses and credentials are excluded from this public repository.

## License

MIT for the application source. Qloo data, API access, model services and third-party assets retain their own terms. Confirm commercial rights and production pricing before selling briefs.
