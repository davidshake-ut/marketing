# FSG Website — UI Kit

A pixel-fidelity recreation of the **fusionsg.com** marketing site, tuned per the brief:
- **Engagement** — more rhythm to the page, fewer dense walls of text
- **Simplicity** — pares duplicated sections, lets the SCALE framework breathe
- **Consistency** — every component lives in `colors_and_type.css` tokens, no inline gradients-of-fortune

Open `index.html` for the live preview. Components live in `components.jsx`.

## Components recreated
- `TopNav` — sticky, backdrop-blur, brand mark + 5 links + primary CTA
- `Hero` — eyebrow chip, H1 with brand-blue emphasis word, problem statement w/ amber left-bar, subhead, three bulleted promises, dual CTA, fit-card sidebar
- `TrustBar` — vendor logo strip (chips)
- `StatStrip` — dark band with 4 accent-numeral stats
- `WinsGrid` — three result cards
- `ServicesGrid` — five service tiles
- `MidCta` — secondary push between sections
- `ScaleSection` — dark section with five SCALE letter-block cards
- `FitPanels` — green/red twin panels
- `FaqSection` — sidebar copy + accordion
- `ContactSection` — info panel + mailto form
- `Footer`

## What was simplified vs the original
- Removed em-dashes throughout (per brand voice rule)
- Single CTA per section (was sometimes two)
- Compressed the hero — three bullets instead of feeling like a kitchen sink
- Stat strip moved above wins so the proof loads earlier
- Service icons swapped to Lucide for visual consistency (flagged substitution)
