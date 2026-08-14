# Starvin' Artist Recording Efforts — Demo Site

Demo brochure site for **Ivie Lamont** (Starvin' Artist Recording Efforts, Atlanta GA), built by [60MinuteSites](https://60minutesites.com).

## Status

- **Demo** — verbal commit on 8/14/2026 call. Client will want `starvinartistrecordingefforts.com`.
- Forms submit to 60MinuteSites Formspree (`xojeqvng`) for testing, with `_subject` prefixed `Starvin' Artist DEMO —` and auto-redirect to `thank-you.html`.
- Payment links go to `60minutesites.com/checkout-information.html?plan=monthly|annual` (Formspree `mvzalyrw` → Stripe).

## Pages

- `index.html` — brochure (hero, about, services, album teaser + notify form, socials, booking form)
- `pricing.html` — custom pricing for Ivie ($150 + $50/mo, or $500/yr) with checkout links
- `thank-you.html` — form redirect target

## To make it live for real

1. Client pays via pricing page.
2. Buy + point `starvinartistrecordingefforts.com`.
3. Swap Formspree IDs to client-owned forms (or keep routing to 60MS inbox), remove demo bars/disclaimers, remove `noindex`.
4. Drop in streaming links (Spotify / Apple Music / SoundCloud placeholders in the Listen section).
