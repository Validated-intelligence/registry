# Validated Intelligence — public registry

This repository is the public, append-only registry for **Validated Intelligence
(VI)** validation tokens (`VI-NO-YYYY-NNNN`). Each record commits to the full
claims table of one document via a Merkle root, **without revealing the claims**
before publication.

- Browse / verify a token: the GitHub Pages site for this repo (`index.html`).
- Records live in `registry/<token>.json`; `registry/index.json` lists them.
- The git history of this repo is the authoritative, tamper-evident timestamp.

VI is part of the Koja Intelligens family and run independently — it never
validates Koja's own output. Governance: see the `vi` repo's `GOVERNANCE.md`.

No tokens issued yet.
