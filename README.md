# Casino Mayor Website

Static bilingual landing page for Casino Mayor in Candelario, focused on dance, dining, stays, and heritage-led events.

Casino Mayor is still under renovation. The website is partly intended to present the future venue concept and support a possible business plan while the project develops.

## Terminology
- Default naming: use the full name Casino Mayor.
- Use the abbreviation CM only when explicitly requested.

## Production URL
- http://casinomayor.es

## Contact
- Mobile WhatsApp: +34 659 376 099
- Email: casinomayor.es@gmail.com
- Future operational email: reservations@casinomayor.es

## Channels
- YouTube: `@CasinoMayor`
- Patreon: https://patreon.com/Ruben_CasinoMayorRestoration
- First public video still pending; add the live channel link to the site once the first update is published.

## Project Status
- Current phase: renovation and concept development
- Immediate restoration priority: secure and repair the roof
- Next priority after the roof: restore doors and windows to weatherproof the building, as many are missing or damaged
- Website role: public-facing concept presentation and business-plan support
- Opening timeline is communicated in the top hero pill on the page: "Grand Opening · Planned End 2027"

## Story and Community Direction
- Core mission: preserve heritage, restore the 1888 building, and bring it back to life for dance, culture, and shared evenings.
- Community goal: make Casino Mayor feel open to all ages, including people who visited decades ago and now want to return with younger generations.
- Voice guideline: keep restoration copy human and emotional, not only technical.
- Minimum narrative structure on restoration updates: short intro story + "Current state" + "Next steps".
- Human trust line: include a first-person note such as "I am restoring this building step by step..." on key pages.

## Attention to Trust to Revenue Path
- YouTube role: attract attention with short update videos and visible progress moments.
- Website role: build trust through clear updates, real photos, and transparent priorities.
- Public support channel: Patreon is live for followers who want to support the restoration journey.

## Community Memories Program
- Add a recurring call for community memories: invite stories and historic photos from people who knew Casino Mayor before closure.
- Positioning line to preserve: the building has been closed for about 50 years and is now reopening as a shared cultural place for old and new generations.
- Historical framing to use in copy: in Spanish tradition, a "casino" is a social-cultural meeting house, not only a gambling concept.

## Next Channel Rollout
- Phase 1 (now): publish short restoration updates on YouTube and embed the channel link on the website.
- Phase 2 (now live): Patreon support link is available for followers who want to back the restoration journey.

## Bank-Readiness Messaging
- Keep language credible and concrete: heritage restoration, phased execution, and clear priorities (roof -> doors/windows -> interiors).
- Show continuity: regular public updates, milestone timeline, and documented community engagement.
- Keep investment narrative practical: restoration creates a viable cultural venue for events, hospitality, and intergenerational community use.

## Repository
- https://github.com/RubenDuijn/CasinoMayor

## Structure
- `index.html` - Main landing page
- `images/` - Project images and visual assets

## Image Asset Note
- If a new image is added to `images/` and referenced in the HTML, it must also be added and committed to git or it will not appear on the live site.
- Current example: `images/Ruben at Cruz del Herrerito.JPG` is used for the host-restorer card on the restoration page.

## Site Notes
- Single-file static website with inline EN/ES language switching.
- Production URL: http://casinomayor.es

## Local Preview
From this folder, run:

```bash
python3 -m http.server 8000
```

Then open:
- `http://127.0.0.1:8000/index.html`
