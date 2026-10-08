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

We don't run a bug bounty: we don't pay for reports or send swag.

Please give us a reasonable time to fix the issue before disclosing it publicly.

## Scope

- The SDKs: `@nohead/sdk` (npm), `nohead` (PyPI) and the `nohead` gem.
- The Nohead CLI, `@nohead/cli`.
- The Nohead API (`api.nohead.io`), the web app (`app.nohead.io`), the image service (`images.nohead.io`) and `nohead.io`.

The docs site (`docs.nohead.io`) is hosted by Mintlify; report issues in the platform itself to them.

### Out of scope

We close these without a fix unless you show a concrete impact on our users or their data:

- Email DNS records (SPF, DKIM, DMARC).
- Missing security headers or cookie flags.
- Clickjacking on pages with no sensitive actions.
- Rate limits, or their absence.
- Self-XSS, and CSRF on sign-in or sign-out.
- Version numbers and software banners.
- Output from automated scanners without a working proof of concept.
- Services we use, such as Cloudflare, Mintlify or Stripe: report those to the vendor.

## Testing guidelines

- Test only against your own account, organizations and data. Never access, change or delete other people's data.
- No automated scanning, denial of service, load testing, spam, social engineering or physical attacks.
- If you come across other people's data by accident, stop, don't keep it, and tell us.

We won't take legal action against research done in good faith within these guidelines.
