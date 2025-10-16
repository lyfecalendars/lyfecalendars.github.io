---
title: Home Maintenance
layout: default
---

<style>
/* Hide Cayman header */
.page-header { display:none !important; }

/* HERO IMAGE (identical behavior to Car page) */
.hero-bleed{
  width: 100vw;
  height: clamp(220px, 38vh, 520px);
  position: relative;
  left: 50%;
  margin-left: -50vw;
  margin-right: -50vw;
  background-repeat: no-repeat;
  background-position: center top;
  background-size: contain;
  background-color: #f5f7fa;
  max-width: none !important;
}

/* In-page nav */
.lc-nav{
  display:flex;
  gap:.75rem;
  justify-content:center;
  background:#f6f8fa;
  padding:.6rem .9rem;
  border-radius:10px;
  margin: 1rem auto 1.25rem;
  width:fit-content;
  box-shadow:0 1px 0 rgba(0,0,0,.04);
}
.lc-nav a{ text-decoration:none; font-weight:600; color:#0b5bd3; }
.lc-nav a:hover{ text-decoration:underline; }
.lc-nav span{ opacity:.5 }

/* Buttons */
.lc-btns{ display:flex; gap:.6rem; flex-wrap:wrap; margin:.9rem 0 1.25rem; }
.lc-btn{
  display:inline-block;
  padding:.7rem 1rem;
  border-radius:10px;
  background:#2ea44f;
  color:#fff !important;
  font-weight:700;
  text-decoration:none;
}
.lc-btn.secondary{ background:#0366d6; }

/* Variant section */
.variant-wrap{ margin:1rem 0 1.25rem; }
.variant-columns{ display:grid; grid-template-columns: 1fr 1fr; gap:1rem; }
.variant-card{
  background:#0f172a;
  color:#fff;
  border-radius:12px;
  padding:1rem;
  box-shadow:0 4px 14px rgba(2,6,23,.15);
}
.variant-card h3{ margin:.25rem 0 1rem; font-size:1.15rem; }
.variant-grid{ display:grid; grid-template-columns: 1fr; gap:.6rem; }
.variant-btn{
  display:block;
  text-align:center;
  padding:.7rem 1rem;
  border-radius:10px;
  background:#111827;
  color:#fff;
  font-weight:700;
  text-decoration:none;
}
.variant-btn:hover{ filter:brightness(1.08); }

.lc-meta{ color:#586069; font-size:.95rem; }
hr.lite{ border:0; border-top:1px solid #eaecef; margin:1.25rem 0; }

@media (max-width: 900px){
  .variant-columns{ grid-template-columns: 1fr; }
}
</style>

<!-- HERO IMAGE -->
<div class="hero-bleed"
     style="background-image:url('{{ "/purchase-hero.png?v=200" | relative_url }}');">
</div>

<!-- NAVIGATION BAR -->
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

<!-- MAIN CONTENT -->
## Thanks for your purchase! Subscribe to your Home Maintenance calendar below. 🏠

Keep your home safe and efficient year-round with smart reminders that land right in your calendar.

<div class="lc-btns">
  <a class="lc-btn secondary" href="#variants">Choose Variant</a>
  <a class="lc-btn" href="#how-it-works">How It Works</a>
</div>

<div class="lc-meta">
Works with Apple Calendar, Google Calendar, and Outlook. Each event includes a 1-day-before alert (you can edit or mute anytime).
</div>

<hr class="lite" />

## <a id="variants"></a>Pick Your Variant

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
Your calendar includes recurring reminders for essential home maintenance, tailored by home type and climate:

- HVAC filter changes — every 2–3 months  
- Smoke/CO detector tests — twice per year  
- Dryer vent cleaning — semiannual  
- Water heater flush — annual  
- Gutter and downspout cleaning — spring & fall  
- Exterior inspection & caulking — annual  
- Window seals & weatherstripping — seasonal check  
- Plumbing leak inspection — quarterly  
- Safety kit refresh — annual  
- Furnace/AC service — spring & fall  

**Cold Climate:** adds extra alerts for snow prep, heating checks, and pipe protection  
**Warm Climate:** focuses more on pest prevention and cooling maintenance

<hr class="lite" />

## <a id="how-it-works"></a>How It Works
1. Click a variant above to **subscribe** to that calendar.  
2. Your calendar app will prompt to add it — choose **Subscribe** (recommended) or **Import**.  
   - *Subscribe*: auto-updates when we add new reminders.  
   - *Import*: static copy that you can edit independently.  
3. Adjust notification times or mute individual alerts anytime.

**Tip:**  
- In **Google Calendar** → *Other calendars → Add by URL*  
- In **Outlook** → *Add calendar → From Internet*  
- In **Apple Calendar** → *File → New Calendar Subscription*

<hr class="lite" />

## <a id="faq"></a>FAQ
**Can I combine multiple variants?**  
Yes — subscribe to one per climate and one per home type if you manage multiple properties.

**Are these tasks editable?**  
Absolutely. You can rename, move, or duplicate events directly in your calendar.

**Will I get duplicate reminders if I switch variants?**  
If both calendars contain similar tasks, duplicates may appear — unsubscribe from the older feed first.

<hr class="lite" />

## <a id="support"></a>Support
Questions or feedback?  
📧 Email **lyfecalendars@gmail.com**

<hr class="lite" />

## <a id="more-calendars"></a>More Calendars
- 🚗 **Car Care** → [/car](/car)  
- ❤️ **Health Check-In** → [/health](/health)
