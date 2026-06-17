# BareLabel — public legal site

Live: https://polepallianvesh.github.io/barelabel-public/

| Document | URL |
| -------- | --- |
| Privacy policy | https://polepallianvesh.github.io/barelabel-public/privacy/ |
| Terms of service | https://polepallianvesh.github.io/barelabel-public/terms/ |

## What this repository is

This repository **only** hosts the rendered HTML of the BareLabel privacy
policy and terms of service so that GitHub Pages can serve them publicly
(Google Play Console + Apple App Store both require a sign-in-free
privacy URL).

## What this repository is NOT

- The BareLabel source code lives in a separate private repository.
- No engineering, design, or business documents are published here.
- The HTML here is auto-generated; do **not** edit files in this repo
  by hand — they will be overwritten on the next publish.

## How updates land here

Every time the privacy policy or terms of service change in the private
source repo, a GitHub Actions workflow there renders the markdown,
strips any internal cross-references, and pushes the resulting static
HTML to `main` of this repository via an SSH deploy key scoped to
this repo only.

Last published: 2026-06-17.

## Contact

- Privacy + data-rights requests: privacy@barelabel.app
- Security disclosure: security@barelabel.app
