<p align="center">
  <img src="assets/terminal.svg" alt="whoami: Titouann Wtt, software engineer, founder of Jam Jam. Focus: AI tooling, Python backends, trading systems, music apps. Open to opportunities." width="100%">
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/titouann-wtt/"><b>LinkedIn</b></a> ·
  <a href="https://jam-jam.org"><b>jam-jam.org</b></a> ·
  <a href="#en-bref"><b>En français</b></a>
</p>

I build products end to end: the model, the backend, the app, and the store listing. Today that means a
music app I founded, an open-source trading stack, and the AI tooling that helps me ship both.

## Founder of Jam Jam

[**Jam Jam**](https://jam-jam.org) is a free chord, key and tempo detector with an editable songbook. Drop an audio
file or play into the mic: on the web, detection is free and unlimited in your browser, with no account. It also comes
as an Android app and an iOS public beta.
[Try the detector](https://jam-jam.org/app/detection) · [Overview](https://github.com/titouannwtt/jam-jam) ·
[Android](https://play.google.com/store/apps/details?id=com.jamjam) · [iOS beta](https://testflight.apple.com/join/fx95DYFE)

- **On-device AI**: chord recognition, beat tracking and stem separation, exported to ONNX and run in the app.
- **Built end to end**: React Native app (Expo, Kotlin native modules), Astro website, Supabase
  backend, Python audio service, public REST API.
- Open parts: [`jam-jam`](https://github.com/titouannwtt/jam-jam) (how the detector works, and where to try it),
  [`jam-jam-assets`](https://github.com/titouannwtt/jam-jam-assets) (versioned models and sounds, with checksums
  and licenses) and [`jam-jam-api-examples`](https://github.com/titouannwtt/jam-jam-api-examples) (API guide and
  examples).

## Trading systems

| Project | What it is |
|---|---|
| [**freqtrade-ultimate**](https://github.com/titouannwtt/freqtrade-ultimate) ![stars](https://img.shields.io/badge/%E2%98%85-26-3FB950?style=flat) | Production fork of Freqtrade for Hyperliquid. Shared data cache across bots (75 % fewer API calls, measured live with four bots), walk-forward and CPCV validation, liquidation detection. |
| [**frequi-ultimate**](https://github.com/titouannwtt/frequi-ultimate) ![stars](https://img.shields.io/badge/%E2%98%85-10-3FB950?style=flat) | Multi-bot dashboard for Freqtrade: fleet comparison, risk overview, strategy tooling. Vue 3, Pinia, ECharts. |

Both are maintained with the **Freqtrade France** community.

## AI engineering

- [**claude-tools**](https://github.com/titouannwtt/claude-tools): my Claude Code setup. Every task goes to the
  cheapest model that can do it (Haiku, Sonnet or Opus), a hook enforces the routing, and reusable work becomes
  a tested skill. Fewer tokens, same reliability.
- [**vault-core**](https://github.com/titouannwtt/vault-core) and [**pp-connect**](https://github.com/titouannwtt/pp-connect):
  the security-critical parts of Prompt Pipeline, open for audit (Argon2id + AES-256-GCM vault, relay layer
  with anti-SSRF guards and secret redaction).

## Stack

**Languages** Python · TypeScript · Kotlin · Rust · SQL<br>
**Product** React Native / Expo · Astro · Vue 3 · Supabase (Postgres)<br>
**AI and data** ONNX Runtime · PyTorch · Claude Code and the Claude API · Freqtrade<br>
**Education** Engineering degree, ESIEA (after a two-year computer science degree, DUT)

**Open to opportunities.** The quickest way to reach me is [LinkedIn](https://www.linkedin.com/in/titouann-wtt/).

---

<h2 id="en-bref">En bref</h2>

Ingénieur logiciel, diplômé de l'ESIEA, je construis des produits de bout en bout. Je suis le fondateur de
[Jam Jam](https://jam-jam.org), une application qui détecte les accords des chansons grâce à une IA qui tourne
sur l'appareil. Je développe aussi [freqtrade-ultimate](https://github.com/titouannwtt/freqtrade-ultimate), une
plateforme de trading algorithmique open source suivie par la communauté Freqtrade France, et
[claude-tools](https://github.com/titouannwtt/claude-tools), ma boîte à outils pour travailler avec des agents IA
à moindre coût. **Ouvert aux opportunités** : écrivez-moi sur [LinkedIn](https://www.linkedin.com/in/titouann-wtt/).
