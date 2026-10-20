# Seven C's Paint Services LLC — handoff at ~60%

**Live:** https://10elizabethbell.github.io/sevenCsPaintServices/ · **Repo:** https://github.com/10elizabethbell/sevenCsPaintServices · **Built:** 2026-10-20 from Muse brief 2026-10-20 (Ocean County group post) · **Call Sheet:** site set

## What's built
- One page, calm band style: paper header (their navy script logo left, `732-305-5003` top right) → photo hero → "We paint your home like it's our own" + four claims → "What we paint" service rows (navy) → Before and after (light) → How it works (deep navy, texture) → free-estimate form (paper) → close (navy, white logo, big number) → footer (email lives only here, plus Facebook).
- Palette: the logo's navy `#06204e` is ink and the deep band; mid navy `#183a72`; paper `#f4f6fb`; one warm accent, brass `#e8b04a` (fills only; `#7d5612` when it must be text on light).
- Hero: their own after-photo (den's blue panelled wall) blurred under a navy overlay. White text measures 9.6:1+ against the brightest hero pixel, brass 4.9:1+.
- H1 "Toms River homes, painted right." bounces in letter by letter; `.rise` fade-up below the first screen; both off under reduced motion and without JS.
- Proof: draggable before/after slider (hallway, mouse/touch/arrow keys, vertical scroll still works over it), the den pair side by side, then "Click to see more of our work." → their Facebook.
- Contact: the form composes a text to 732-305-5003 (chips Interior/Exterior/Trim/Wall patching, name required, town and details optional); a call fallback line appears if Messages doesn't open. Floating brass text circle shows after the hero and hides over the form. Tapping a service row ticks its chip.
- Images are separate files in `img/` (WebP, ~110 KB total) rather than base64 in the HTML; favicon and home-screen icon are the "C's" from their logo; `og.jpg` 1200×630 for Facebook previews.

## Assumptions I made
- **Brass accent** is mine: the logo is navy only. Chosen to sit with the nautical "seven seas" logo (brass fittings) and the warm wood floors in their photos.
- **"Trim and wainscoting" and "Wall patching"** as services are inferred from the photos (wainscoting painted, holes patched before paint). Their own words only say "Interior and Exterior".
- **Trust copy** ("the people who come out for your estimate are the people who paint. We cover your floors, patch the dings first, and leave every line clean.") is written for them from "small family owned and operated" and what the photos show (drop cloths, patches). Owner should approve.
- **"Booking interior jobs through the winter and exterior jobs for spring."** comes from Muse's seasonal note, not the owner.
- **"With our lead painter on the job"** is read from "Lead painter brings 29 years of experience to every job."
- **We/our** voice: they say "family owned and operated".
- **Texts:** unknown whether 732-305-5003 takes texts. The form and the circle hand off by text; the call link is the header number and the fallback line.

## Placeholders and gaps
- No owner/lead painter name, no reviews, hours, prices, insurance or licence: the page says nothing about them.
- Photos: only the one group post (two before/after pairs, Facebook-sized at ~356 px each). They're soft at phone 2×; originals would fix that.
- Registered name "Seven C's Paint Services LLC" is from the Facebook page, unconfirmed.

## Questions for the owner
1. Does 732-305-5003 take texts? (If not, the form should switch to call.)
2. The lead painter's first name, so the page can say who they'll deal with.
3. The original full-size photos, and more jobs (especially exteriors).
4. Which towns you cover around Toms River.
5. Insured? Any reviews or referral quotes we can use word for word?
6. OK with the services list and the trust paragraph as written?

## Ideas not built (yours to pick)
- Worlds from the trade, for an opt-in signature motion: (1) **a wet roller stroke** that paints the hero from tan to their slate blue as you drag (best: it's literally their before/after); (2) brush strokes revealing each section's band; (3) the logo's waves rolling along the hero's bottom edge; (4) painter's tape that peels off to reveal the heading; (5) a colour-chip fan for the services.
- A gallery page once they send more photos; exterior before/afters.
- Name the lead painter in the hero promise once known.
- Impeccable findings kept by choice: detector flags the diagonal band texture ("repeating-gradient stripes") and the eyebrow pills; both are house calm style.

## Not verified
- Real-device touch on the slider (tested with Playwright Chromium and WebKit, mouse drag and keyboard).
- Real SMS handoff on iOS/Android and inside Facebook's in-app browser (message body decodes correctly in tests).
- Frame rate on old phones (motion is CSS only, short).
