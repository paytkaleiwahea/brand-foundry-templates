# Brand Foundry Templates

A growing library of templates by Payton Kaleiwahea
([@paytkaleiwahea](https://x.com/paytkaleiwahea)) for
[Brand Foundry](https://github.com/bbm-media/brand-foundry), the local-first
template studio. Browse the list below, pick one, and copy it into your own studio.

## Templates

| Template | Type | Length | Sizes | Folder |
| --- | --- | --- | --- | --- |
| [Claude Engraving Ad](templates/video/ads/claude-engraving-ad.md) | Video ad | 14.5 s, 60 fps | 9:16, 4:5, 16:9 | `templates/video/ads/` |

Folders follow Brand Foundry's own layout, `templates/<media>/<category>/`, so a
category folder drops straight into a studio checkout.

## Use a template

You need a working Brand Foundry checkout (see its README). Templates here are
source files, so the studio's build fills in sizes and brand defaults.

**With your coding agent (recommended).** Point it at this repo and follow
Brand Foundry's
[IMPORTING-TEMPLATES.md](https://github.com/bbm-media/brand-foundry/blob/main/docs/IMPORTING-TEMPLATES.md):

> Import the claude-engraving-ad template from
> https://github.com/paytkaleiwahea/brand-foundry-templates into my Brand Foundry
> at [local path]. Follow IMPORTING-TEMPLATES.md. Keep its assets folder with it,
> build, and check the preview and export.

**By hand.**

1. Download or clone this repo somewhere outside your studio.
2. Copy the template's category folder, for example `templates/video/ads/`, into
   the same place in your studio. If that category already exists, rename the
   folder you copy (for example `ads-engraving/`) instead of merging over it.
3. In the studio, run `npm run build` (stop a running server first on Windows),
   then `npm start`. The template shows up under its media type and category.
4. Fill in the fields in the editor, or export through the local API as described
   in Brand Foundry's AGENT-WORKFLOW.md.

Each template has its own page (linked in the table) listing its editable fields,
sizes and any image credits.

## Credits

Brand Foundry was created by Payton Kaleiwahea and is published by
[Business Based Media](https://github.com/bbm-media). Third-party images used
by a template are listed in a `SOURCES.md` file inside its `assets/` folder.

Some templates are spec pieces built around other companies' brands. They are
unofficial and not affiliated with or endorsed by those companies; each
template's page says so where it applies.
