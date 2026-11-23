# ResumeKit — Your One-Page Resume, Built Right

A single-file web app that builds a one-page, ATS-friendly resume with a
live preview. Type on the left, watch the resume build itself on the right.

**Live:** https://abhiramunni.github.io/resumekit/

## What it does

- **Live A4 preview** — every keystroke updates the resume sheet on the
  right. No save button, no signup, nothing uploaded.
- **Live ATS score (0–100)** — ten checks the screening software cares
  about: name, email + phone, location, a 20–60 word summary, at least
  5 skills, at least 3 experience bullets, half or more bullets with a
  number, most bullets starting with an action verb, education listed,
  and fitting on one page (about 42 lines).
- **Length meter** — estimated lines and a "Fits on one page" verdict.
  If the bar turns red, trim a bullet or shorten the summary.
- **Three templates** — Classic (single column), Editorial (dark sidebar)
  and Compact (dense). Switch any time; your content stays.
- **Bullet coach** — paste a bullet and get a score out of 100 with
  plain-words tips. Weak example: "Responsible for managing the website
  and various duties." scores 15. Strong example: "Cut page load time
  by 40% by lazy-loading images and code-splitting routes." scores 100.
  One tap adds a good bullet to your resume.
- **Saved versions** — up to 3 named versions (one per role you apply
  for), saved on your device. Load or delete any of them.
- **Print / Save as PDF** — one tap prints just the resume sheet, no
  watermark. Name the file `Your-Name-Resume.pdf`.
- **Copy plain text** — for portals that ask you to paste your resume.
- **Six plain-language guides** — one page, numbers over adjectives,
  matching the job post's words, action verbs, honest degree status,
  and naming your PDF properly.

## The sample resume

The app ships with a clearly-marked fictional sample — "Asha Nair,
Junior Full-Stack Developer" — so you can see a 100/100 resume at work.
It scores 100 because it passes all ten checks: 28-word summary,
8 skills, 6 bullets (all quantified, all starting with action verbs),
education listed, 25 estimated lines. Remove it with one tap and start
blank.

## How the score is worked out

| Check | Points |
| --- | --- |
| Name on the page | 10 |
| Email and phone listed | 10 |
| Location listed | 5 |
| Summary is 20–60 words | 10 |
| At least 5 skills | 10 |
| At least 3 experience bullets | 10 |
| Half or more bullets have a number | 15 |
| Most bullets start with an action verb | 15 |
| Education listed | 5 |
| Fits on one page (about 42 lines) | 10 |

90+ is excellent, 70+ is strong, 45+ is getting there. These are
common-sense rules, not a guarantee of shortlisting.

## Privacy

Everything is stored in your browser's localStorage. No account, no
server, no tracking. "Erase everything" wipes it all in two taps.

## Files

- `index.html` — the whole app (single file, plus the two photos below)
- `resumekit-hero.webp` — golden-hour desk photo (hero)
- `resumekit-flatlay.webp` — resume flat-lay photo (mid-page band)
- `README.md` — this file

## Run it locally

Open `index.html` in any modern browser. No build step, no server.

Built 23 Nov 2026.
