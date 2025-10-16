---
title: Car Care
layout: default
---

<style>
/* Hide the Cayman header */
.page-header { display:none !important; }

/* HERO */
.hero-bleed{
  width: 100vw;
  height: clamp(220px, 38vh, 520px);
  position: relative;
  left: 50%;
  margin-left: -50vw;
  margin-right: -50vw;
  background-image: url('{{ "/purchase-hero.png?v=310" | relative_url }}');
  background-repeat: no-repeat;
  background-position: center top;
  background-size: contain;
  background-color: #f5f7fa;
  max-width: none !important;
}

/* FOOTER HERO */
.footer-bleed{
  width: 100vw;
  height: clamp(220px, 38vh, 520px);
  position: relative;
  left: 50%;
  margin-left: -50vw;
  margin-right: -50vw;
  margin-top: 3rem;
  background-color: #F8F1DE; /* warm tone */
  background-image: url('{{ "/purchase-footer.png?v=310" | relative_url }}');
  background-repeat: no-repeat;
  background-position: center bottom;
  background-size: contain;
  max-width: none !important;
}

/* NAV */
.lc-nav{
  display:flex; gap:.75rem; justify-content:center;
  background:#f6f8fa; padding:.6rem .9rem; border-radius:10px;
  margin: 1rem auto 1.25rem; width:fit-content;
  box-shadow:0 1px 0 rgba(0,0,0,.04);
}
.lc-nav a{ text-decoration:none; font-weight:600; color:#0b5bd3; }
.lc-nav a:hover{ text-decoration:underline; }
.lc-nav span{ opacity:.5 }

/* BUTTONS */
.lc-btns{ display:flex; gap:.6rem; flex-wrap:wrap; margin:.9rem 0 1.25rem; }
.lc-btn{
  display:inline-block; padding:.7rem 1rem; border-radius:10px;
  background:#2ea44f; color:#fff !important; font-weight:700; text-decoration:none;
}
.lc-btn.secondary{ background:#0366d6; }

/* VARIANT GRID */
.variant-wrap{ margin:1rem 0 1.25rem; }
.variant-grid{
  display:grid; grid-template-columns: repeat(4, minmax(160px,1fr));
  gap:.6rem;
}
.variant-btn{
  display:block; text-align:center; padding:.7rem 1rem; border-radius:10px;
  background:#111827; color:#fff; font-weight:700; text-decoration:none;
}
.variant-btn:hover{ filter:brightness(1.08); }

.lc-meta{ color:#586069; font-size:.95rem; }
hr.lite{ border:0; border-top:1px solid #eaecef; margin:1.25rem 0; }

@media (max-width: 960px){
  .variant-grid{ grid-template-columns: repeat(2, minmax(160px,1fr)); }
}
@media (max-width: 560px){
  .variant-grid{ grid-template-columns: 1fr; }
}
</style>

<!-- HERO -->
<div class="hero-bleed"></div>

<!-- NAV -->
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
  <a class="lc-btn secondary" href="#variants">Choose Variant</a>
  <a class="lc-btn" href="#how-it-works">How It Works</a>
</div>

<div class="lc-meta">
Works with Apple Calendar, Google Calendar, and Outlook. Each event includes a 1-day-before alert (you can edit or mute anytime).
</div>

<hr class="lite" />

## <a id="variants"></a>Pick your variant
<div class="variant-wrap">
  <div class="variant-grid">
    <a class="variant-btn" href="/Car_Warm.ics">🚗 Car — Warm Climate</a>
    <a class="variant-btn" href="/Car_Cold.ics">🚗 Car — Cold Climate</a>
    <a class="variant-btn" href="/Truck_Warm.ics">🚚 Truck — Warm Climate</a>
    <a class="variant-btn" href="/Truck_Cold.ics">🚚 Truck — Cold Climate</a>
  </div>
</div>

<hr class="lite" />

## <a id="whats-included"></a>What’s Included
- Oil change — every 4 months  
- Tire rotation — every 6 months  
- Battery & terminals check — every 6 months  
- Wipers & washer fluid — quarterly (+ pre-winter)  
- Air & cabin filters — twice a year  
- Brake visual check — twice a year  
- Fluids spot checks — seasonal  
- Registration / inspection — annual reminder  
- Detail / wash + underbody rinse — quarterly (bump in salted climates)

**Sample cadence**
- Jan 15 — Winter check: wipers, washer fluid, battery  
- Mar 01 — Oil change  
- Apr 15 — Tire rotation + brake visual  
- Jun 01 — Air/Cabin filters  
- Aug 01 — Oil change  
- Oct 01 — Tire rotation + winter readiness  
- Nov 15 — Winter fluids & wiper swap

<hr class="lite" />

## <a id="how-it-works"></a>How It Works
1. Click a **variant** above to subscribe.  
2. Choose **Subscribe** (recommended) or **Import** when prompted.  
   - *Subscribe* → adds a toggleable, auto-updating calendar feed.  
   - *Import* → copies static events into your main calendar.  
3. Reminders appear automatically on all synced devices.

**Quick tips**
- **Google Calendar:** Other calendars → *Add by URL* → paste link  
- **Outlook:** *Add calendar → From Internet* → paste link  
- **Apple Calendar:** *File → New Calendar Subscription*

<hr class="lite" />

## <a id="faq"></a>FAQ
**Does this track mileage?**  
This version is time-based.  

**Can I change reminder times?**  
Yes—edit or mute alerts in your calendar app after subscribing.

**My inspection month is different.**  
Duplicate or edit that event after subscribing, or request a localized version.

<hr class="lite" />

## <a id="support"></a>Support
Questions or ideas? Email **lyfecalendars@gmail.com**.

<hr class="lite" />

## <a id="more-calendars"></a>More Calendars
- 🏠 **Home Maintenance** → [/home](/home)  
- ❤️ **Health Check-In** → [/health](/health)

<!-- FOOTER HERO -->
<div class="footer-bleed"></div>

<p style="text-align:center; color:#6a737d; font-size:.9rem; margin-top:.5rem;">
© {{ 'now' | date: '%Y' }} LyfeCalendars. All rights reserved.
</p>
