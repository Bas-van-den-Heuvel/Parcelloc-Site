# parcelloc.io — landing page

Single-file static site for PARCELLOC (an innoXL venture). Everything — styles, scripts,
images — is inlined in `index.html`. No build step, no dependencies.

## Deploy
Hosted on Cloudflare (Workers & Pages), connected to this repository:
- push to `main` = production deploy to https://parcelloc.io
- any other branch = preview URL for review

## Editing rules
- Content changes are prepared in the Parcelloc Studio (Cowork) and reviewed before merge.
- Nothing goes live without Bas's explicit go (public-content rule).
- Source of truth for facts: the award application + CURRENT_PARCELLOC_status.md (in the venture repo, not here).

© Q10 Consulting b.v. — all rights reserved. This repository contains public marketing content only.
