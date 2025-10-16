---
title: Home Maintenance
layout: default
---

<style>
/* Hide Cayman header */
.page-header { display:none !important; }

/* SAME AS CAR: full-bleed hero, no overlay, no crop */
.hero-bleed{
  width: 100vw;
  height: clamp(220px, 38vh, 520px);   /* fills the top nicely */
  position: relative;
  left: 50%;
  margin-left: -50vw;
  margin-right: -50vw;
  background-repeat: no-repeat;
  background-position: center top;
  background-size: contain;            /* show entire image */
  background-color: #f5f7fa;           /* subtle backdrop behind transparent areas */
  max-width: none !important;
}

/* In-page nav / buttons (unchanged) */
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
.variant-columns{ display:grid; grid-template-columns: 1fr 1fr; gap:1rem; }
.variant-card{ background:#0f172a; color:#fff; border-radius:12px; padding:1rem; box-shadow:0 4px 14px rgba(2,6,23,.15); }
.variant-card h3{ margin:.25rem 0 1rem; font-size:1.15rem; }
.variant-grid{ display:grid; grid-template-columns: 1fr; gap:.6rem; }
.variant-btn{ display:block; text-align:center; padding:.7rem 1rem; border-radius:10px; background:#111827; color:#fff; font-weight:700; text-decoration:none; }
.variant-btn:hover{ filter:brightness(1.08); }

.lc-meta{ color:#586069; font-size:.95rem; }
hr.lite{ border:0; border-top:1px solid #eaecef; margin:1.25rem 0; }

@media (max-width: 900px){ .variant-columns{ grid-template-columns: 1fr; } }
</style>

<!-- HERO — SAME STRUCTURE AS CAR -->
<div class="hero-bleed"
     style="background-image:url('{{ "/home-hero.png?v=120" | relative_url }}');">
</div>
