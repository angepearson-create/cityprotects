# cityprotects.com

Companion site to *Minneapolis: A City Protects Her Own*.
Hosted on GitHub Pages. Served files:

| File | What it is |
|---|---|
| `index.html` | Homepage — `cityprotects.com` |
| `resources/index.html` | **The companion page** — `cityprotects.com/resources` (the URL printed in Appendix B) |
| `rebel-loon-custom.svg` | The loon logo. One copy here at the root serves every page. **Add this file — see below.** |
| `404.html` | Shown for any bad URL; routes readers to /resources |
| `CNAME` | Tells GitHub Pages the custom domain. Don't delete or rename. |

## How to update the site (the whole routine)

1. Open the file on github.com and click the **pencil icon** (Edit).
2. Make the change (org link, description, adding an org — the HTML has
   plain-English maintenance comments at the top of `resources/index.html`).
3. **Update the "Last updated" date** in the hero of `resources/index.html`.
4. Click **Commit changes**. The live site rebuilds itself in ~1 minute.

Every edit is saved in the repository history (the "History" button on any
file), so any change can be reviewed or reverted.

## One thing to add before first deploy

Drop `rebel-loon-custom.svg` into the root of this repository (same level as
this README). Both pages look for it at `/rebel-loon-custom.svg`; until it's
there, the pages simply hide the mark and show the wordmark.
