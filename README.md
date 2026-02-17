
# Analytics Demo Site (GitHub Pages)

A minimal static site to practice GA4 or GTM tagging.

## Quick start
1. Replace **G-XXXXXXXXXX** in `index.html` with your GA4 Measurement ID.
2. Commit and push to `main`.
3. Enable **GitHub Pages**: Settings → Pages → Source: *Deploy from a branch* → Branch `main` / `/root`.
4. Open `https://<your-username>.github.io/demo-analytics/` and test.

### Events included
- `cta_click` when you press the CTA button
- `click_outbound` when you click the external link
- `lead_submit` when you submit the form (no PII sent)

### Consent
A minimal banner toggles GA4 analytics storage (for learning Consent Mode behavior). Keep `anonymize_ip: true` and avoid sending PII.
