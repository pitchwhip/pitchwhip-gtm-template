# PitchWhip Website Visitors: Google Tag Manager template

See which companies visit your website. This Community Template adds the PitchWhip Website visitors snippet through Google Tag Manager, with Google Consent Mode support.

## Use

1. Get a free site key at https://pitchwhip.com/website-visitors.
2. In Google Tag Manager: Templates → Search Gallery → "PitchWhip Website Visitors" (or import `template.tpl`).
3. New tag → PitchWhip Website Visitors → paste the site key → trigger on All Pages → Publish.

## Consent

- **Use Google Consent Mode** (default): consent is sent when `analytics_storage` is granted, including later in the visit.
- Visitors from the UK, EU/EEA, Switzerland and Canada are only counted once consent is sent.

## Privacy

Sends the page path, the referring host, the site key and the consent flag to px.pitchwhip.com. Optional: the company domain of a signed-in visitor's email (the part after the @). See https://pitchwhip.com/privacy.

## Licence

Apache 2.0 (required by the Community Template Gallery).
