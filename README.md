# findley

Family knowledge base for **Findley Elementary School** (Beaverton School District, Portland OR), school year 2026-27.

**Live page:** https://reubenbroadfoot.github.io/findley-0c4984c218/

The repository name is deliberately unguessable, and the HTML pages carry `noindex` so they stay out of search results. The repo is still public, though — treat the URL as unlisted, not private.

## What's here

| File | What it is |
|---|---|
| `index.html` | The family hub. Ten tabs: an action checklist, confirmed dates, staff and PTO contacts, notes by grade, clubs, volunteering, costs, questions to ask, and links. Single self-contained file — no build step, no dependencies. |
| `docs/website-update-list.pdf` | Content requiring update across the school and PTO websites, sorted into what is incorrect, what is broken, and what is out of date. Every page path in it is a clickable link. Sent to the PTO president. |
| `docs/website-update-list.html` | Source for the PDF above, so it can be edited and re-exported. |
| `docs/reference.md` | Dates, contacts, phone numbers and program notes in plain text — searchable, and easy to diff when something changes. |
| `docs/VERIFIED.md` | Which facts were confirmed against a source, which are inferred, and which are still open. Read this before relying on anything. |

## Updating it

Replace the file and commit. GitHub Pages redeploys within about a minute and the URL does not change.

To regenerate the PDF after editing `docs/website-update-list.html`, print it to PDF at Letter size with background graphics enabled.

## A note on sources

Assembled August 10, 2026 from findley.beaverton.k12.or.us, findleypto.com and beaverton.k12.or.us. Every outbound link was individually fetched and checked; results are recorded in `docs/VERIFIED.md`.

Content in the hub is flagged green where it is confirmed for 2026-27, amber where it needs verifying, and red where the source is known to be out of date. **One thing to know up front:** the school's Kindergarten Orientation page publishes a first-week schedule that contradicts the emails sent to families. The emails are correct.

The most useful habit is not this page — it's reading ParentSquare, where nearly every signup and closure actually goes out.

Prepared with the assistance of Claude.
