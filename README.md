# Digital Footprint Quiz — How Exposed Are You Online?

A 10-question quiz that measures the thing privacy advice usually leaves vague: **how much of you is findable**. Posting habits, tagging, public profiles, contact exposure and dead accounts each add to a **footprint score (0–30)** and an exposure band — then the quiz builds a **tailored reduction plan** from your two weakest areas. A local account saves your results over time (watch the score drop) and holds the cleanup task list that gets you there.

**Live Demo:** https://anaskhan0009.github.io/digital-footprint-quiz/

## Features

- **Local account system** — sign up / log in on this device (passwords stored only as salted SHA-256 hashes, never plain text), continue as guest, per-account data separation, account deletion, and Export / Import of your records as JSON
- **Full record manager (CRUD)** — create, view, edit and delete your own saved records; the core tool works fully without an account, signing in unlocks saving for quiz results and cleanup tasks in one personal record list
- **Weighted scoring across 6 exposure areas** — public profiles, posting habits, tagging, old accounts, contact exposure, self-awareness
- **Tailored plan, not generic tips** — the output targets your two highest-exposure areas with concrete actions
- **The universal reduction plan** — profile lockdown, dead-account deletion, post-later-not-live, quarterly self-search

## How to Use

1. Answer all 10 questions honestly — nobody sees this but you.
2. Read your band and the two exposure areas driving it.
3. Save the result, then create cleanup tasks from the plan and work them off.
4. Retake the quiz after your cleanup and save the new result — progress you can see.

## Why Your Footprint Is a Security Issue

Scammers and stalkers build their approach from public scraps: your routine from check-ins, your family from a public friends list, your password hints from a visible birthdate and a pet's name in a tagged photo. A smaller footprint is not paranoia — it is removing the raw material of social engineering, one setting and one dead account at a time.

## Ethical Use

This is a **defensive, educational tool** — it only ever helps you understand and improve your own security. Nothing here can be used to attack, track or deceive anyone else.

## Tech

Single self-contained `index.html` — HTML, CSS, vanilla JavaScript, WebCrypto (salted SHA-256 password hashing), localStorage persistence. No servers, no tracking, no external requests.

---

Built by **Dinal Studios** — free cyber security tools and web apps.
GitHub: https://github.com/anaskhan0009
