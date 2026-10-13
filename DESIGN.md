# Rutgers Formula Racing redesign

Astro with Tailwind CSS 4 via the official Vite plugin. Lucide supplies interface icons.

## Visual direction

Editorial hierarchy and clear, accessible navigation inspired by National Design
Studio (https://ndstudio.gov/) and Harvard (https://www.harvard.edu/).
The RFR identity combines large serif typography, technical labels,
full-width racing photography, and ruled, unframed sections.

Brand colors: Oxblood `#7A0F1C`, Obsidian `#0B0B0B`, Parchment `#EDE7E1`.
Fonts: Canela, Neue Haas Grotesk, Aptos Mono, with locally hosted and system
fallbacks. See `public/fonts/README.md` for licensed webfont integration.

## Content and media

Background, statistics, contact details, electric competition debut, and
supporters are sourced from https://www.rutgersformularacing.com/.
Team discipline descriptions are new editorial copy. Photographs are archival
images from RFR's website, not claims about the latest car or current season.

Public image source identifiers at https://static.wixstatic.com/media/:

- Hero: `26fdda_38f599b85bb94636b64ce6046b9b7124~mv2.jpg`
- Circuit: `860904_0e88d1df47484471aecab9f678ced2b8~mv2.jpg`
- Driver: `860904_f03b17ab95c7427eb3ad879cae75066bf000.jpg`

## Interactions

Responsive navigation with Escape support, keyboard-accessible gallery tabs,
native department and FAQ disclosures, and recruitment and sponsor email links.
Recruitment opens an email draft. There is no backend form service.

## Commands

```sh
bun run build
bunx astro dev --background
bunx astro dev status
bunx astro dev logs
bunx astro dev stop
```
