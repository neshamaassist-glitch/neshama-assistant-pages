# Neshama Personal Assistant public information

Static homepage and privacy policy for a personal/household assistant's Google OAuth branding. This repository is intended to contain public information only, not the assistant's source code, private records, email contents, tokens, or configuration.

## Pages

- `index.html`: assistant identity, purpose, Google integration overview and support contact.
- `privacy.html`: data access, use, AI processing, storage/retention, revocation and support.
- `style.css`: local styling; no external font, analytics, advertising, JavaScript, form or Google login.
- `.nojekyll`: serve static files directly.

## Publishing

Use a new dedicated public repository named `neshama-assistant-pages` under the owner's chosen GitHub account. Do not modify an existing school or application repository. GitHub Free requires a public repository for Pages. Enable Pages from branch `main`, folder `/` using the free branch deployment path; do not enable paid products or add a custom domain without separate approval.

Upload only the explicit static page files and this README. Keep private deployment notes outside the repository. After publication verify both public page URLs, their mutual links, styling, no authentication requirement, and the actual public repository contents. Never claim Google accepts the Pages domain merely because GitHub serves it.

Google OAuth domain authorization/ownership verification and app publication are separate steps. Do not add someone else's domain or invent a verification result. A separate custom-domain/DNS authorization may still be needed if Google refuses the provided Pages address. Fresh OAuth consent and a real forced-refresh/account check remain necessary after any branding/publication repair; these pages alone do not restore revoked grants.
