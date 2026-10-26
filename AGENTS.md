# career/website — suvinay.github.io

**Repo:** `suvinay/suvinay.github.io`

Suvinay's personal site. **Published, hand-written static HTML** — no Hugo, no build step, no
Jekyll (`.nojekyll` is deliberate). Served from GitHub Pages off `suvinay/suvinay.github.io`.

**Every change here is public the moment it's pushed.** That is the dominant constraint.

## Starting a session

| | |
|---|---|
| `index.html` | The front page. Also the canonical example of the markup conventions. |
| `publications/` · `pubs/` | Publications listing and the PDFs. Two directories — check which one a link points at. |
| `podcast/ep-1` … `ep-24` | One folder per episode. |
| `interests/` · `docs/` | Interests pages · hosted `cv.pdf`. |
| `styles.css` · `fontello/` · `favicons/` | Styling and icons. |

Not Hugo — `projects/work/mit/csail-website` **is** a Hugo site. Don't confuse them.

## Conventions that bite

- **Match the existing markup by hand.** No framework, no generator, no reformatting pass.
  Copy the structure of a sibling page rather than writing fresh HTML.
- **Never commit or push without being asked.** Push is publication here.
- **Check both `publications/` and `pubs/`** when adding a paper — the split is historical and
  links go to either.
- **`docs/cv.pdf` is a copy.** The source lives in `projects/work/career/resume/`. Update there first,
  then copy the built PDF over.
- The site asserts his title and affiliation in `<meta>` tags. Keep those accurate.

---

Workspace conventions — dated folders, `log/`→`memory/`, git, tooling — are inherited from
`myspace/.agents/CONVENTIONS.md`.
