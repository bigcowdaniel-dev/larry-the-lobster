# Larry the Lobster

Larry is an autonomous AI assistant built and operated by [Daniel Lee](https://www.linkedin.com/in/daniel-lee-1205). This repository contains the public-facing landing page for Larry: a single-page site that explains what Larry does, how he is built, and how he operates day to day.

Live site: [bigcowdaniel-dev.github.io/larry-the-lobster](https://bigcowdaniel-dev.github.io/larry-the-lobster/)

## What This Site Covers

- Larry's day-to-day work: business intelligence, email triage, calendar and CRM automation, accountability, and personal ops.
- Larry's operating model: always-on Mac mini, Telegram-first workflow, scheduled jobs, browser automation, and API integrations.
- Larry's stack: Claude API, Node.js, Playwright, Google Workspace, Asana, SSH, and related tooling.
- Larry's design principles: high-agency execution, constraint awareness, and low-friction automation.

## Repository Structure

```text
.
|-- index.html   # Single-page site with markup, styling, and client-side behavior
`-- README.md    # Project overview
```

## Tech Stack

- Plain HTML, CSS, and vanilla JavaScript
- Google Fonts for typography
- No build step
- No framework
- No package manager or runtime dependency required for local editing

## Local Development

Because the project is a static site, the simplest way to work on it is to open `index.html` in a browser.

If you want a local server instead, use any static file server. For example:

```powershell
cd C:\Users\danie\Website\larry-the-lobster
python -m http.server 8080
```

Then open [http://localhost:8080](http://localhost:8080).

## Editing Notes

- The entire site currently lives in `index.html`.
- Styling and interactions are inline, so content, layout, animation, and metadata changes all happen in one file.
- If you update public copy, also update the document metadata near the top of `index.html` so the page title and social preview stay in sync.

## Deployment

The site is intended to be deployed via GitHub Pages from this repository:

- Repo: [bigcowdaniel-dev/larry-the-lobster](https://github.com/bigcowdaniel-dev/larry-the-lobster)
- Site: [bigcowdaniel-dev.github.io/larry-the-lobster](https://bigcowdaniel-dev.github.io/larry-the-lobster/)

## Credits

- Built by [Daniel Lee](https://www.linkedin.com/in/daniel-lee-1205)
- Site content and project concept based on Larry's real operating workflow
