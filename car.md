---
title: Car Care
layout: default
---

<!-- =================== PAGE STYLES =================== -->
<style>
/* Hide the built-in Cayman header for this page */
.page-header { display: none !important; }

/* Full-bleed hero banner (edge-to-edge), 200px tall */
.hero-bleed {
  width: 100vw;
  height: 200px;
  position: relative;
  left: 50%;
  margin-left: -50vw;
  margin-right: -50vw;
  background-repeat: no-repeat;
  background-position: center top;
  background-size: contain;   /* show full image without crop */
  background-color: #ffffff;
  max-width: none !important;
}

/* Gradient fallback (matches banner tones) */
.hero-bleed::before {
  content: "";
  position: absolute;
  inset: 0;
  background: linear-gradient(to right, #b0d0e8, #f5eec9);
  opacity: 0.35;
}

/* Navigation bar */
.lc-nav {
  display: flex;
  gap: .75rem;
  justify-content: center;
  background: #f6f8fa;
  padding: .6rem .9rem;
  border-radius: 10px;
  margin: 1rem auto 1.25rem;
  width: fit-content;
  box-shadow: 0 1px 0 rgba(0,0,0,.04);
}
.lc-nav a { text-decoration: none; font-weight: 600; color: #0b5bd3; }
.lc-nav a:hover { text-decoration: underline; }
.lc-nav span { opacity: .5; }

/* Buttons */
.lc-btns { display: flex; gap: .6rem; flex-wrap: wrap; margin: .9rem 0 1.25rem; }
.lc-btn {
  display: inline-block;
  padding: .7rem 1rem;
  border-radius: 10px;
  background: #2ea44f;
  color: #fff !important;
  font-weight: 700;
  text-decoration: none;
}
.lc-btn.secondary { background: #0366d6; }

.lc-meta { color: #586069; font-size: .95rem; }
hr.lite { border: 0; border-top: 1px solid #eaecef; margin: 1.25rem 0; }

@media (max-width: 720px) {
  .lc-nav { border-radius: 0; width: 100%; }
}
</style>

<!-- =================== HERO IMAGE =================== -->
<div class="hero-bleed"
     style="background-image:url('{{ "/purchase-hero.png?v=100" | relative_url }}');">
</div>

<!-- =================== IN-PAGE MENU =================== -->
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

<!-- =================== MAIN CONTENT =================== -->
## Thanks for your purchase! Subscribe to your Car Care calendar below. 🚗
Keep your vehicle on schedule with smart reminders that land right in your calendar.

<div class="lc-btns">
  <a class="lc-btn" href="/Car_Care.ics">📅 Subscribe (.ics)</a>
  <a class="lc-btn secondary" href="#how-it-works">ℹ️ How It Works</a>
</div>

<div class="lc-meta">
Works with Apple Calendar, Google Calendar, and Outlook. Each event includes a 1-day-before alert (you can edit or mute anytime).
</div>

<hr class="lite" />

## <a id="whats-included"></a>What’s Included
A curated yearly rhythm that fits most daily drivers — no mileage tracking required.

- **Oil change** — every 4 months  
- **Tire rotation** — every 6 months  
- **Battery & terminals check** — every 6 months  
- **Wipers & washer fluid** — quarterly (+ pre-winter)  
- **Air & cabin filters** — twice a year  
- **Brake visual check** — twice a year  
- **Fluids spot checks** (coolant, brake, PS, transmission) — seasonal  
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

> Tip: we can later add **Warm Climate** and **Cold Climate** variants.

<hr class="lite" />

## <a id="how-it-works"></a>How It Works
1. Click **Subscribe (.ics)** above.  
2. Choose **Subscribe** (recommended) or **Import** when prompted.  
   - **Subscribe** → adds a toggleable, auto-updating calendar feed.  
   - **Import** → copies static events into your main calendar.  
3. Reminders appear automatically on all synced devices.

**Quick tips**
- **Google Calendar:** Other calendars → *Add by URL* → paste link  
- **Outlook:** *Add calendar → From Internet* → paste link  
- **Apple Calendar:** *File → New Calendar Subscription*

<hr class="lite" />

## <a id="faq"></a>FAQ
**Does this track mileage?**  
This version is **time-based**, so anyone can use it. A mileage-aware edition may come later.

**Can I change reminder times?**  
Yes — edit or mute alerts in your calendar app after subscribing.

**My inspection month is different.**  
Duplicate or edit that event after subscribing, or request a localized version.

<hr class="lite" />

## <a id="support"></a>Support
Questions or ideas? Email **lyfecalendars@gmail.com** — we love suggestions.

<hr class="lite" />

## <a id="more-calendars"></a>More Calendars
Browse other Lyfe Calendars (info pages only):
- 🏠 **Home Maintenance** — seasonal chores & safety checks → [/home](/home)  
- ❤️ **Health Check-In** — dentist, physicals, labs, vaccines → [/health](/health)
