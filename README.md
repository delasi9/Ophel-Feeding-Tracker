# Ophel Academy — Feeding Fees Tracker

A lightweight web app for recording student feeding-fee payments (Day / Week / Term)
and giving the school administrator a live, always-current view of what's been collected.

## Live app (recommended way to use this)
The working, real-time-synced version of this app lives here, hosted by Claude:
👉 https://claude.ai/artifact/L1zxhEWaaBbx9reSCti91J

Share that link with your teachers and admin — no setup needed, updates sync instantly
between everyone who opens it.

## About this repository
This repo holds the **source code** (`index.html`) as a version-controlled backup and
for anyone who wants to read, modify, or redeploy it.

⚠️ **Important:** the live sync (teachers and admin seeing the same data instantly) is
powered by a database feature built into Claude's artifact hosting. If you open
`index.html` directly in a browser, or host it on GitHub Pages, that live-sync feature
will **not** work — you'd need to wire it up to your own backend (e.g. Firebase,
Supabase, or a simple Google Sheets API) for that. Until then, use the claude.ai link
above as the actual working app, and use this repo just to track changes to the code.

## Fee structure (editable in-app under Settings)
- Day: GHS 15 (base rate)
- Week: 15 × school days per week (default 5 → GHS 75)
- Term: 15 × days/week × weeks/term (default 13 weeks → GHS 975)
- live app  coming soon.

## Project structure
```
index.html   # the whole app (HTML/CSS/JS, single file)
README.md    # this file
```
