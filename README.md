# Personal CV with AltaCV

Credit to author of the repo this is a fork of:
- [LianTze Lim](https://github.com/liantze) (liantze@gmail.com)

## Please note that...

- ...the CV uses placeholders for information I don't like to share on a public repository!
- ...it is made to be rendered in [Overleaf](https://www.overleaf.com/)

---

## Important info by the original author

### Requirements and Compilation

* AltaCV uses [`fontawesome5`](http://www.ctan.org/pkg/fontawesome5)
* The samples here use the [Lato](http://www.latofonts.com/lato-free-fonts/) and [Roboto Slab fonts](https://github.com/googlefonts/robotoslab).

### Configurable colours

Use `\colorlet` or `\definecolor` to change these; see examples
in preamble of `sample.tex`.
* `accent`
* `emphasis`
* `heading`
* `headingrule`
* `subheading`
* `body`
* `name`
* `tagline`

### Configurable fonts

Use `\renewcommand` to change these; see examples in preamble of
`sample.tex`.
* `\namefont`
* `\taglinefont`
* `\personalinfofont`
* `\cvsectionfont`
* `\cvsubsectionfont`

### Configurable icons

Use `\renewcommand` to change these; see examples in preamble of
`sample.tex`.
* `\cvItemMarker` (bullets for `itemize`)
* `\cvRatingMarker` (for `\cvskill`)
* `\cvDateMarker` (for date in `\cvevent`)
* `\cvLocationMarker` (for location in `\cvevent` and `\location`)

### Clickable Info fields

As of v1.3, the `withhyper` document class option will load the `hyperref` package, and make fields in the personal detail fields into clickable hyperlinks (where it makes sense anyway).

*BIG CAVEAT:* Remember that not all readers may want to click on hyperlinks in PDFs. You may therefore sometimes want to _remove_ `withhyper`, and spell out the field URL details a bit more completely, e.g. `\github{github.com/your-id}`.

# License

LaTeX Project Public License (LPPL) Version 1.3c.

See LICENSE.md for details.
