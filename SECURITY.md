# Security policy

Thank you for helping keep Nohead and its users safe.

## Reporting a vulnerability

Please don't open a public issue. Report it privately instead:

- **On GitHub (preferred):** open the affected repository's **Security** tab and choose **Report a vulnerability**. Every public `nohead-io` repository accepts private reports.
- **By email:** hello@nohead.io, with "Security" in the subject.

Include what you found, where (repository, package version, or the API endpoint or page), and how to reproduce it. A proof of concept helps.

## What to expect

- We acknowledge your report within **3 business days**.
- We keep you updated while we investigate and fix it, and tell you when the fix is released.
- We credit you in the advisory, unless you'd rather not be named.

Please give us a reasonable time to fix the issue before disclosing it publicly.

## Scope

- The SDKs: `@nohead/sdk` (npm), `nohead` (PyPI) and the `nohead` gem.
- The Nohead CLI, `@nohead/cli`.
- The Nohead API (`api.nohead.io`), the web app (`app.nohead.io`), the image service (`images.nohead.io`) and `nohead.io`.

The docs site (`docs.nohead.io`) is hosted by Mintlify; report issues in the platform itself to them.

## Testing guidelines

- Test only against your own account, organizations and data. Never access, change or delete other people's data.
- No denial of service, load testing, spam or social engineering.
- If you come across other people's data by accident, stop, don't keep it, and tell us.

We won't take legal action against research done in good faith within these guidelines.
