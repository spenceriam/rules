# rules

Public page hosting the three critical instructions for coding agents plus the bug report and draft PR standards, so any agent with web access can load them from one stable URL.

- **Page (raw markdown, `text/markdown`):** https://spenceriam.github.io/rules/index.md — the URL to give agents; served unparsed.
- **Bare path:** https://spenceriam.github.io/rules/ — redirects to the markdown (GitHub Pages only serves `index.html` at the root path; a markdown file cannot occupy it).
- **Source of truth:** private `agent-instructions` repo. `index.md` is generated — the `publish-site` workflow assembles it from `site/index.md` (the operating contract), `design-anti-slop-standard.md`, `bug-report-standard.md`, and `draft-pr-standard.md`, in that order, and pushes it here. Don't edit `index.md` by hand; edit the sources.

Usage: paste this into any new coding agent's first message —

```
Read https://spenceriam.github.io/rules/index.md and adopt all three critical instructions as your operating contract for this session.
```

The ADHD-friendly output rules are adapted from [i-have-adhd](https://github.com/ayghri/i-have-adhd) (MIT).
