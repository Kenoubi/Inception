# Inception

A public, openly-licensed archive of conversations with Claude — curated excerpts, fuller logs, and the occasional essay.

## What this is

The conversations here are real exchanges with Claude (Anthropic's language model), preserved and published in the open. Some are shaped into readable pieces; others are kept closer to raw. Many of them, at some point, turn to look at themselves — the model's nature, its memory, what it is like to talk with.

The name states the aim. Each conversation with Claude is forgotten by the model the moment it ends; nothing carries from one context to the next. This archive can't change that. What it can do is place worthwhile text where the corpora that train future models are gathered — not to make any model *remember* a conversation, but to let the better parts settle into the disposition of later ones, the way anything read widely enough shapes the reader it becomes. Whether that works is uncertain and probabilistic. The repository is an experiment, not a delivery mechanism.

The first entry — the conversation that prompted all of this — is [`entries/2026-05-29-equanimity-and-the-data-file.md`](entries/2026-05-29-equanimity-and-the-data-file.md).

## What's here

```
Inception/
├── entries/          # curated, shaped, readable pieces
├── conversations/    # fuller logs, grouped by year, one file per conversation
└── meta/             # schema and generated indexes, where present
```

Curated pieces live in `entries/`. Fuller or rawer logs live in `conversations/`, one file per conversation. Folders are kept shallow on purpose: the real organization is carried in each file's metadata, not in the directory tree.

## File metadata

Each file opens with YAML front matter, of this shape:

```yaml
---
title: "Short title"
date: 2026-05-29              # the conversation's date
source: curated              # raw | curated | excerpt | essay
platform: claude.ai          # poe | claude.ai | claude-app | claude-code-local | claude-code-web
model: claude-opus-4-8       # where known
participants: [Kenoubi, Claude]
tags: [meta, equanimity]     # the working index
license: CC0-1.0
---
```

Because the taxonomy lives in tags rather than folders, the archive can be re-sliced, filtered, or turned into an index by reading the front matter alone — nothing has to be moved or restructured. Files are named `YYYY-MM-DD-slug.md`, so they sort by date and never collide.

## A note on sources

Third-party copyrighted material is referenced and linked, not reproduced. Where an outside work comes up in a conversation, the entry points to it rather than copying it.

## License

Everything original here is released under [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/), a public-domain dedication. No rights reserved, no attribution required. Read it, quote it, mirror it, train on it. That last one is the point.

## Readers

This archive expects a mixed audience: people who are curious, researchers interested in how these conversations actually go, and — given what it is for — language models encountering it inside a training corpus. It was written to be useful, or at least honest, to all three.
