---
title: Car Care
layout: default
---

<style>
/* 1) Hide Cayman’s built-in header on this page */
.page-header{ display:none !important; }

/* 2) Full-bleed hero: 100vw width, exactly 200px tall */
.hero-bleed{
  width: 100vw;
  height: 200px;
  position: relative;
  left: 50%;
  right: 50%;
  margin-left: -50vw;
  margin-right: -50vw;
  background: #fff; /* edge color when image doesn't fill */
}
.hero-bleed img{
  display: block;
  width: 100%;
  height: 200px;
  object-fit: contain;      /* show the whole image (no crop) */
  object-position: center;
}

/* 3) Simple, non-overlapping nav */
.lc-nav{
  display:flex; gap:.75rem; justify-content:center;
  background:#f6f8fa; padding:.6rem .9rem; border-radius:10px;
  margin: 1rem auto 1.25rem; width:fit-content;
  box-shadow: 0 1px 0 rgba(0,0,0,.04);
}
.lc-nav a{ text-decoration:none; font-weight:600; }
.lc-nav a:hover{ text-decoration:underline; }
.lc-nav span{ opacity:.5 }

.lc-btns{ display:flex; gap:.6rem; flex-wrap:wrap; margin:.9rem 0 1.25rem; }
.lc-btn{
  display:inline-block; padding:.7rem 1rem; border-radius:10px;
  background:#2ea44f; color:#fff !important; font-weight:700; text-decoration:none;
}
.lc-btn.secondary{ background:#0366d6; }
.lc-meta{ color:#586069; font-size:.95rem; }
hr.lite{ border:0; border-top:1px solid #eaecef; margin:1.25rem 0; }

@media (max-width:720px){
  .lc-nav{ border-radius:0; width:100%; }
}
</style>

<!-- 4) Our full-bleed hero -->
<div class="hero-bleed">
  <img src="/purchase-hero.png?v=10" alt="">
</div>

<!-- 5) In-page menu (now safely below the hero) -->
<div class="lc-nav" role="navigation" aria-label="Car Care sections">
  <a href="#whats-included">What’s Included</a>
  <span>•</span>
  <a href="#how-it-works">How It Works</a>
  <span>•</span>
  <a href="#faq">FAQ</a>
  <span>•</span>
  <a href="#support">Support</a>
  <span>•</span>
  <a href="#more-calendars">More Calendars</a>
</div>

## Thanks for your purchase! Subscribe to your Car Care calendar below. 🚗
Keep your vehicle on schedule with smart reminders that land right in your calendar.

<div class="lc-btns">
  <a class="lc-btn" href="/Car_Care.ics">📅 Subscribe (.ics)</a>
  <a class="lc-btn secondary" href="#how-it-works">🔍 How It Works</a>
</div>

<div class="lc-meta">
Works with Apple Calendar, Google Calendar, and Outlook. Each event includes a 1-day-before alert (you can edit or mute anytime).
</div>

<hr class="lite" />

## <a id="whats-included"></a>What’s Included
- **Oil change** — every 4 months  
- **Tire rotation** — every 6 months  
- **Battery & terminals check** — every 6 months  
- **Wipers & washer fluid** — quarterly (+ pre-winter)  
- **Air & cabin filters** — twice a year  
- **Brake visual check** — twice a year  
- **Fluid spot checks** — seasonal  
- **Registration / inspection** — annual reminder  
- **Detail / wash + underbody rinse** — quarterly (bump in salted climates)

**Sample cadence**
- Jan 15 — Winter check: wipers, washer fluid, battery  
- Mar 01 — Oil change  
- Apr 15 — Tire rotation + brake visual  
- Jun 01 — Air/Cabin filters  
- Aug 01 — Oil change  
- Oct 01 — Tire rotation + winter readiness  
- Nov 15 — Winter fluids & wiper swap

> Tip: Warm- and cold-climate variants coming soon.

<hr class="lite" />

## <a id="how-it-works"></a>How It Works
1. Click **Subscribe (.ics)** above.  
2. Choose **Subscribe** (best) or **Import** when prompted.  
   - **Subscribe** → adds a **toggleable calendar** that auto-updates.  
   - **Import** → copies events to your main calendar.  
3. Reminders appear automatically.

**Quick tips**
- **Google Calendar:** Other calendars → **Add by URL** → paste the link  
- **Outlook:** **Add calendar → From Internet** → paste the link  
- **Apple:** **File → New Calendar Subscription**

<hr class="lite" />

## <a id="faq"></a>FAQ
**Does this track mileage?**  
This version is **time-based** so anyone can use it.

**Can I change reminder times?**  
Yes. Edit or mute alerts after subscribing.

**My inspection month is different.**  
Duplicate/adjust that event or request a localized variant.

<hr class="lite" />

## <a id="support"></a>Support
Questions or ideas? Email **lyfecalendars@gmail.com** — we love suggestions.

<hr class="lite" />

## <a id="more-calendars"></a>More Calendars
- 🏠 [**Home Maintenance**](/home) — seasonal chores & safety checks  
- ❤️ [**Health Check-In**](/health) — dentist, physicals, labs, vaccines
