# Alaska Cruise & Explorer Trip Dashboard

## Live Dashboard

**URL:** https://manmesin-bay.github.io/alaska-trip-dashboard/

**Password Protected** — Only accessible with the trip password (see `PASSWORD.md`).

---

## What's Inside

| Tab | Contents |
|-----|----------|
| Overview | Trip timeline, booking status, countdown timer |
| Itinerary | Day-by-day plan (13 days: 7 cruise + 6 Alaska) with notes |
| Flights | Flight suggestions, pre-cruise stay info |
| Reviews | Cruise ship reviews and ratings |
| Deals | Onboard deals and packages |
| Budget | Shared expense tracker — divided by 9 per person, accommodation by 3 per family |
| Packing | Alaska-specific packing checklist |
| Checklist | Pre-trip booking checklist |
| Stays | Post-cruise accommodation details and booking confirmations |

---

## Trip Summary

- **Cruise:** Ovation of the Seas — Vancouver to Seward (Jun 26 – Jul 3, 2026)
- **Post-Cruise:** 6 days in Alaska — Seward, Moose Pass, Homer, Anchorage (Jul 3–8)
- **Travelers:** 9 people across 3 families (MS, AK, AW)
- **Cabins:** 3 Ocean View Balcony rooms on Deck 6

## Booked So Far

| Item | Cost | Paid By |
|------|------|---------|
| Cruise (3 cabins) | $12,966 | Each family paid individually |
| Summit Lake Lodge (3 rooms × 2 nights) | $2,193.90 | Manmeet Singh |
| "Unique Sense of Place" Homer (2 nights) | $1,815.50 + $1,500 deposit | Manmeet Singh |
| Downtown Anchorage Grand (1 night) | $980.92 | Manmeet Singh |
| Heli + Glacier Dog Sled (9 people) | $5,394.50 | Manmeet Singh |
| 12-Passenger Van (4 days) | $2,671.76 | Amit Koshal |
| **Total confirmed spend** | **$26,022.58** | |

---

## GitHub Repo

**Repository:** https://github.com/manmesin-bay/alaska-trip-dashboard

### Files

| File | Purpose |
|------|---------|
| `index.html` | The live dashboard served by GitHub Pages |
| `alaska-cruise-dashboard.html` | Working copy you edit in Cursor |
| `.gitignore` | Excludes PDFs and sensitive files from the repo |
| `README.md` | This file |
| `PASSWORD.md` | Password and update instructions (do NOT commit to repo) |

### Security

- Dashboard is password-protected with a SHA-256 hashed password
- PDFs with personal booking details are excluded from the public repo via `.gitignore`
- The password is not stored in plain text in the HTML source code
- Session persists per browser tab (no re-entry needed while tab is open)
