<div align="center">

<img src="https://my-bi.github.io/assets/logo.svg" alt="MyBI" width="96" />

# MyBI

### Business intelligence that stays on your machine

Powerful dashboards, deep analytics and geospatial intelligence on **macOS, Windows &amp; Linux**.
Your data stays on your computer — no account, no cloud, no telemetry.

[**Website &rarr;**](https://my-bi.github.io) &nbsp;&middot;&nbsp; [Features](https://my-bi.github.io/#features) &nbsp;&middot;&nbsp; [Roadmap](https://my-bi.github.io/roadmap.html) &nbsp;&middot;&nbsp; [Build a plugin](https://my-bi.github.io/build-plugin.html)

</div>

---

## What is MyBI?

MyBI is a business intelligence platform that runs on your own computer. It turns raw data into
dashboards, deep analytics and geospatial intelligence without sending a single row to a server —
the engine runs locally, the project file is yours, and nothing leaves the machine unless you
deliberately export it.

It is built **block-first** — Importer, Semantic model, Calc Engine, Charts, Canvas and Analytics
each do one job well and compose into a workspace. Every number runs through a single Calc Engine,
so a total reads the same in every visual — checked, never assumed.

> Works fully offline &middot; No account required &middot; No cloud, no telemetry

---

## The MyBI family

One app, plus two focused desktop companions — for the people who publish plugins, and the people
who have to account for what left the building.

### MyBI &mdash; the app

The BI app itself. Import data, model it in the Semantic layer, calculate with the **Calc Engine**,
and build dashboards on an infinite canvas — charts, deep analytics and geospatial intelligence,
all offline, all on your machine. Free for everyone, on macOS, Windows and Linux.

→ [See what it does](https://my-bi.github.io/#features)

### MyBI Publisher Studio

A desktop signer for third-party plugin and palette authors. Generate your own **Ed25519** keypair,
sign your plugin locally, and submit your public key for countersignature — so your work ships with
the **"Trusted by MyBI"** badge after review. Your private key never leaves your machine.

→ [How cross-signing works](https://my-bi.github.io/verify.html)

### MyBI Forensic Studio — coming soon

A planned companion for security and compliance teams. It opens MyBI's encrypted, **forensic
exports** — a content key sealed to your organisation with **X25519**, the body under
**AES-256-GCM** — and verifies the **Ed25519 SHA-256 hash-chained audit log**, proving a bundle
hasn't been tampered with and showing the disclosed device fingerprint behind every export.

→ [On the roadmap](https://my-bi.github.io/roadmap.html)

---

## Private by design

MyBI keeps your data on your device — no account to create, nothing uploaded, nothing shared:

- **No lock-in** — projects live in portable `.mybi` files you can back up, move and keep, with or without MyBI.
- **Genuine plugins** — every plugin carries an Ed25519 signature the app checks on install, so you know it's authentic and untampered.
- **Sandboxed by design** — plugins run isolated, with declared permissions and no network by default; you control exactly what each one can touch.
- **Numbers that reconcile** — one Calc Engine behind every visual, checked by golden-number tests.

The only data that ever leaves is what you deliberately export.

---

<div align="center">

**Builds for macOS, Windows &amp; Linux are on the way.** &nbsp;&middot;&nbsp; [my-bi.github.io](https://my-bi.github.io)

<sub>Business intelligence that stays on your machine. &middot; Private by design.</sub>

</div>
