<style>
/* Force a 200px-tall hero that FITS the full image (no crop) */
.page-header{
  background: url('/purchase-hero.png?v=6') center/contain no-repeat !important;
  height: 200px !important;
  padding: 0 !important;          /* ← Cayman adds big padding; kill it */
  margin: 0 !important;
  border: 0 !important;
  background-color: #fff;         /* fallback for edges */
}

/* Cayman increases padding on large screens; override that too */
@media (min-width: 64em){
  .page-header{ padding: 0 !important; height: 200px !important; }
}

/* Hide default title/subtitle over the hero */
.page-header .project-name,
.page-header .project-tagline{ display: none !important; }
</style>
