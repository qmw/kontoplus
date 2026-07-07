# KontoPlus — Strona Biura Rachunkowego

Przykładowa strona-wizytówka dla fikcyjnego biura rachunkowego **KontoPlus**. Projekt tworzony jako element portfolio 100strona.pl.

## O stronie

Profesjonalna, korporacyjna strona one-page dla biura księgowego. Styl: czysty, czytelny, budzący zaufanie — ciemny grafit + morska zieleń/teal na bieli.

**Paleta:** `#ffffff` / `#f1f6f5` (tło), `#0f766e` (teal), `#1e293b` (grafit), `#d1f0ec` (mięta akcentowa)  
**Font:** Manrope (400–800) — Google Fonts

## Sekcje

1. Nawigacja (fixed, CTA "Bezpłatna wycena", scrolled-blur)
2. Hero (hasło, dwa CTA, sygnały zaufania, tło z gradientem)
3. Stats bar (liczniki animowane)
4. Usługi (księgowość, kadry i płace, doradztwo podatkowe, JPK/PIT/CIT)
5. Pakiety cenowe (3 plany, wyróżniony "Biznes")
6. Dlaczego my (6 atutów z ikonami)
7. Opinie klientów (4 recenzje)
8. Formularz kontaktu + dane + mapa OSM
9. Footer z creditem 100strona.pl

## Stack

- [Astro 5](https://astro.build/) — framework
- [Tailwind CSS 4](https://tailwindcss.com/) — style (via `@tailwindcss/vite`)

## Komendy

```bash
npm install       # zainstaluj zależności
npm run dev       # serwer developerski → http://localhost:4321
npm run build     # build produkcyjny → dist/
npm run preview   # podgląd builda
```

## Hosting

Projekt gotowy do wdrożenia na [Vercel](https://vercel.com/) — wystarczy połączyć repozytorium.
