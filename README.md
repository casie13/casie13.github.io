# Portfolio — static site

Five pages, no build step, no dependencies. Same architecture as the reference site (plain HTML + GitHub Pages).

```
index.html          landing — hero + the four case cards + contact
case-tochi.html     e-proctoring / privacy (anchor)
case-cihi.html      regulated health data
case-protea.html    tangible interaction
case-thesis.html    behavioural research
images/             drop your visuals here (slots are marked in each page)
```

## Fill it in
Each case page has the same spine — TL;DR, Context, Research question, Methods, Key findings, Impact, Reflection. The italic teal boxes are **writing prompts**: replace each one with your own prose. Delete the prompt box once a section is written. The metadata rows (role / methods / year) have a few `fill in` placeholders.

Start with **case-tochi.html** — it's your strongest asset and the rest get easier once it exists.

## Deploy to GitHub Pages
1. Create a repo. To get a `username.github.io` URL, name it exactly `yourusername.github.io`.
2. Put these files at the repo root and push.
3. Repo → Settings → Pages → Source: `main` branch, `/ (root)` → Save.
4. Live in a minute or two at `https://yourusername.github.io`.

## Before you publish — quick edits
- Email: `you@example.com` in `index.html` (footer) and `case-tochi.html` isn't linked, only index — search `example.com`.
- LinkedIn URL in `index.html` footer (`yourhandle`).
- Confirm the name "Kazma Chaudhry" reads how you want it to professionally.
- Years marked `fill in` on the case pages.

## A note on what I changed from the reference
The reference portfolio is a *product designer's*, so it leads with visuals and an "AI-first / vibe-coded" thesis. Yours is a *researcher's*: it leads with findings and rigor, and I did **not** copy the "vibe-coded with Claude" line — that's her positioning, not yours, and for privacy/security/regulated-data hiring managers your credibility signal is method, not build speed. The structure forces every case to end on *what changed because the research existed.*
