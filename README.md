# QA Screenshots

Evidence repository for Shiftopus QA agent runs. Each screenshot is referenced from the corresponding Zoho Projects issue (https://projects.zoho.eu/portal/shiftopusdotcom).

Public so Zoho can embed images via raw.githubusercontent.com URLs without authentication.

## Layout

```
<product-slug>/
  <run-timestamp>-<suite>/
    <NNN>-<K-or-tc-key>-<short-description>.png
```

## Why public?

Screenshots are of demo product UI that's already customer-facing. No secrets, no PII. The trade-off was: be able to embed in Zoho descriptions (which sanitize away base64 data URIs but allow external `<img src>`), vs keep private (then Zoho can't render the image at all).
