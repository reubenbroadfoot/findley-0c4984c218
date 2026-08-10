# What was verified, and when

Everything in this repository was assembled on **August 10, 2026** by reading the Findley Elementary site, findleypto.com, and beaverton.k12.or.us page by page. This file records how much weight each claim can carry, so that future-me can tell a confirmed fact from a reasonable inference.

## Confirmed against a primary source

| Fact | Source |
|---|---|
| First day grades 1–5 is Aug 25, 2026; last day Jun 10, 2027; all no-school days | Official district 2026-27 calendar PDF |
| Bell times 8:25 am – 3:00 pm | District school-schedules page, "Late-Start Elementary" tier, cross-checked against Findley's Kindergarten Orientation page |
| Kindergarten half days Aug 25–28 split by last name | **Email to families**, confirmed by Reuben. Supersedes the website. |
| Staff names, titles, grade assignments | Findley staff directory |
| Supply bundle $50; headphones excluded, plug-in with no microphone | Findley supply list page, updated 5/13/2026 |
| Absence reporting, 2:00 pm going-home cutoff, 2:40 pm early-pickup deadline | Findley attendance and going-home forms |
| Drop-off/pick-up windows and cell-phone-free rule | Findley drop-off/pick-up page |
| Raptor process: 10 business days, valid 2 years, unique email, photo ID | District volunteer pages |
| TAG: universal screening grades 3–5, NGAT-Verbal for grade 4 in October, private testing not accepted | District TAG pages |
| Spirit assembly dates | Findley assemblies page (2026-27) |
| Oregon Exclusion Day Feb 24, 2027 | Oregon Health Authority schedule |
| Immunization rates 2025-26 | Findley immunization-rates page |

## Verified by fetching every link

All 46 outbound links in `index.html` were individually fetched on August 10, 2026, and all 60 links in the worklist PDF as well.

- **Two were dead.** `pledgestar.com/findley` (redirect loop — this is the address the PTO's Dragon Dash page tells families to use) and `pack718.net` (HTTP 500; the working site is `pack718.com`).
- **Three were live but mislabeled.** The PTO "VP application" is a general 2025-26 board interest form; the "Grade Leader form" is the all-school volunteer form; Art Literacy's "Calendar" is a teacher booking sheet for the Art Cart.
- **Four require a Google sign-in**: both Science Fair files, the yearbook volunteer form, and the PTO reimbursement form (HTTP 401 to anyone not on the permitted list).
- **One link I had built myself was wrong** — `/findley-flyers-faq/` 404s; the real path is `/findley-flyers/findley-flyers-frequently-asked-questions/`. Corrected.
- **Nine could not be machine-checked** because the sites block automated access: Amazon supply lists, SchoolCafé, the Facebook group, Quizlet, Scholastic, Fred Meyer, the library catalog, Sora. Normal bot protection, not evidence of breakage — but unconfirmed.

## Inferred, not confirmed

- **All PTO event timing in the "annual rhythm" table** is drawn from 2025-26 actuals, because neither site has posted a 2026-27 calendar. Treat those as "roughly when to expect it," not as dates.
- **Chess Club and Math Olympiad cost, grade eligibility, and registration** have never been published anywhere. Unknown, not merely stale.
- **Whether Findley is a CEP school** (all meals free) is unresolved. The district CEP page would not render. This determines whether money needs loading at all.
- **Door-open and breakfast times** are not published for Findley. A peer late-start school publishes 8:05/8:15/tardy-at-8:25, but that is that school's policy, not Findley's.
- **Teacher assignments** may still reflect 2025-26; the staff directory carries no date.
- **The newsletter "August" link** under the 2026/2027 heading points to a Smore page whose metadata shows a publication date of August 8, 2025. Either the link is wrong or Smore reuses the URL. Unresolved.
- **The IXL vs Dreambox question** — the Academics page says 4th grade uses IXL 45 min/week; the Math page describes Dreambox. One is wrong; I do not know which.

## Known-wrong sources

Do not trust these pages; they are live but out of date. Full list with paths in the worklist PDF.

- **Findley Kindergarten Orientation** — publishes a staggered full-day start that contradicts the emails. Wrong.
- **Findley Meals** — still describes COVID-era curbside pickup.
- **Student handbook** — last updated August 24, 2023.
- **School Improvement Plan** — goals dated June 2024.
- **Parent Partnership letters** — 2020-21.
- **Science page** — May 2019 adoption, K-8 still "pending."
- **Learning Targets** — October 2022.
- **PTO site** — Fall Festival page advertises October 2024; Chess Club 2024; Math Olympiad 2021; Battle of the Books 2019; AmazonSmile (program discontinued); Box Tops (2016 PDF); minutes stop February 2024; blog silent since February 17, 2026. Only the reimbursement form carries a 2026-27 label.

## How to keep this current

The highest-value habit is not maintaining this page — it is reading ParentSquare. Nearly every signup, party, field trip and closure runs through ParentSquare, not the website. This repository is a reference for things that do not change weekly.

When something is confirmed that is listed as inferred above, move it into the confirmed table and note the source. When the PTO posts a 2026-27 calendar, the "annual rhythm" table in `index.html` can be replaced with real dates.
