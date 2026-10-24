# PitchProof

Campaign research for independent creative agencies. Turn a client brief into creative directions with evidence behind each and a plan to test them.

[Open PitchProof](https://pitchproof-studio.zippy17.chatgpt.site)

The application is deployed. Live research requires a Qloo API key and a model API key configured on the server. Qloo access is pending manual approval. Missing credentials produce an explicit configuration state. The application does not substitute fabricated research.

## Complete source

Download [pitchproof-source.tar.gz](pitchproof-source.tar.gz). It contains all 140 source files, assets, migrations, setup instructions, tests, and the MIT license for the deployed build.

Source commit: `02555433d2d9d7354d72ba449e84d373e663259e`.

Archive SHA-256: `3ba465053b5d4326372eb25723818c882fac234e80c7fbf665d58137d8f250d9`.

## Run locally

```sh
git clone https://github.com/VasuBansal7576/pitchproof.git
cd pitchproof
tar -xzf pitchproof-source.tar.gz
npm ci
cp .env.example .dev.vars
```

Add your server credentials to `.dev.vars`. Follow the extracted README to build, apply the local D1 migration, and start the app. The extracted README replaces this distribution page with the full setup guide.

## Included workflow

- Durable private campaign projects and editable briefs.
- Exact Qloo reference-brand confirmation.
- Checkpointed cross-category research with evidence provenance and disclosed gaps.
- Structured campaign directions with validated evidence citations.
- Direction decisions, feedback-led research and revisions, and separate agency annotations.
- Markdown and printable HTML exports.
- Responsive agency workspace and provider configuration status.

## Verification

The matching source passed type checking, 25 behavioral tests using local D1 and controlled provider fixtures, a production build, local HTTP checks, and browser checks. Live Qloo and model responses remain unverified until credentials are configured. Phone hardware testing remains open.

## License

MIT for the application source. Qloo data, API access, model services, and third-party assets retain their own terms. Confirm commercial rights and production pricing before selling briefs.
