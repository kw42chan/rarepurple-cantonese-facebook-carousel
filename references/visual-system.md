# RarePurple visual system

## Direction

Premium, cinematic, editorial 3D advertising for social media. The visual should feel like a polished AI product campaign: dramatic but clean, expressive but not childish. When a user supplies a visual reference, match its lettering and composition as closely as its palette; a purple background and generic bold font alone are not a match.

## Palette

- 70% deep royal purple / dark violet background.
- 20% warm white or cream information surfaces and type.
- 8% metallic warm gold accents.
- 2% functional accents such as amber, green, or red status markers.

Use subtle mottled texture, paper grain, restrained gold dust or brush texture, soft vignette, and cinematic rim lighting. Avoid flat pale purple, pastel palettes, neon cyberpunk, or generic template styling.

## Typography and layout

### Display-lettering specification

- The reference uses custom-looking, extra-black Traditional Chinese display lettering, not ordinary clean sans-serif text. Do not claim an exact font family from the raster reference. Start with a heavy Traditional Chinese / Hong Kong Gothic face (for example Noto Sans HK Black or Source Han Sans HC Heavy, if available), then shape the headline to match the reference: broad block strokes, angular or brush-cut terminals, slightly irregular edges, and open, legible counters. A font substitute without this custom treatment is not sufficient.
- For Latin words and numerals in the headline, use an equally heavy condensed sans-serif treatment (Anton/Impact-like). Match the Chinese headline's visual weight and baseline rather than allowing English to look thin or detached.
- Set the main hook as the dominant graphic element. On a portrait 4:5 page, it may fill roughly the upper quarter to third and nearly the full safe width. Prefer two tightly stacked semantic lines when the copy allows: warm-white/cream first line and metallic-gold second line. Preserve the supplied words, punctuation, English casing, and reading order; do not force an unnatural line break just to imitate the example.
- Make headline strokes look dimensional: subtle warm-white paper grain on the light line; restrained warm-gold metallic gradient and fine grain on the gold line; a short, dark-purple offset extrusion or hard shadow for separation. Avoid flat yellow, chrome shine, thick black outlines, soft blurry shadows, or effects that close up Chinese glyphs.
- Tighten line spacing and tracking enough for a compact poster-like headline, while keeping every character and punctuation mark distinct. Keep the baseline stable and the title clearly separated from the character's head and scene objects. Do not stretch glyphs disproportionately or overlap strokes.
- Secondary copy sits directly below the hook as a bold white Traditional Chinese block, clearly smaller but still readable on a phone. Use short left-aligned lines, strong contrast, and deliberate breaks at natural Cantonese phrases. Avoid thin captions, overly small body text, and large empty gaps between the hook and explanation.
- A small centered dark-purple badge with a fine gold border may sit above the title when the page calls for AI 拍拍機 branding. Use a restrained gold brush-stroke underline or glint to support the headline; these details must not compete with the wording. Keep a bottom dark-purple/gold CTA strip only where the page brief calls for it.

### Composition and consistency

- Use about 5% safe margins, one dominant idea per page, and a strong hierarchy: badge (if applicable) → oversized hook → bold supporting line → cartoon workplace scene → CTA (if applicable).
- Keep the headline treatment consistent across the carousel, but vary the line break and type size to fit each page's exact copy. Never shrink the hook into an ordinary text box or let the scene swallow the text.
- Use badges, cards, arrows, checklists, comparison panels, and CTA strips only as needed. The expressive cartoon workplace character and props support the copy; they must not cover, distort, or replace it.

## Generation guardrails

Keep the same palette, lighting logic, rendering quality, and headline treatment on every page. Treat a supplied image as a visual reference for letterform, size, texture, hierarchy, and spacing—not as evidence of a specific font file. If an image model cannot reliably typeset exact Traditional Chinese, generate the scene without text and add the supplied copy in a separate layout pass. Verify each finished page at both full size and phone/contact-sheet size against the reference: Chinese glyphs, punctuation, English casing, headline scale, white/gold material, line spacing, safe margins, and absence of cropping or overlaps. Do not add logos, claims, interface elements, or decorative objects not requested by the page prompt.
