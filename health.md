---
title: Health Check-In
layout: default
---

<style>
/* Hide Cayman header */
.page-header { display:none !important; }

/* HERO (same as Car/Home) */
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

/* FOOTER hero */
.footer-bleed{
  width: 100vw;
  height: clamp(220px, 38vh, 520px);
  position: relative;
  left: 50%;
  margin-left: -50vw;
  margin-right: -50vw;
  margin-top: 3rem;
  background-color: #F8F1DE; /* warm tone overlay */
  background-image: url('{{ "/purchase-footer.png?v=310" | relative_url }}');
  background-repeat: no-repeat;
  background-position: center bottom;
  background-size: contain;
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

/* Variant section (two columns: Female / Male) */
.variant-wrap{ margin:1rem 0 1.25rem; }
.variant-columns{ display:grid; grid-template-columns: 1fr 1fr; gap:1rem; }
.variant-card{
  background:#0f172a; color:#fff; border-radius:12px; padding:1rem;
  box-shadow:0 4px 14px rgba(2,6,23,.15);
}
.variant-card h3{ margin:.25rem 0 1rem; font-size:1.15rem; }
.variant-grid{ display:grid; gap:.6rem; }
.variant-btn{
  display:block; text-align:center; padding:.7rem 1rem; border-radius:10px;
  background:#111827; color:#fff; font-weight:700; text-decoration:none;
}
.variant-btn:hover{ filter:brightness(1.08); }

.lc-meta{ color:#586069; font-size:.95rem; }
hr.lite{ border:0; border-top:1px solid #eaecef; margin:1.25rem 0; }

@media (max-width: 900px){
  .variant-columns{ grid-template-columns: 1fr; }
}
</style>

<!-- HERO -->
<div class="hero-bleed"></div>

<!-- NAV -->
<div class="lc-nav" role="navigation" aria-label="Health Check-In sections">
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

## Thanks for your purchase! Subscribe to your Health Check-In calendar below. ❤️
Stay on top of preventative care, screenings, and routine visits with reminders that land right in your calendar.

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
      <h3>♀️ Female</h3>
      <div class="variant-grid">
        <a class="variant-btn" href="/Health_Female_Child.ics">Female — Child</a>
        <a class="variant-btn" href="/Health_Female_Adult.ics">Female — Adult</a>
        <a class="variant-btn" href="/Health_Female_Senior.ics">Female — Senior</a>
      </div>
    </div>

    <div class="variant-card">
      <h3>♂️ Male</h3>
      <div class="variant-grid">
        <a class="variant-btn" href="/Health_Male_Child.ics">Male — Child</a>
        <a class="variant-btn" href="/Health_Male_Adult.ics">Male — Adult</a>
        <a class="variant-btn" href="/Health_Male_Senior.ics">Male — Senior</a>
      </div>
    </div>

  </div>
</div>

<hr class="lite" />

## <a id="whats-included"></a>What’s Included
A curated cadence of general check-ins (you can edit once subscribed):

- **Primary care**: annual wellness visit / physical  
- **Dental**: cleaning & exam every 6 months  
- **Vision**: annual exam (or per your optometrist)  
- **Vaccines**: seasonal flu; boosters per guidelines  
- **Baseline labs**: annual CBC, CMP, lipids (adjust with your provider)  
- **Blood pressure**: quarterly self-check reminder  
- **Skin self-exam**: quarterly reminder  
- **Mental well-being**: quarterly check-in prompt  
- **Female-specific (Adult/Senior)**: Pap/HPV per interval, mammogram per age/risk, bone density (DEXA) per guidance  
- **Male-specific (Adult/Senior)**: prostate discussion (PSA/shared decision), abdominal aortic aneurysm screen if applicable  
- **Child**: pediatric wellness cadence, immunization schedule checkpoints, dental/vision as age-appropriate

> These reminders are informational and adjustable—you and your clinician decide the right schedule.

<hr class="lite" />

## <a id="how-it-works"></a>How It Works
1. Click a variant above to subscribe.  
2. Choose **Subscribe** (auto-updating) or **Import** (static copy).  
3. Edit or mute alert times in your calendar app anytime.

**Quick tips**
- **Google Calendar:** Other calendars → *Add by URL* → paste link  
- **Outlook:** *Add calendar → From Internet* → paste link  
- **Apple Calendar:** *File → New Calendar Subscription*

<hr class="lite" />

## <a id="faq"></a>FAQ
**Can I customize tasks or timing?**  
Yes. After subscribing, duplicate or edit events to fit your plan.

**Does this replace medical advice?**  
No—use this as a helpful nudge. Follow guidance from your healthcare providers.

**Can I subscribe to multiple variants?**  
Yes (e.g., your child + your own). Each variant is a separate toggleable calendar.

<hr class="lite" />

## <a id="support"></a>Support
Questions or suggestions? Email **lyfecalendars@gmail.com**.

<hr class="lite" />

## <a id="more-calendars"></a>More Calendars
- 🚗 **Car Care** → [/car](/car)  
- 🏠 **Home Maintenance** → [/home](/home)

<!-- FOOTER HERO -->
<div class="footer-bleed"></div>

<p style="text-align:center; color:#6a737d; font-size:.9rem; margin-top:.5rem;">
© {{ 'now' | date: '%Y' }} LyfeCalendars. All rights reserved.
</p>
