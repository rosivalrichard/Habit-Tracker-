# Habit Tracker PWA — GitHub Pages návod

## Čo je v balíku
- `index.html` — hlavná appka
- `manifest.json` — PWA konfigurácia
- `service-worker.js` — offline cache
- `icons/` — ikony appky

## Ako to nahodiť na GitHub Pages
1. Na GitHube vytvor nový repository, napríklad `habit-tracker`.
2. Nahraj doň všetky súbory z tohto balíka.
3. Otvor repository -> **Settings** -> **Pages**.
4. V sekcii **Build and deployment** nastav:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/root**
5. Ulož nastavenie.
6. Po pár minútach bude appka dostupná na URL v tvare:
   - `https://TVOJ-NICK.github.io/habit-tracker/`

## Ako ju nainštalovať do mobilu
### iPhone
1. Otvor URL v Safari.
2. Klikni **Share**.
3. Zvoľ **Add to Home Screen**.
4. Potvrď pridanie.

### Android
1. Otvor URL v Chrome.
2. Browser by mal ponúknuť **Install app** alebo **Add to Home screen**.
3. Potvrď inštaláciu.

## Dôležité
- Appka používa `localStorage`, takže dáta ostávajú uložené lokálne v zariadení a prehliadači.
- Ak otvoríš appku na inom mobile, nebude tam tvoja história, lebo zatiaľ nemá backend ani účet.
- Ak neskôr zmeníš názov repozitára, skontroluj, že link stále smeruje na správnu GitHub Pages adresu.

## Odporúčanie
Ak chceš, ďalší krok by mal byť:
- vlastná ikona s tvojím brandingom,
- export/import dát,
- cloud sync cez Firebase alebo Supabase.
