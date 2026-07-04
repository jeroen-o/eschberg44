# Eschberg 44 — woningpresentatie

E�n zelfstandige pagina (`index.html`) met alle foto's ingesloten + de brochure.
Geen build-step, geen externe API's, geen localStorage.

## Bestanden
- `index.html` — de volledige pagina (foto's zitten erin ingesloten)
- `Brochure.pdf` — wordt gelinkt vanaf de knop "Brochure (PDF)"
- `.nojekyll` — laat GitHub de bestanden ongewijzigd serveren

## Online zetten via GitHub Pages
1. Maak een nieuwe repository (bijv. `eschberg-44`).
2. Upload **de inhoud van deze zip** naar de root van de repo
   (`index.html`, `Brochure.pdf`, `.nojekyll`).
3. Settings → Pages → Source: **Deploy from a branch**, branch **main**, map **/ (root)**.
4. Na ~1 min live op: `https://<gebruikersnaam>.github.io/<repo>/`

## In Google Sites
Invoegen → Insluiten → **Op URL insluiten** → plak de github.io-URL.
Volledige breedte, hoge insluithoogte.
