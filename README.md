# barelabel-public

This repository exists **only** to host the rendered HTML of the BareLabel privacy policy and terms of service so that GitHub Pages can serve them publicly (Play Console requires a sign-in-free privacy URL).

- **Source of truth:** the private `BareLabel` repository.
- **Updates here:** automated by the `publish-legal-site` GitHub Actions workflow in the private repo. Every push to `main` that touches `docs/legal/*.md` regenerates this repo's contents.
- **Do NOT edit files in this repository directly.** Manual edits will be overwritten on the next publish.

The site is served at `https://POLEPALLIANVESH.github.io/barelabel-public/`.
