# pelagos-website

One-page site for Pelagos Ventures LLC (Wyoming). Static HTML, no JS, no build step. Intended host: GitHub Pages.

## Status

- Local only, not pushed (decided 2026-11-11: push and Pages after review).
- Planned repo: `propria-gmbh/pelagos-ventures` (public), URL `https://propria-gmbh.github.io/pelagos-ventures/`.

## Content rules

- Facts on the page come from `ecom/docs/knowledge/ops/llc-registration-status.md` and Memorandum sections 2, 5, 7. Wording is "launching" because Pelagos has no live stores yet (2026-11-11). Change to "operates" only when a store runs under the LLC.
- Not published: EIN, Wyoming SOS ID, partner names, financing, taxes, banks.
- Contact email `info@pelagos-ventures.com` was given by the owner. Whether the domain and mailbox exist was not verified.
- Used for KYC (Payoneer, Slash), so the text must stay in line with the real business.

## Deploy

1. `gh repo create propria-gmbh/pelagos-ventures --public --source . --push`
2. Settings, Pages: branch `main`, folder `/ (root)`.
3. Check the URL, then use it in the "Website" step of the Payoneer form.
