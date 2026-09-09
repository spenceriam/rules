# rules

Public page hosting the two critical instructions for coding agents plus the bug report standard, so any agent with web access can load them from one stable URL.

- **Page (raw markdown, `text/markdown`):** https://spenceriam.github.io/rules/index.md — the URL to give agents; served unparsed.
- **Bare path:** https://spenceriam.github.io/rules/ — redirects to the markdown (GitHub Pages only serves `index.html` at the root path; a markdown file cannot occupy it).
- **Source of truth:** private `agent-instructions` repo. The operating-contract section of `index.md` is pushed automatically by that repo's `publish-site` workflow — the Bug Report Standard appendix below it was appended manually as a one-time copy from `bug-report-standard.md` (no auto-sync).

Usage: paste this into any new coding agent's first message —

```
Read https://spenceriam.github.io/rules/index.md and adopt both critical instructions as your operating contract for this session.
```

The ADHD-friendly output rules are adapted from [i-have-adhd](https://github.com/ayghri/i-have-adhd) (MIT).
