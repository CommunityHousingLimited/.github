# Brand components for the public organisation profile

**Draft — pending approval by CHL Communications and Marketing.** Communications and Marketing approve all applications of the CHL brand. Nothing in this directory is approved for publication until they have signed it off.

## What these files are

The profile is a splash page built from the sections of the chl.org.au home page as it stood on 9 September 2026 — the same order, grounds, typography, copy and photographs — so that the GitHub profile reads as a sibling of the website. Each section is one image, rendered at exactly twice its display width, and each links to https://chl.org.au/.

| File | Section on chl.org.au | Display size |
| --- | --- | --- |
| `hero.jpg` | The home page hero photograph (regional housing courtyard), full bleed, without the site's text overlay | 1200 × 560 |
| `intro.png` | "A world without housing poverty": small-caps eyebrow over the site's introductory copy in Public Sans Light, Vivid Blue on white | 1200 × 410 |
| `stats.png` | The four counters with their rules: 20,000+ customers living in our homes, 12,000+ homes nationally, 420+ passionate people, $7B housing portfolio | 1200 × 200 |
| `reach.png` | "National reach, local connections": heading, body copy and the "Our partnerships" button | 1200 × 380 |
| `foundation.jpg` | "Every life deserves a solid foundation.": Purple Dark panel with white copy and a white button beside the customer portrait | 1200 × 560 |
| `homes.jpg` | "Featured homes" on Cream: heading, rule, "What is community housing?", the "Our homes" button and three home columns with captions, copy and photographs | 1200 × 1040 |

Copy, counter values and home captions are verbatim from the home page. The buttons are drawn as they appear on the site (Vivid Blue with white label, or white with Vivid Blue label on the Purple Dark panel, 5 px radius) and are part of the image; the whole section is the link. No text is placed over any photograph, as the Brand Guidelines require; the site's hero text overlay is therefore omitted.

Sections that carry photographs are JPEG (quality 90, 4:2:0) to keep the page light; text-only sections are PNG.

## Sources

- The chl.org.au home page, captured on 9 September 2026, for section order, layout, copy, counters, captions and photographs.
- *Community Housing Ltd Brand Guidelines, July 2026 v.3* for colour, typography and the photography rules.
- Typography inside the images: Bauhaus Scal Display Medium (eyebrows, headings, counters, home captions), Public Sans Light (large introductory and panel copy), Public Sans Regular (body copy), Public Sans Medium (buttons).

## Photography

The photographs are CHL's own images as published on the chl.org.au home page: the regional housing courtyard, the customer portrait, and the Ground Lease Model 2 artist impression, Ironbark Place and ROSAS home images. Communications and Marketing hold the media consent records; confirm that the customer portrait's consent covers use on GitHub before sign-off, and replace it if it does not.

## Palette

Only these values appear in the files, taken exactly from the Brand Guidelines colour page (the site's own theme uses the same values).

| Name | Hex | Used in |
| --- | --- | --- |
| Vivid Blue | `#593BFF` | Eyebrows, headings, counters, rules, home captions, buttons, button label on the Purple Dark panel |
| Purple Dark | `#9E2DD0` | Foundation panel ground |
| Cream | `#F6EFE5` | Featured homes ground |
| White | `#FFFFFF` | Intro, stats and reach grounds; panel copy and button; button labels |
| Near black | `#111111` | Body copy and counter labels, as on the site |

Flat colour only. No gradients, shadows, strokes, rotation or distortion. Text and ground pairings match the site: Vivid Blue on white 6.0:1, near black on white and Cream, white on Purple Dark 5.6:1 — all meet WCAG AA for normal text.

## Regenerating

These files are the output of a small render kit that is not kept in this repository. The kit holds one SVG source per section, authored at twice the display size from the copy and layout above, and renders them with `rsvg-convert` and ImageMagick in an `alpine:3.20` container with the brand fonts registered. To change a section, edit its source in the kit, run the render and copy the result here under the same name. Do not edit these images directly.

The approved logo and wordmark images in the parent `assets/` directory are separate and are not produced by the kit.
