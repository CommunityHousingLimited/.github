# Brand components for the public organisation profile

**Draft — pending approval by CHL Communications and Marketing.** Communications and Marketing approve all applications of the CHL brand. Nothing in this directory is approved for publication until they have signed it off.

## What these files are

PNG components referenced by `profile/README.md`. Each file is rendered at exactly twice its display width so it stays sharp on high-density screens.

| File | What it is | Display size |
| --- | --- | --- |
| `banner-supergraphic.png` | Decorative band of the C, H and L letterforms in Vivid Blue on Light Blue, composed as a window strip (Brand Guidelines p27), not as the logo | 1200 × 240 |
| `tile-home.png` | Message tile, "A place where you belong" | 380 × 300 |
| `tile-affordable.png` | Message tile, "Affordable housing built with you in mind." | 380 × 300 |
| `tile-foundation.png` | Message tile, "Every life deserves a solid foundation" | 380 × 300 |
| `btn-website.png` | Link button, "Website" | 110 × 44 |
| `btn-careers.png` | Link button, "Careers" | 107 × 44 |
| `btn-contact.png` | Link button, "Contact" | 108 × 44 |
| `btn-security-policy.png` | Link button, "Security policy" | 160 × 44 |
| `btn-support.png` | Link button, "Support" | 109 × 44 |
| `btn-policy-library.png` | Link button, "Policy library" | 146 × 44 |

The tile wording is taken verbatim from the key brand messages in the Brand Guidelines. The buttons follow the button style used on chl.org.au. The banner letterforms are the unaltered vector paths from the official CHL logo, placed at one uniform scale.

GitHub wraps any image that is not already inside a link in a link to the image file itself. The banner and the three tiles are therefore clickable on the rendered profile and open the PNG. This is standard GitHub behaviour for README images and is not something the page controls; the buttons are unaffected because each one is already a link.

## Sources

- The official CHL logo vector (`CHL_LogoTag_Blue-RGB.svg`, as published on chl.org.au) for the letterforms.
- *Community Housing Ltd Brand Guidelines, July 2026 v.3* for colour, typography, message wording and the supergraphic treatment.
- Typography inside the images: Bauhaus Scal Display Medium (tile headlines) and Public Sans SemiBold (button labels).

## Palette

Only these values appear in the files, taken exactly from the Brand Guidelines colour page.

| Name | Hex | Used in |
| --- | --- | --- |
| Vivid Blue | `#593BFF` | Banner letterforms, tile-home and tile-foundation headlines, tile-affordable ground, all buttons |
| Light Blue | `#C8EFFD` | Banner ground, tile-home ground, tile-affordable headline |
| Cream | `#F6EFE5` | Tile-foundation ground |
| Purple Dark | `#9E2DD0` | Tile-home and tile-foundation key phrase |
| White | `#FFFFFF` | Tile-affordable key phrase, button labels |

Flat colour only. No gradients, shadows, strokes, rotation or distortion. No photographs and no people. Every text and background pairing is one the Brand Guidelines list as an approved combination and meets WCAG AA for normal text.

## Regenerating

These files are the output of a small render kit that is not kept in this repository. The kit holds one SVG source per asset, authored at twice the display size, and a `render.sh` script that runs `rsvg-convert` and ImageMagick in an `alpine:3.20` container with the brand fonts registered, renders every source at its authored width, strips metadata and recompresses the PNGs. To change a component, edit its SVG source in the kit, run the script and copy the resulting PNG here under the same name. Do not edit these PNGs directly.

The approved logo and wordmark images in the parent `assets/` directory are separate and are not produced by the kit.
