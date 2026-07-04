# Eschberg 44 — woningpresentatie

Statische site (één `index.html` + `assets/` met foto's). Geen build-step, geen externe API's.

## Online zetten via GitHub Pages
1. Maak een nieuwe repository op GitHub (bijv. `eschberg-44`).
2. Upload **de inhoud van deze map** naar de root van de repo:
   - `index.html` (moet in de root staan)
   - de map `assets/`
   - `.nojekyll`
3. Ga in de repo naar **Settings → Pages**.
4. Bij *Build and deployment → Source* kies **Deploy from a branch**,
   branch **main** en map **/ (root)**. Opslaan.
5. Na ~1 minuut is de site live op:
   `https://<gebruikersnaam>.github.io/eschberg-44/`

## In Google Sites zetten
Sites → **Invoegen → Insluiten → Op URL insluiten** → plak de github.io-URL.
Zet de breedte op volledig en de hoogte ruim (bijv. 3000+ px) of gebruik
een volledige-pagina-insluiting.

## Aanpassen
- Foto's vervangen: overschrijf het gelijknamige bestand in `assets/`.
- Volgorde/indeling galerij: de `GCONFIG`-instellingen bovenin het
  tweede `<script>`-blok in `index.html`.
