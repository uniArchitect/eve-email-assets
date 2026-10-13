# Eve Hair newsletter template

`newsletter-template.html` is the blank version of the October 2026 newsletter (see `2026-10/newsletter-2026-10.html` for a finished example).

- Fixed parts: logo header, nav row, footer. Do not restyle them.
- Blocks are marked `<!-- BLOCK name -->` ... `<!-- END name -->`. Repeat or drop blocks as needed, then delete the comments.
- Fill every `{{PLACEHOLDER}}`. No `{{` may remain in a finished email.
- Images go in a dated folder (`YYYY-MM/`), named `eve-<mon><yy>-<slug>.jpg`, about 640px wide and under 250 KB. Link them as `https://raw.githubusercontent.com/uniArchitect/eve-email-assets/main/YYYY-MM/<file>`.
- Never rename, move or delete files that have been sent. Old emails link to them.
- This repo is public. Keep pricing-sensitive drafts out of it unless the email has already gone out.
