---
name: rarepurple-cantonese-facebook-carousel
description: Generate 6–7 page Facebook or Instagram carousels for Hong Kong white-collar audiences in conversational Traditional Chinese Cantonese, using the RarePurple deep-purple and metallic-gold visual system, a recurring premium 3D East Asian female office-worker character, page-by-page image prompts, and a Facebook-optimized caption for AI 拍拍機.
---

# RarePurple Cantonese Facebook Carousel

Use this skill when the user asks for a RarePurple / AI 拍拍機 carousel, a Cantonese office-pain-point carousel, or a Facebook/Instagram carousel based on a use-case library.

## Audience and voice

- Hong Kong white-collar workers, roughly 25–45, who work in bilingual office environments.
- Write in Traditional Chinese conversational Cantonese. Natural English office terms such as PDF, Excel, meeting, deadline, summary, stakeholder, or send are allowed.
- Sound relatable, slightly self-deprecating, direct, and useful. Avoid formal Mainland-style written Chinese, generic motivational copy, and unsupported claims.

## Workflow

1. Select one source use case and preserve its scenario, benefits, prompt, and product card name.
2. Build a coherent 6–7 page story: cover hook, pain point, consequence, AI solution, before/after, emotional payoff, and CTA. A 6-page version may merge the consequence and pain-point pages.
3. Read the relevant references before drafting: [visual-system.md](references/visual-system.md), [character-system.md](references/character-system.md), [carousel-structure.md](references/carousel-structure.md), and [facebook-caption.md](references/facebook-caption.md).
4. Produce one page-by-page image prompt for every page. Each prompt must state purpose, exact artwork text, character state, environment, objects, composition, typography, and visual system. Keep artwork text short and mobile-readable; do not rely on image generation to render long paragraphs accurately.
5. Produce the Facebook caption, hashtags, and a low-friction comment-driving question.
6. Preserve the AI 拍拍機 CTA language: 「拍到邊張卡，就跟住做」, 「5–10 分鐘，跟住做就會」, and 「Link in bio 睇 AI 拍拍機」. Use the most relevant lines together on the CTA page and in the caption.
7. If image generation is available, generate pages consistently from the prompts and verify character continuity, text hierarchy, purple/gold palette, and the absence of unrequested elements.

## Output

Return, in order: selected use case, 6–7 page storyline, page prompts, Facebook caption, hashtags, and comment question. For source-driven work, state which source fields were retained. Do not silently change the use case.

## Prompt routing

Use the page templates in [prompts/](prompts/) as starting points. Read only the page templates needed for the chosen page count, then adapt their placeholders to the source use case. The worked #11 example is in [examples/use-case-11-long-document-summary.md](examples/use-case-11-long-document-summary.md).
