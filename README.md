# karpathy.ai Redesign Concept

> **Unofficial design concept.** Made as a thank-you to Andrej Karpathy for his free teaching. It is not affiliated with or endorsed by Andrej Karpathy.

## This is a design, not an implementation

This repo shares a **visual design proposal** for [karpathy.ai](https://karpathy.ai). It is not production code.

To make the design easy to preview, everything (HTML, CSS, JavaScript and the photo) is packed into a single `index.html` file. That's handy for a demo, but it isn't how a real website should be built. A proper implementation would:

- Split the code into clean, separate files (pages, styles, scripts, assets)
- Use whatever stack and constraints Andrej prefers (for example, plain static HTML and CSS with no frameworks, like the current site)
- Be optimized for performance, accessibility and SEO
- Be reviewed and approved by him before going anywhere near his real website

Think of this as the architect's drawing, not the finished house.

## Screenshots

### Home (light mode)
![Home, light mode](1-home-light.png)

### Home (dark mode)
![Home, dark mode](2-home-dark.png)

### Zero to Hero course page
![Zero to Hero course page](3-zero-to-hero.png)

### Talks page
![Talks page](4-talks.png)

## How to view the design

1. Download `index.html` (click the file, then the download button).
2. Open it in any modern browser (Chrome, Firefox, Edge or Safari).
3. Click through the tabs: Home, Teaching, Talks, Writing, Projects, Publications and About.

No installation, server or internet connection is needed (except for fonts and video thumbnails).

## What the design proposes

| Area | Current site | Proposed design |
|---|---|---|
| Navigation | One long scrolling page | A top menu with separate sections |
| Learning path | Courses mentioned inside the timeline | A clear "Start learning" button and a dedicated Teaching section |
| Zero to Hero | A simple list page | A course page with lecture numbers, durations and summaries |
| Talks | A list of thumbnails | Video cards with filters (Podcast, Keynote, Talk, Interview) |
| Career | Long paragraphs | Scannable cards and a visual timeline |
| Publications | A plain list | A clean layout with venue, year and highlighted authorship |
| Theme | Light only | Light and dark mode |
| Mobile | Basic responsive | A dedicated mobile layout with a menu button |

## Design choices

- **Typography:** Inter for clean, readable text, with a touch of Lora italic for the tagline
- **Colors:** a warm off-white background, near-black text and one orange accent color
- **Layout:** generous spacing, rounded cards and soft shadows for a modern, professional feel
- **Content:** unchanged. Every word, link and image comes from the current karpathy.ai

## Credits

- All content, links and the portrait photo belong to Andrej Karpathy and are taken from [karpathy.ai](https://karpathy.ai).
- Design concept by **Michel Ndjock**, a software engineer and tech mentor from Cameroon, currently learning through [Neural Networks: Zero to Hero](https://karpathy.ai/zero-to-hero.html).

If Andrej would like any changes, or would prefer this repo to be taken down, I'll do it right away.
