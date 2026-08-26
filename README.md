# rules

Public page hosting the two critical instructions for coding agents, so any agent with web access can load them from one stable URL.

- **Page (raw markdown, `text/markdown`):** https://spenceriam.github.io/rules/index.md — the URL to give agents; served unparsed.
- **Bare path:** https://spenceriam.github.io/rules/ — redirects to the markdown (GitHub Pages only serves `index.html` at the root path; a markdown file cannot occupy it).
- **Source of truth:** private `agent-instructions` repo (`AGENTS.md`). Update flow: edit there → copy into `index.md` here → push.

Usage: paste this into any new coding agent's first message —

```
Read https://spenceriam.github.io/rules/index.md and adopt both critical instructions as your operating contract for this session.
```

The ADHD-friendly output rules are adapted from [i-have-adhd](https://github.com/ayghri/i-have-adhd) (MIT).
