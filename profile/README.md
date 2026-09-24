![Banner](banner.jpg)

# CollegeGrub

> Bringing Voice to UW-Madison's Dining Community

[![Website](https://img.shields.io/badge/website-college--grub.com-C1901A?style=flat-square)](https://college-grub.com)
[![App Store](https://img.shields.io/badge/App%20Store-download-000000?style=flat-square&logo=apple&logoColor=white)](https://apps.apple.com/us/app/collegegrub-493cd8/id6758421157)
[![Google Play](https://img.shields.io/badge/Google%20Play-download-414141?style=flat-square&logo=googleplay&logoColor=white)](https://play.google.com/store/apps/details?id=com.xjason321.frontend)
[![Instagram](https://img.shields.io/badge/Instagram-@collegegrub__mad-E4405F?style=flat-square&logo=instagram&logoColor=white)](https://www.instagram.com/collegegrub__mad/)

CollegeGrub is a campus dining feedback platform built for students, by students. It gives UW-Madison students a real, structured way to be heard — and gives dining staff the tools to actually listen.

---

## The Problem

Campus dining affects every student, every day. But feedback has historically gone into a void — comment cards, suggestion boxes, one-off emails that never seem to go anywhere. Students feel unheard. Dining staff lack visibility into what students actually want.

CollegeGrub fixes that.

## What It Does

Students use CollegeGrub to submit suggestions and sign petitions about their campus dining experience — whether that's a new menu item, extended hours, accessibility improvements, or anything else that matters to them. When enough students get behind an idea, it automatically rises to the top for dining staff to review.

On the other side, dining administrators and moderators have a dedicated workspace to review incoming petitions, provide real-time updates, and mark changes as implemented. Students can see exactly where their petitions stand — no more black holes.

It's a two-way conversation, built into the dining community, officially endorsed by UW-Madison's University Housing Dining department.

**Key features:** petition & feedback system · signature thresholds per dining hall · live status tracking from submission to implementation · anonymous submissions · dining hall / meal type / category filtering · push notifications · admin analytics.

---

## Our Repositories

CollegeGrub is split across five repositories — one backend and four independently deployed clients that all talk to it.

| Repository | What it is | Built with |
|---|---|---|
| [**Platform-API**](https://github.com/CollegeGrub/Platform-API) | The backend REST API powering every client — petitions, auth, analytics, the moderator email inbox, and scheduled digests | FastAPI (Python) · MongoDB Atlas · Redis · Docker · Firebase Auth |
| [**Mobile-Platform**](https://github.com/CollegeGrub/Mobile-Platform) | The iOS & Android app — create, sign, and track petitions on the go | React Native · Expo · Expo Router · TypeScript |
| [**Web-Version**](https://github.com/CollegeGrub/Web-Version) | The student-facing web app at [try.college-grub.com](https://try.college-grub.com) — a guest suggestion flow plus a signed-in petition feed | React · Vite · Tailwind CSS · Firebase Auth |
| [**Web-Dashboard**](https://github.com/CollegeGrub/Web-Dashboard) | The internal dashboard dining admins and moderators use to triage petitions, manage the shared email inbox, and view analytics | React · MUI · Recharts · Firebase Auth |
| [**Landing-Page**](https://github.com/CollegeGrub/Landing-Page) | The public marketing site at [college-grub.com](https://college-grub.com) | React · Vite · Tailwind CSS |

---

## Who It's For

CollegeGrub is built for **UW-Madison students** who want their voices heard, and for **University Housing Dining staff** who want to understand and respond to those voices.

## More Coming Soon

We're planning to open-source CollegeGrub so other universities can deploy it for their own campus dining communities — join our RSO to get a sneak peek. Stay tuned, the public release is on its way.

---

📍 University of Wisconsin–Madison · ✉️ [collegegrub@outlook.com](mailto:collegegrub@outlook.com) · *CollegeGrub — because your dining experience matters.*
