<div align="center">

<br/>

```
   ██████╗ █████╗███╗   ███╗██████╗ ██╗   ██╗███████╗
  ██╔════╝██╔══██╗████╗ ████║██╔══██╗██║   ██║██╔════╝
  ██║     ███████║██╔████╔██║██████╔╝██║   ██║███████╗
  ██║     ██╔══██║██║╚██╔╝██║██╔═══╝ ██║   ██║╚════██║
  ╚██████╗██║  ██║██║ ╚═╝ ██║██║     ╚██████╔╝███████║
   ╚═════╝╚═╝  ╚═╝╚═╝     ╚═╝╚═╝      ╚═════╝ ╚══════╝
        ██████╗ ██████╗ ███╗   ██╗███╗   ██╗███████╗ ██████╗████████╗
        ██╔════╝██╔═══██╗████╗  ██║████╗  ██║██╔════╝██╔════╝╚══██╔══╝
     ██║     ██║   ██║██╔██╗ ██║██╔██╗ ██║█████╗  ██║        ██║
     ██║     ██║   ██║██║╚██╗██║██║╚██╗██║██╔══╝  ██║        ██║
     ╚██████╗╚██████╔╝██║ ╚████║██║ ╚████║███████╗╚██████╗   ██║
      ╚═════╝ ╚═════╝ ╚═╝  ╚═══╝╚═╝  ╚═══╝╚══════╝ ╚═════╝   ╚═╝
```

### *Every opportunity on campus. One place.*

<br/>

![Status](https://img.shields.io/badge/Status-Active%20Development-22c55e?style=for-the-badge&labelColor=0f0f0f)
![Built With](https://img.shields.io/badge/Stack-HTML%20%7C%20CSS%20%7C%20JS-f59e0b?style=for-the-badge&labelColor=0f0f0f)
![University](https://img.shields.io/badge/Pilot-MUJ%20Jaipur-6366f1?style=for-the-badge&labelColor=0f0f0f)
![License](https://img.shields.io/badge/License-MIT-ec4899?style=for-the-badge&labelColor=0f0f0f)

<br/>

</div>

---

## The Problem Nobody Talks About

> *"There was a hackathon last weekend. I heard about it on Monday."*

Sound familiar?

Inside every university, things are constantly happening  hackathons, study groups, football matches, music jams, startup idea sessions. But the information to find them is buried in:

| Channel | Problem |
|---|---|
| 📱 WhatsApp groups | You have to be in the right one |
| 📸 Instagram stories | Gone in 24 hours |
| 📌 Posters | You have to walk past them |
| 📧 Emails | Lost in the inbox |
| 🗣️ Word of mouth | Luck-based |

**The result?** The most engaged 10% of students know everything. The rest miss most of it.

There is no single place where a student can open an app and see:
- What is happening on campus **today**?
- What can I **join**?
- Who shares my **interests**?

---

## What CampusConnect Does

**CampusConnect** is a centralized student event platform — built to turn fragmented campus information into a structured discovery experience.

```
Student creates event  →  Platform surfaces it  →  Interested students find & join it
```

Starting with **Manipal University Jaipur (MUJ)** as the pilot campus.

---

## Events You Can Discover (or Create)

<table>
<tr>
<td>🏆 Hackathons</td>
<td>📚 Study Groups</td>
<td>⚽ Sports Matches</td>
</tr>
<tr>
<td>💡 Startup Idea Sessions</td>
<td>🎵 Music Jams</td>
<td>🔧 Project Collabs</td>
</tr>
<tr>
<td>🎤 Workshops</td>
<td>🤝 Club Activities</td>
<td>☕ Casual Meetups</td>
</tr>
</table>

Anyone can post. Not just clubs. Not just admins. **Any student.**

---

## Core Product Principles

### 🔐 1. Trust-First Onboarding
Login restricted to **official university email IDs** only.
- Ensures a real student community
- Reduces spam from day one
- Builds credibility without moderation overhead

### 🧭 2. Clean Discovery Interface
Minimal event feed. Clear cards. Quick join actions. Every design decision optimized for **low-friction interaction** — because friction kills discovery.

### 🙌 3. Student-Driven Ecosystem
No gatekeeping. Any student can create an event. Clubs, individuals, random people with an idea — all equal. Encourages initiative over passive consumption.

### 👥 4. Social Layer Built In
**Best Friends** — a feature that automatically surfaces the people you interact with most, based on shared events and activity. Real connections over follower counts.

### 🌐 5. Web-First Architecture
No app store. No install. Works on mobile, laptop, and tablet. **Zero installation barrier.**

### 📈 6. Built to Scale
Starting at MUJ. Architecture designed so any university can have its own verified community environment — same product, isolated communities.

---

## Current Progress

```
✅ Full UI system designed
✅ Landing page — built
✅ Authentication flow — designed
✅ Dashboard — built
✅ Event pages — designed
✅ Profile structure — designed
✅ Social components — designed
✅ Working HTML/CSS/JS prototype
✅ Scalable design token system

🔨 Event creation workflow — in progress
🔨 Interaction-based friend ranking logic — in progress
🔨 Database integration — in progress
🔨 Auth flow (institutional email) — in progress
🔨 Responsive optimization — in progress
```

---

## Tech Stack

```
Frontend      →   HTML, CSS, Vanilla JavaScript
Auth Layer    →   University email ID gating (institutional domain validation)
Architecture  →   Web-first, no framework dependency, GitHub Pages compatible
Design System →   Custom design token system for consistent, scalable UI
```

> No build steps. No dependencies. Just open and run.

---

## What I'm Learning Through This Build

- How **product thinking** differs from solving coding exercises
- How **UI decisions** directly shape user behavior
- How to design **scalable systems** from the start, not after the fact
- How **social features** change engagement patterns entirely
- How a small, focused tool can solve a **genuinely real problem**

---

## Project Structure

```
campusconnect/
├── index.html              # Landing page
├── auth/
│   └── login.html          # Institutional email login
├── dashboard/
│   └── index.html          # Main event feed
├── events/
│   ├── create.html         # Event creation
│   └── [event-id].html     # Event detail page
├── profile/
│   └── index.html          # User profile + Best Friends
├── assets/
│   ├── css/
│   │   ├── tokens.css      # Design token system
│   │   └── components.css  # Reusable component styles
│   └── js/
│       └── app.js          # Core app logic
└── README.md
```

---

## Getting Started

```bash
# Clone the repo
git clone https://github.com/devSatyamm/campusconnect.git

# Navigate into it
cd campusconnect

# Open in browser — no build step needed
open index.html
```

That's it.

---

## Roadmap

| Phase | Focus | Status |
|---|---|---|
| **Phase 1** | UI system + Working prototype | ✅ Done |
| **Phase 2** | Event creation + Auth flow | 🔨 In Progress |
| **Phase 3** | Database + Backend integration | 📋 Planned |
| **Phase 4** | Friend ranking algorithm | 📋 Planned |
| **Phase 5** | Multi-university expansion | 🔭 Vision |

---

## Building in Public

This project is being built in the open because **early feedback improves product direction**.

If you've worked on any of these:
- Campus or community platforms
- Event discovery systems
- Social apps for niche communities
- Student startup tools

**Your insights or suggestions would genuinely help.** Open an issue, start a discussion, or reach out directly.

---

## Contributing

```bash
# Fork the repo
# Create your branch
git checkout -b feature/your-idea

# Commit your changes
git commit -m "feat: describe what you added"

# Push and open a PR
git push origin feature/your-idea
```

All contributions welcome : design feedback, code, or just ideas.

---

## 📜 License
 
MIT : use it, remix it, build on it.
 
---
 
<div align="center">
<br/>
  
**Built by a student. For students.**

 
*Piloting at Manipal University Jaipur then expanding everywhere.*

 
<br/>

[![GitHub Stars](https://img.shields.io/github/stars/devSatyamm/campusconnect?style=for-the-badge&logo=github&labelColor=0d1117&color=f59e0b)](https://github.com/devSatyamm/campusconnect/stargazers)

[![GitHub Forks](https://img.shields.io/github/forks/devSatyamm/campusconnect?style=for-the-badge&logo=github&labelColor=0d1117&color=6366f1)](https://github.com/devSatyamm/campusconnect/network)

[![GitHub Issues](https://img.shields.io/github/issues/devSatyamm/campusconnect?style=for-the-badge&logo=github&labelColor=0d1117&color=ec4899)](https://github.com/devSatyamm/campusconnect/issues)
 
<br/>

⭐ **Star this if you believe every student deserves to know what's happening on their campus.**

 
<br/>

`#buildinpublic` `#webdev` `#productdesign` `#studentstartup` `#muj` `#campustech`

 
</div>
 
