# Brand components for the public organisation profile

**Draft — pending approval by CHL Communications and Marketing.** Communications and Marketing approve all applications of the CHL brand. Nothing in this directory is approved for publication until they have signed it off.

## What these files are

PNG components referenced by `profile/README.md`. Each file is rendered at exactly twice its display width so it stays sharp on high-density screens.

| File | What it is | Display size |
| --- | --- | --- |
| `banner-supergraphic.png` | Hero strip in the supergraphic treatment (Brand Guidelines p27, p31): the C, H and L letterforms as windows onto photographs of CHL homes, on a Light Blue band | 1200 × 240 |
| `statement-vision.png` | Statement band, "A world without housing poverty", Vivid Blue on Light Blue | 1200 × 200 |
| `tile-home.png` | Message tile, "A place where you belong" | 380 × 300 |
| `tile-affordable.png` | Message tile, "Affordable housing built with you in mind." | 380 × 300 |
| `tile-foundation.png` | Message tile, "Every life deserves a solid foundation" | 380 × 300 |
| `window-c.png` | Photo window: the C letterform framing a CHL customer outside her home | 380 × 300 |
| `window-h.png` | Photo window: the H letterform framing a couple with their dog at home | 380 × 300 |
| `window-l.png` | Photo window: the L letterform framing people on a housing construction site | 380 × 300 |
| `statement-purpose.png` | Statement band, the purpose statement, Vivid Blue with the key word in Purple Dark on Cream | 1200 × 200 |
| `belong-slippers.png`, `belong-key.png`, `belong-neighbours.png` | "You belong…" campaign tiles, one line each from the key brand messages | 270 × 220 |
| `cta-website.png` | Call-to-action band, "Find out more about CHL — chl.org.au", Light Blue and White on Vivid Blue with the C letterform accent; the page links it to chl.org.au | 1200 × 160 |

The tile wording is taken verbatim from the key brand messages in the Brand Guidelines. The banner and window letterforms are the unaltered vector paths from the official CHL logo, placed at one uniform scale.

GitHub wraps any image that is not already inside a link in a link to the image file itself. The banner and the three tiles are therefore clickable on the rendered profile and open the PNG. This is standard GitHub behaviour for README images and is not something the page controls.

## Sources

- The official CHL logo vector (`CHL_LogoTag_Blue-RGB.svg`, as published on chl.org.au) for the letterforms.
- *Community Housing Ltd Brand Guidelines, July 2026 v.3* for colour, typography, message wording and the supergraphic treatment.
- Typography inside the images: Bauhaus Scal Display Medium (statement bands, tile headlines and the call to action) and Public Sans SemiBold (the web address on the call to action).

## Palette

Only these values appear in the files, taken exactly from the Brand Guidelines colour page.

| Name | Hex | Used in |
| --- | --- | --- |
| Vivid Blue | `#593BFF` | Statement band text, purpose band text, call-to-action ground, belong-slippers ground, tile-home and tile-foundation headlines, tile-affordable ground |
| Light Blue | `#C8EFFD` | Banner ground, statement ground, tile-home and belong-key grounds, tile-affordable and belong-slippers headlines, call-to-action headline and C accent |
| Cream | `#F6EFE5` | Tile-foundation, purpose band and belong-neighbours grounds |
| Purple Dark | `#9E2DD0` | Tile-home and tile-foundation key phrase, purpose band key word, "You belong" labels on Light Blue and Cream |
| White | `#FFFFFF` | Tile-affordable key phrase, "You belong" label on Vivid Blue, call-to-action web address |

Flat colour only. No gradients, shadows, strokes, rotation or distortion. Every text and background pairing is one the Brand Guidelines list as an approved combination and meets WCAG AA for normal text.

## Photography

The hero strip and the three photo windows use the supergraphic treatment from the Brand Guidelines: the unaltered C, H and L paths from the official logo vector act as windows onto photography of CHL customers, communities and homes being built. The photographs are CHL's own images as published on the chl.org.au home page, embedded uncropped apart from the framing each letter gives them; no text is placed over any image, as the guidelines require. Communications and Marketing hold the media consent records for these photographs. Confirm that each consent covers use on GitHub before sign-off, and replace any image that it does not.

## Regenerating

These files are the output of a small render kit that is not kept in this repository. The kit holds one SVG source per asset, authored at twice the display size, and a `render.sh` script that runs `rsvg-convert` and ImageMagick in an `alpine:3.20` container with the brand fonts registered, renders every source at its authored width, strips metadata and recompresses the PNGs. To change a component, edit its SVG source in the kit, run the script and copy the resulting PNG here under the same name. Do not edit these PNGs directly.

The approved logo and wordmark images in the parent `assets/` directory are separate and are not produced by the kit.
