<style>
/* Hide Cayman's built-in header */
.page-header{ display:none !important; }

/* Full-bleed hero: breaks out of the narrow column to span the viewport */
.hero-bleed{
  width: 100vw;             /* full browser width */
  height: 200px;
  position: relative;
  left: 50%;
  right: 50%;
  margin-left: -50vw;       /* escape the container */
  margin-right: -50vw;
  background: #fff;         /* edge color when aspect leaves bars */
  background-image: url('/purchase-hero.png?v=20');  /* <- your file */
  background-repeat: no-repeat;
  background-position: center;
  background-size: contain; /* show the ENTIRE image (no cropping) */
  max-width: none !important;  /* ignore any theme constraints */
}
</style>

<!-- FULL-BLEED HERO -->
<div class="hero-bleed"></div>
