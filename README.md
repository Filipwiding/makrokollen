# MakroKollen v4

Matpris-/erbjudande-inspirerad layout, men med egen MakroKollen-vinkel: protein per krona, protein per 100 kcal och deff-score.

## Uppdatera sidan
Ladda upp `index.html` till GitHub-repot `makrokollen`. Vercel uppdaterar automatiskt.

## Supabase
Sidan hämtar data från:
- `product_scores`
- `offer_scores` om tabellen/vyn finns, annars används produktdata som fallback.
