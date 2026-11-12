Public support and privacy documents for PinGoTrek and Curvy Cruiser.

- `pingotrek/`: PinGoTrek support and privacy notice.
- `curvycruiser/`: Curvy Cruiser support and privacy notice.
- `index.html`: app directory.

The site uses static HTML on GitHub Pages, with `.nojekyll` at the repository
root. Curvy Cruiser reuses `pingotrek/styles.css` for the existing site layout;
keep that shared stylesheet available when publishing either app's pages.
There is no package manifest, build step, or repository-defined test suite.

Verified Pages configuration: `main` branch, repository root, no custom domain.
Curvy Cruiser public URLs:

- Support: `https://verykross.github.io/PublicDocs/curvycruiser/`
- Privacy: `https://verykross.github.io/PublicDocs/curvycruiser/privacy.html`

## Curvy Cruiser content review

The owner accepted the initial support and privacy wording and authorized
publication on November 12, 2026 (commit `199afbe`). Revise these pages as
features change.

The owner authorized publication of the QR privacy update and matching support
guidance on November 12, 2026. They describe the Cloudflare sharing service,
including immediate upload with no second confirmation when choosing Show QR
code, no early revocation (including after canceling), 24-hour download access,
possibly delayed live-file deletion, longer provider recovery/backup retention,
and access for anyone with the code or link. They also distinguish direct file
sharing from QR uploads and disclose readable uploads and provider request
metadata. Review these disclosures whenever the sharing behavior changes.

The pages direct invited testers to their beta organizer for support and privacy
questions. PinGoTrek's public mailbox has not been confirmed for Curvy Cruiser,
so it is not reused. A dedicated public contact and legal operator identification
remain follow-up items; no contact or operator name has been invented.

Review the sharing wording against the build being released. Outlook delivery
and receiver import were validated on real devices; Apple Mail currently sends
only the body, not the ride attachment. Other sharing destinations are not
described as validated. Keep the limitation visible unless new release evidence
supports changing it.
