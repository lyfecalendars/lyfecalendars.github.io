---
title: Car Care
layout: default
---

<!-- ───────────────────────── NAV ───────────────────────── -->
<div class="lc-nav">
  <a href="/">🏠 Home</a>
  <span>•</span>
  <a href="/home">🛠️ Home Maintenance</a>
  <span>•</span>
  <a href="/car">🚗 Car Care</a>
  <span>•</span>
  <a href="/health">❤️ Health Check-In</a>
</div>

<style>
.lc-nav{
  display:flex; gap:.75rem; justify-content:center;
  background:#f6f8fa; padding:.6rem .9rem; border-radius:10px;
  margin: 1rem auto 1.25rem; width:fit-content;
  box-shadow: 0 1px 0 rgba(0,0,0,.04);
}
.lc-nav a{ text-decoration:none; font-weight:600; }
.lc-nav a:hover{ text-decoration:underline; }
.lc-nav span{ opacity:.5 }
.lc-btns{ display:flex; gap:.6rem; flex-wrap:wrap; margin:.5rem 0 1.25rem; }
.lc-btn{
  display:inline-block; padding:.6rem .9rem; border-radius:10px;
  background:#2ea44f; color:#fff !important; font-weight:700; text-decoration:none;
  box-shadow:0 1px 0 rgba(0,0,0,.04);
}
.lc-btn.secondary{
  background:#0366d6;
}
.lc-meta{ color:#586069; font-size:.95rem; }
hr.lite{ border:0; border-top:1px solid #eaecef; margin:1.25rem 0; }
.lc-kv{ display:grid; grid-template-columns: 1fr 1fr; gap:.5rem; max-width:720px; }
@media (max-width:720px){ .lc-kv{ grid-template-columns: 1fr; } }
.lc-note{ background:#fffdef; border:1px solid #f1e6a8; padding:.75rem .9rem; border-radius:8px; }
</style>

## 🚗 Car Care
Keep your vehicle on schedule with smart reminders that land right in your calendar.

<div class="lc-btns">
  <a class="lc-btn" href="https://lyfecalendars.github.io/Car_Care.ics">📅 Subscribe / Download (.ics)</a>
  <a class="lc-btn secondary" href="#whats-inside">🔍 See what’s included</a>
</div>

<div class="lc-meta">
Works with Apple Calendar, Google Calendar, and Outlook. All events include a 1-day-before alert you can edit or mute anytime.
</div>

<hr class="lite" />

### Why this helps
- Never miss **oil changes** or **tire rotations**
- Stay ahead of **registration / inspection** deadlines
- Remember seasonal checks (battery, wipers, fluids)
- Keep resale value by maintaining a clean service rhythm

---

## <a id="whats-inside"></a>What’s inside
A curated yearly rhythm tuned for most daily drivers. (Time-based by default so it works even if you don’t track mileage.)

**Core cadence**
- **Oil change** — every 4 months  
- **Tire rotation** — every 6 months  
- **Battery & terminals check** — every 6 months  
- **Wiper blades & washer fluid** — quarterly (+ before winter)  
- **Air filter / Cabin filter** — twice a year  
- **Brake visual check** — twice a year  
- **Fluids** (coolant, brake, power steering, transmission as applicable) — seasonal spot checks  
- **Registration / inspection** — auto-dated once a year  
- **Detail / wash + underbody rinse** — quarterly (more in salted climates)

**Examples of dated events**
- Jan 15 — Winter check: wipers, washer fluid, battery health  
- Mar 01 — Oil change  
- Apr 15 — Tire rotation + brake visual  
- Jun 01 — Cabin & engine air filter check  
- Aug 01 — Oil change  
- Oct 01 — Tire rotation + winter readiness  
- Nov 15 — Winter fluids & wiper swap  
- (Plus your **state registration/inspection** month)

> 💡 Want to localize later? You can publish **Warm Climate** and **Cold Climate** variants with slightly different seasonal timing.

---

## How it works
1. Click **Subscribe / Download (.ics)** above.  
2. Your calendar app will offer to **subscribe** (best) or **import**.  
   - *Subscribe =* shows up as its **own toggleable calendar** and auto-updates.  
   - *Import =* copies events to your main calendar.  
3. That’s it — reminders will pop up automatically.

> **Tip (Google Calendar):** “Other calendars → Add by URL → paste the link.”  
> **Tip (Outlook):** “Add calendar → From Internet → paste the link.”  
> **Tip (Apple):** “File → New Calendar Subscription…”

---

## FAQ

**Will this track mileage?**  
This version is **time-based** so anyone can use it. If you want a mileage-aware variant later, we’ll publish an optional “Pro” feed with odometer prompts.

**Can I change reminder times?**  
Yep. Each event includes a 1-day-before alert by default. You can edit or mute reminders in your calendar app.

**What if my inspection month is different?**  
After subscribing, duplicate that event to your specific month or tell us and we’ll add a localized variant.

---

## Support
Questions or ideas? Email **lyfecalendars@gmail.com** — we love suggestions.

[← Back to all calendars](/)
