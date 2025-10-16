---
title: Home Maintenance
layout: default
---

<!-- =================== PAGE STYLES =================== -->
<style>
/* Hide the Cayman header on this page */
.page-header { display:none !important; }

/* Full-bleed hero: edge-to-edge, tall enough to fill the top area */
.hero-bleed{
  width: 100vw;
  height: clamp(220px, 38vh, 520px);   /* fills the top of the screen */
  position: relative;
  left: 50%;
  margin-left: -50vw;
  margin-right: -50vw;
  background-repeat: no-repeat;
  background-position: center top;
  background-size: contain;            /* show the entire image (no crop) */
  background-color: #f5f7fa;           /* subtle page-matching backdrop */
  max-width: none !important;
}

/* In-page nav */
.lc-nav{
  display:flex; gap:.75rem; justify-content:center;
  background:#f6f8fa; padding:.6rem .9rem; border-radius:10px;
  margin: 1rem auto 1.25rem; width:fit-content;
  box-shadow:0 1px 0 rgba(0,0,0,.04);
}
.lc-nav a{ text-decoration:none; font-weight:600; color:#0b5bd3; }
.lc-nav a:hover{ text-decoration:underline; }
.lc-nav span{ opacity:.5 }

/* Buttons */
.lc-btns{ display:flex; gap:.6rem; flex-wrap:wrap; margin:.9rem 0 1.25rem; }
.lc-btn{
  display:inline-block; padding:.7rem 1rem; border-radius:10px;
  background:#2ea44f; color:#fff !important; font-weight:700; text-decoration:none;
}
.lc-btn.secondary{ background:#0366d6; }

/* Variant grid */
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

<!-- =================== HERO IMAGE (no overlay) =================== -->
<div class="hero-bleed"
     style="background-image:url('{{ "/purchase-hero.png?v=120" | relative_url }}');">
</div>

<!-- =================== HERO IMAGE (no overlay) =================== -->
<div class="hero-bleed"
     style="background-image:url('{{ "/home-hero.png?v=1" | relative_url }}');">
</div>

<!-- =================== IN-PAGE MENU =================== -->
<div class="lc-nav" role="navigation" aria-label="Home Maintenance sections">
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
## Thanks for your purchase! Subscribe to your Home Maintenance calendar below. 🏠
Stay on top of seasonal chores and safety checks with reminders that land right in your calendar.

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
  <div class="variant-columns">

    <div class="variant-card">
      <h3>🌞 Warm Climate</h3>
      <div class="variant-grid">
        <a class="variant-btn" href="/Home_SingleFamily_Warm.ics">Single-Family — Warm</a>
        <a class="variant-btn" href="/Home_Townhome_Warm.ics">Townhome — Warm</a>
        <a class="variant-btn" href="/Home_Apartment_Warm.ics">Apartment — Warm</a>
      </div>
    </div>

    <div class="variant-card">
      <h3>❄️ Cold Climate</h3>
      <div class="variant-grid">
        <a class="variant-btn" href="/Home_SingleFamily_Cold.ics">Single-Family — Cold</a>
        <a class="variant-btn" href="/Home_Townhome_Cold.ics">Townhome — Cold</a>
        <a class="variant-btn" href="/Home_Apartment_Cold.ics">Apartment — Cold</a>
      </div>
    </div>

  </div>
</div>

<hr class="lite" />

## <a id="whats-included"></a>What’s Included
Core annual rhythm tailored for most homes (adjust as you like after subscribing):

- Smoke/CO detector tests & battery swap — semiannual  
- HVAC filter — every 2–3 months (adjust for pets/allergies)  
- HVAC service — spring & fall checks  
- Range hood & bath fans — clean quarterly  
- Water heater flush — annual  
- Dryer vent & lint trap deep clean — semiannual  
- Refrigerator coils & door gaskets — semiannual  
- GFCI test — quarterly  
- Plumbing: leaks, under-sink traps, toilet flappers — quarterly  
- Windows & weatherstripping check — spring/fall  
- Exterior: gutters & downspouts — spring/fall  
- Exterior: foundation, grading, and caulking — annual  
- Safety kit refresh (extinguishers, first-aid) — annual  
- Local requirements (e.g., furnace filters, HOA checks) — as needed

**Sample cadence**
- Jan — Detector test, GFCI test, filter change  
- Mar — Gutters (post-winter), exterior caulking, water heater flush  
- May — AC service, windows & screens  
- Aug — Filter change, dryer vent clean  
- Oct — Heat service, gutters (pre-winter), safety kit refresh

<hr class="lite" />

## <a id="how-it-works"></a>How It Works
1. Click a **variant** above to subscribe.  
2. Choose **Subscribe** (recommended) or **Import** when prompted.  
   - *Subscribe* → adds a toggleable, auto-updating calendar feed.  
   - *Import* → copies static events into your main calendar.  
3. Edit reminder times or mute alerts any time in your calendar app.

**Quick tips**
- **Google Calendar:** Other calendars → *Add by URL* → paste link  
- **Outlook:** *Add calendar → From Internet* → paste link  
- **Apple Calendar:** *File → New Calendar Subscription*

<hr class="lite" />

## <a id="faq"></a>FAQ
**Can I add my own tasks?**  
Yes—after subscribing, duplicate events or create your own alongside this calendar.

**Apartment vs Townhome vs Single-Family—what’s different?**  
Exterior and system checks vary slightly. Apartments emphasize interior/safety items; single-family includes exterior items like gutters and grading.

**Warm vs Cold climate—what’s different?**  
Timing and frequency for HVAC, gutters, exterior sealing, and winterization steps.

<hr class="lite" />

## <a id="support"></a>Support
Questions or ideas? Email **lyfecalendars@gmail.com**.

<hr class="lite" />

## <a id="more-calendars"></a>More Calendars
- 🚗 **Car Care** → [/car](/car)  
- ❤️ **Health Check-In** → [/health](/health)
