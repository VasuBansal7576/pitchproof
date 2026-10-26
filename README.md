# PitchProof

Campaign research for independent creative agencies. Turn a client brief into three creative directions with cultural evidence and a small test plan.

[Open PitchProof](https://pitchproof-studio.zippy17.chatgpt.site)

## Verified workflow

The running-footwear workflow was exercised on the public deployment with real Qloo and Gemini on October 25, 2026. Checks covered exact brand confirmation, cross-category research, three directions, fresh feedback-led research and revision, choices, rejections, agency notes, immutable history and reload. Actual Qloo reference images appear in the workspace and printable brief.

The app exports printable HTML, which can be printed to PDF, and Markdown with a preview and copy option. The embedded test browser cancels native file downloads. Its Markdown preview and copy path was verified instead. Four pages of the actual printed brief were visually inspected. A 390-pixel layout check does not establish real-phone hardware compatibility.

Generated directions are proposals for agency review. The tests included rejecting an off-brief alternative and adding production controls before approving a selected direction. Qloo associations do not establish measured customer tastes, purchase intent or campaign performance.

## Complete source

Download [pitchproof-source.tar.gz](pitchproof-source.tar.gz). It contains all 152 tracked source files, assets, migrations, setup instructions, scripts, tests and the MIT license for the deployed source.

Source commit `35eb2cb1016c2679f22cd01741271f71d6731380`.

Archive SHA256 `b2160f732cfa4857b252796ba6a28c89237d8954e565aba2841ea242adf6cc20`.

## Run locally

```sh
git clone https://github.com/VasuBansal7576/pitchproof.git
cd pitchproof
tar -xzf pitchproof-source.tar.gz
npm ci
cp .env.example .dev.vars
```

Add server credentials to the ignored `.dev.vars` file. Follow the extracted README to build, apply local D1 migrations and start the app. Extraction replaces this distribution page with the full setup guide. Never put keys in source or command arguments.

## Qloo-powered workflow

- Three exact reference-brand identities and their competitor, aesthetic or audience-proxy roles drive Qloo queries.
- Research spans brands, artists, films, places and podcasts, with checkpointed results and explicit geographic scope.
- Three creative hypotheses cite canonical observations from their own research run.
- Feedback can request new categories and creates fresh research before revision.
- Choices, rejections, agency notes and generation history remain persistent and separate from source observations.
- Reference imagery, Markdown and printable HTML retain evidence provenance.

A controlled same-brief and same-prompt comparison changed only reference brands. It returned 52 versus 51 distinct Qloo entities with one shared entity and materially different creative inspirations. This is evidence of reference sensitivity in that case, not a statistical claim about campaign effectiveness or an LLM-only benchmark.

## Verification and limits

The current source passed 66 behavior tests, TypeScript and a production build. Local tests use synthetic fixtures. Actual provider and campaign artifacts remain outside this repository. The final release uses stateless Gemini Interactions requests, short model-local citation labels and strict mapping to canonical Qloo records. Invalid citations and unsupported visual references remain rejected.

The opt-in `scripts/verify-live-flow.mjs` offers configuration preflight, storage-only checks and actual-provider API smoke. A script pass does not replace browser and semantic review. Guest workspaces are tied to the browser session. Product facts are entered by the agency; a website URL is context and is not scraped. Running footwear was the live verification category.

## License and separate operator steps

MIT applies to the application source. Qloo data, API access, model services and third-party assets retain their own terms. Confirm commercial rights and production pricing before selling briefs. Paid demand validation, real-phone hardware QA and Devpost submission remain separate steps.
