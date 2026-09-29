# Workshop Lesson Planner

A single-page, fillable planner for facilitators: workshop details, a Learning
Objectives table, and a timed Lesson Planner table. No build step, no
backend — it's one self-contained `index.html` file.

## Features

- Name of workshop + Lead Facilitator fields (Educationalist / Clinical
  Faculty Team / Both)
- **Learning Objectives** table: Details, Number, Assign Developer (same
  role dropdown)
- **Lesson Planner** table: Time, Activity, Addresses Learning Outcome,
  Lead Facilitator, Notes
- "+ Add row" and "+ Add column" on both tables — new columns get an
  editable name
- Text boxes grow automatically as you type
- Entries autosave to your browser's local storage, so a reload keeps your
  draft
- **Export as Word** and **Export as PDF** — builds a clean document from
  whatever you've filled in, skipping any row left completely blank

## Using it

Open `index.html` in any browser — locally, or via GitHub Pages once it's
enabled for this repo (Settings → Pages → deploy from the `main` branch,
`/ (root)` folder). No installation or server required.

## Privacy

Everything you type stays in your own browser's local storage — nothing is
sent to a server. Clearing your browser data (or using a different browser
or device) clears the draft too. If you host this on GitHub Pages, anyone
with the link can open a blank copy of the planner; it does **not** expose
anything you've typed, since that never leaves your own browser.

## Tech

Vanilla HTML/CSS/JS. Word and PDF export use
[docx](https://github.com/dolanmiu/docx) and
[jsPDF](https://github.com/parallax/jsPDF) + jsPDF-AutoTable, loaded from
public CDNs.
