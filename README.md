# təməsew̓txʷ Aquatic and Community Centre — Pool Relay embed preview

A mockup of the Lap Pool Lane Schedule on the centre's
[facility page](https://www.newwestcity.ca/parks-and-recreation/facilities/temesewtx-aquatic-and-community-centre)
(New Westminster, BC), on live [Pool Relay](https://www.poolrelay.com) calendars.

Not an official City of New Westminster page. It says so in a ribbon across the top.

Built with `python3 build.py` (the chrome lives there; edit it, not the HTML) and served by GitHub Pages.

## The pages

| Page | Calendar | Scoped to |
|---|---|---|
| `index.html` — Lap Pool lane schedule | [`EAC0sD8h…`](https://www.poolrelay.com/v/EAC0sD8hAvVP3xbSMiUyXB) | the Lap Pool lane by lane, one day; opens on Short Course (25 m) |
| `week.html` — The pool week | [`RrfODQia…`](https://www.poolrelay.com/v/RrfODQiaUOkxieHrLF1zaT) | the Lap Pool's week, lane count and course on each block |

## Source (read 2026-10-05)

- **Facility page**, *Lap Pool Lane Schedule — Fall: September 21 – December 18, 2026*: a seven-column HTML table,
  each cell a time, a lane count and `(50m)` or `(25m)`. Read cell by cell; flattening the text detaches blocks
  from their day.
- **Holiday Hours** page: no holiday entries posted yet.

## What is ours

- **Lanes.** The page gives lane counts, not lane numbers, so open lanes are drawn from lane 1.
- **24 weekly series**, one per block shape (Tue/Thu share a grid; Mon/Wed/Fri share most of theirs).
- **Start date Sept 24**, the day after the posted Sept 8–23 maintenance shutdown, not the grid's Sept 21.
- No holiday closures entered; none are published.

## Open questions (also on the page)

| | |
|---|---|
| **Gap** | Is the tank bulkheaded into two 25 m courses? The grid never shows more than 8 short-course lanes. |
| **Conflict** | Fall grid from Sept 21 vs. maintenance shutdown to Sept 23. |
| **Gap** | Thanksgiving (Oct 12) and Remembrance Day (Nov 11) hours. |
| **Gap** | What uses the lanes that aren't open for length swim. |
| **Gap** | Leisure Pool (3 lanes) and the dive tank: no published grid. |
