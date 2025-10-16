---
title: Mental Wellness & Self-Care
layout: default
---

<style>
.page-header { display:none !important; }

.hero-bleed{
  width: 100vw;
  height: clamp(220px, 38vh, 520px);
  position: relative;
  left: 50%;
  margin-left: -50vw;
  margin-right: -50vw;
  background-image: url('{{ "/purchase-hero.png?v=400" | relative_url }}');
  background-repeat: no-repeat;
  background-position: center top;
  background-size: contain;
  background-color: #f5f7fa;
  max-width: none !important;
}

.footer-bleed{
  width: 100vw;
  height: clamp(220px, 38vh, 520px);
  position: relative;
  left: 50%;
  margin-left: -50vw;
  margin-right: -50vw;
  margin-top: 3rem;
  background-color: #F8F1DE;
  background-image: url('{{ "/purchase-footer.png?v=400" | relative_url }}');
  background-repeat: no-repeat;
  background-position: center bottom;
  background-size: contain;
  max-width: none !important;
}

.lc-nav{
  display:flex; gap:.75rem; justify-content:center;
  background:#f6f8fa; padding:.6rem .9rem; border-radius:10px;
  margin: 1rem auto 1.25rem; width:fit-content;
  box-shadow:0 1px 0 rgba(0,0,0,.04);
}
.lc-nav a{ text-decoration:none; font-weight:600; color:#0b5bd3; }
.lc-nav a:hover{ text-decoration:underline; }
.lc-nav span{ opacity:.5 }

.lc-btns{ display:flex; gap:.6rem; flex-wrap:wrap; margin:.9rem 0 1.25rem; }
.lc-btn{
  display:inline-block; padding:.7rem 1rem; border-radius:10px;
  background:#2ea44f; color:#fff !important; font-weight:700; text-decoration:none;
}
.lc-btn.secondary{ background:#0366d6; }

.variant-wrap{ margin:1rem 0 1.25rem; }
.variant-grid{
  display:grid; grid-template-columns: repeat(3, minmax(160px,1fr));
  gap:.6rem;
}
.variant-btn{
  display:block; text-align:center; padding:.7rem 1rem; border-radius:10px;
  background:#111827; color:#fff; font-weight:700; text-decoration:none;
}
.variant-btn:hover{ filter:brightness(1.08); }

.lc-meta{ color:#586069; font-size:.95rem; }
hr.lite{ border:0; border-top:1px solid #eaecef; margin:1.25rem 0; }

@media (max-width: 720px){
  .variant-grid{ grid-template-columns:1fr; }
}
</style>

<div class="hero-bleed"></div>

<div class="lc-nav">
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

## Thanks for your purchase! Subscribe to your Mental Wellness calendar below. 🧠  
Gentle reminders to rest, reflect, and reconnect — right in your calendar.

<div class="lc-btns">
  <a class="lc-btn secondary" href="#variants">Choose Variant</a>
  <a class="lc-btn" href="#how-it-works">How It Works</a>
</div>

<div class="lc-meta">
Works with Apple Calendar, Google Calendar, and Outlook. Events include positive nudges and journaling prompts.
</div>

<hr class="lite" />

## <a id="variants"></a>Pick Your Variant
<div class="variant-wrap">
  <div class="variant-grid">
    <a class="variant-btn" href="/Mental_Daily.ics">🧘 Daily Mindfulness</a>
    <a class="variant-btn" href="/Mental_Weekly.ics">🌿 Weekly Reset</a>
    <a class="variant-btn" href="/Mental_Monthly.ics">🌙 Monthly Reflection</a>
  </div>
</div>

<hr class="lite" />

## <a id="whats-included"></a>What’s Included
- **Daily Mindfulness:** quick gratitude prompt, hydration check, breathing moment  
- **Weekly Reset:** digital detox day, space declutter, social check-in  
- **Monthly Reflection:** goal review, self-kindness note, new intention set  
- Seasonal reminders: daylight change energy check, year reflection, new-season reset  

<hr class="lite" />

## <a id="how-it-works"></a>How It Works
1. Click a variant above to subscribe.  
2. Choose **Subscribe** or **Import** when prompted.  
3. Reminders will appear across all devices automatically.

<hr class="lite" />

## <a id="faq"></a>FAQ
**Are these affirmations or tasks?**  
Both — gentle, actionable prompts to stay grounded.

**Can I edit or delete specific ones?**  
Yes, after subscribing, you can customize freely.

<hr class="lite" />

## <a id="support"></a>Support
Email **lyfecalendars@gmail.com** for feedback or variant requests.

<hr class="lite" />

## <a id="more-calendars"></a>More Calendars
- 💰 [Finance & Bills](/finance)  
- 🧺 [Cleaning & Declutter](/cleaning)  
- ❤️ [Health Check-In](/health)

<div class="footer-bleed"></div>
<p style="text-align:center; color:#6a737d; font-size:.9rem; margin-top:.5rem;">
© {{ 'now' | date: '%Y' }} LyfeCalendars. All rights reserved.
</p>
