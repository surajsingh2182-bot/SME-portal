# SME Connect Portal

> An internal portal that helps team members find Subject Matter Experts (SMEs) to navigate roadblocks on challenging client projects.

---

## What is this?

When teams hit a roadblock on a complex project, finding the right expert quickly can make or break a deadline. **SME Connect** solves this by giving everyone in the organisation a single place to:

- Discover who the internal experts are
- See their availability before reaching out
- Send a structured help request or quick message
- Schedule a meeting directly via their calendar link
- Rate the SME after getting help — earning them points and badges

---

## Features

### For Team Members
- Search SMEs by skill, domain, or name
- Filter by availability (Available Now / Busy)
- Send a **Quick Message** or a **Detailed Help Request** (with project name, problem description, skills needed, and urgency level)
- Book a meeting directly via the SME's calendar link (Calendly, Teams, etc.)
- Rate SMEs after getting help (1–5 stars)

### For SMEs
- Self-register and create your own profile
- List your skills, past projects, availability, and meeting link
- Earn points for every help session and great rating
- Climb the leaderboard and earn Bronze / Silver / Gold badges

### For Admins
- View all registered SMEs and their status
- Track all help requests across the organisation
- Monitor resolution rates and engagement metrics

### Points & Badges System
| Badge | Points Required | What it means |
|-------|----------------|----------------|
| 🥇 Gold | 500+ points | Top expert, highly recognised |
| 🥈 Silver | 200–499 points | Experienced and trusted helper |
| 🥉 Bronze | 50–199 points | Rising contributor |
| 🔰 New | 0–49 points | Just getting started |

Points are earned by:
- Resolving a help request → **+20 points**
- Receiving a 5-star rating → **+15 points**
- Receiving a 4-star rating → **+10 points**
- Any other rating → **+5 points**

---

## Tech Stack

This is a single-file web application — no frameworks, no installation, no backend required.

| Layer | Technology |
|-------|-----------|
| Structure | HTML5 |
| Styling | CSS3 (no external libraries) |
| Logic | Vanilla JavaScript |
| Hosting | GitHub Pages (free) |

Everything runs in the browser. No server, no database, no setup needed.

---

## How to Run Locally

1. Download or clone this repository
2. Open `index.html` in any web browser (Chrome, Safari, Firefox)
3. That's it — the app runs instantly

No installation. No terminal commands. No dependencies.

---

## How to Deploy (Make it Live)

This app is hosted using **GitHub Pages** for free:

1. Push this repository to GitHub
2. Go to **Settings → Pages**
3. Set source to `main` branch
4. Your live URL will be: `https://yourusername.github.io/sme-connect-portal`

---

## Project Structure

```
sme-connect-portal/
│
├── index.html       ← The entire app (HTML + CSS + JavaScript in one file)
└── README.md        ← This file
```

---

## Future Improvements

- [ ] Connect to a real database (e.g. Firebase or Supabase) so data persists
- [ ] Add login / authentication so each user has their own account
- [ ] Email notifications when a help request is sent
- [ ] Admin ability to approve or reject SME registrations
- [ ] Export SME directory to CSV or PDF
- [ ] Mobile app version

---

## About This Project

This portal was designed with a **Business Analyst / Product Manager** mindset — focusing on real user needs:

- Team members need to find help **fast**, without knowing who to call
- SMEs need **recognition** for their contributions to stay motivated
- Admins need **visibility** into how knowledge is flowing across the org

Built as a learning project while exploring product development and vibe coding.

---

## Author

**Vijendra** — Aspiring Product Manager | Business Analyst

---

*Built with the help of Claude (Anthropic) as part of a learning journey into product development and coding.*
