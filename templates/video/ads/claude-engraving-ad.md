# Claude Engraving Ad

`video/ads/claude-engraving-ad` · 14.5 s · 60 fps · 9:16, 4:5 and 16:9

A fast brand spot in bold light mode. Public-domain engravings and museum
photographs cut every 0.16 to 1.4 seconds, with a coral spark and brush marks
painted over them:

1. The spark and wordmark open, fold into a dot, and become a Bentley snowflake
   inside an inked ring that pulls back into a grid of flakes.
2. "ask?" morphs into "task" beside Kepler and Leonardo engravings.
3. Dürer's rhinoceros gets a painted loop round its horn and a push-in through it.
4. A Muybridge zoetrope spins around a galloping horse.
5. A black flash of the Vesalius skeleton, measured with a ruler.
6. Two marble heads on ruled lines lead into "draft" morphing into "craft".
7. Pacioli's letter C: its construction rays become the spark, which turns in 3D.
8. Two Rodin hands hold the spark while an orbit draws around it.
9. A montage flashes inside a large open circle.
10. "think" becomes "ink", then "Keep thinking.", whose full stop becomes the spark
    for the closing lockup.

## Editable fields

| Field | Default | Notes |
| --- | --- | --- |
| Morph one | `ask\|task` | Two words separated by `\|`. Shared letters slide into place. |
| Morph two | `draft\|craft` | The first new letter is handwritten in above, then drops in. |
| Morph three | `think\|ink` | The second word slides into the tagline's second line where they share letters. |
| Tagline | `Keep\|thinking.` | Two lines. A closing `.`, `!` or `?` is painted in the accent and becomes the spark. |
| Wordmark | `Claude` | Closing lockup beside the spark. |
| Spark and paint | `#D97757` | Accent colour for the spark, brush marks and dots. |
| Ink | `#141413` | Type and rules. |
| Paper | `#FFFFFF` | Background. |
| Serif font | Source Serif 4 | Any font the editor offers. |

Words are measured after web fonts load and refitted to the frame, so longer
words shrink to fit instead of overflowing.

## Sizes

The design sits on a 1080×1920 stage whose central 1080×1350 band holds
everything that matters. The 9:16 render shows the whole stage. 4:5 crops only
empty margin. 16:9 scales the band to the frame height and full-bleed elements
extend to the sides.

## Requirements

- Brand Foundry with HyperFrames installed for video export.
- Network access at render time for GSAP (jsDelivr) and Source Serif 4 (Google
  Fonts), like the other Brand Foundry motion templates.

## Images

All 36 images in `assets/engraving/` are processed copies of public-domain or
CC0 files from Wikimedia Commons (Dürer, Muybridge, Bentley, Vesalius, Pacioli,
Leonardo, Kepler, Besler, and photographs from The Met). See
[assets/engraving/SOURCES.md](assets/engraving/SOURCES.md) for every source and
licence.

## Trademark notice

This is an unofficial spec piece. "Claude" and the spark mark are trademarks of
Anthropic. This template is not affiliated with, sponsored by or endorsed by
Anthropic. The spark is drawn in code as an approximation; no Anthropic logo
files are included. Change the wordmark and colours before using the template
for anything other than a personal or spec project.

## Credit

Structure inspired by [@LexnLin's engraving-style Claude ad](https://prompt-motion.com/lexnlin-038035).
The design, motion and code here are rebuilt from scratch, and no frames or
assets from that video are used.
