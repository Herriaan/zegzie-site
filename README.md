# zegzie-site

Static support page and privacy policy for the iPad app ZegZie, served by GitHub Pages on
`https://zegzie.nl/` (custom domain via `CNAME`; DNS in Cloudflare, records via `cf_dns.py`).

- `index.html`: support page (FAQ and contact).
- `privacy/index.html`: privacy policy. The app links here (`PrivacyText.policyURL` in
  `KatamaNL/spraak-naar-tekst-opa`) and App Store Connect uses it as the Privacy URL.
- Source texts live in `docs/app-store/` of the app repo; keep both in sync and update the
  "Laatst bijgewerkt" date on every change of the privacy policy.

No build step, no external fonts, scripts or trackers.
