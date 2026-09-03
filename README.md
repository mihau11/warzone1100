# Niemiecki Arsenał 2WŚ — mod nazw do Warzone 2100 (wersja 4.3.3)

Oto gotowy plik moda, waćpan może go od razu zainstalować. Zmienia on jedynie **nazwy** wszystkich wieżyczek (broni, sensorów, wieżyczek naprawczych, elektronicznych i dowódczej) oraz wszystkich jednostek cyborgów, nadając im miano niemieckiego arsenału z czasów drugiej wojny światowej. Żadna statystyka, model ani balans rozgrywki nie uległy naruszeniu — jest to mod wyłącznie kosmetyczny.

## Dwie wersje moda

W paczce znajdują się teraz dwa pliki:

- **`niemiecki_arsenal.wz`** — dla wersji silnika **4.3.x**.
- **`niemiecki_arsenal_4.7.wz`** — dla wersji silnika **4.7.x** (zbudowany bezpośrednio z oficjalnych plików wydania 4.7.0, dla pewności zgodności co do joty).

Proszę użyć tylko jednego z nich naraz, stosownie do zainstalowanej wersji gry — oba mają tę samą treść (identyczne przechrzczenia), różnią się jedynie dopasowaniem do wewnętrznej struktury danych właściwej wersji. Instalacja przebiega identycznie — plik trafia do `mods/global/`.

## Instalacja

1. Proszę odnaleźć folder konfiguracyjny gry Warzone 2100:
   - **Windows:** `%APPDATA%\Warzone 2100 4.3\`
   - **Linux:** `~/.local/share/warzone2100-4.3/`
   - **macOS:** `~/Library/Application Support/warzone2100-4.3/`
2. Wewnątrz proszę utworzyć (o ile jeszcze nie istnieje) podfolder `mods/global/`.
3. Do owego podfolderu proszę przenieść załączony plik `niemiecki_arsenal.wz`.
4. Przy najbliższym uruchomieniu gry mod winien zostać wykryty automatycznie (w menu głównym, w zakładce dotyczącej modów, można sprawdzić, czy jest on aktywny).

Jeśli waćpan wolałby, aby mod działał wyłącznie w rozgrywce wieloosobowej lub kampanii, plik można też umieścić w podfolderze `mods/multiplay/` bądź `mods/campaign/` zamiast `mods/global/`.

## Co zostało przechrzczone

**Wieżyczki broni (79 sztuk)** — m.in.:
- Machinegun → *MG 34*, Heavy Machinegun → *MG 42*
- Light/Medium/Heavy Cannon → *2 cm KwK 38* / *5 cm KwK 39* / *7,5 cm KwK 40*
- Lancer → *Panzerfaust*, Tank Killer → *Panzerschreck*
- Mini-Rocket Array → *Nebelwerfer 41*
- Needle Gun / Rail Gun → *8,8 cm PaK 43* / *12,8 cm PaK 44*
- Pulse Laser, Flashlight, Plasma Cannon i inna broń energetyczna → nazwy niemieckich programów broni cudownej: *Rheintochter*, *Feuerlilie*, *Enzian*, *Sonnengewehr*, *Röntgenkanone*
- Rakiety SAM → *Wasserfall* i *Schmetterling* (autentyczne niemieckie projekty rakiet przeciwlotniczych)
- Bomby VTOL → *SC 500 Bombe*, *Fritz X* i inne

**Wieżyczki pomocnicze** — sensor → *Funkmessgerät* (z wariantami *Würzburg*, *Freya*), naprawcza → *Bergekran*, zagłuszająca → *Störsender*, saperska → *Pionierschaufel*, dowódcza → *Befehlsstand*.

**Cyborgi** — pancerz lekki/ciężki → *Leichte/Schwere Sturmrüstung*; poszczególne typy cyborgów otrzymały miana żołnierskich funkcji, np. Machinegunner Cyborg → *MG-Schütze*, Lancer Cyborg → *Panzerschreck-Schütze*, Flamer Cyborg → *Flammenwerfer-Pionier*, Combat Engineer Cyborg → *Kampfpionier*.

## Kadłuby pojazdów (body.json) — 16 pozycji

- Viper → Pz. I
- Cobra → Pz. III G
- Tiger → Jagdpanzer IV
- Retaliation → Pz. II Luchs
- Scorpion → Sd.Kfz 234 Puma
- Vengeance → Tiger
- Bug → Sd.Kfz 232
- Retribution → Hetzer
- Python → Pz. IV H
- Leopard → Pz. II F
- Panther → Pz. III L
- Mantis → StuG III G
- Wyvern → Panther
- Dragon → Königstiger
- Super Transport Body → Ju 252
- Transport Body → Ju 52

## Zawieszenia (propulsion.json) — 7 pozycji

- Wheels → Rad-Laufwerk
- Tracks → Ketten-Laufwerk
- Half-tracks → Halbketten-Laufwerk
- Hover → Kreiselantrieb
- VTOL → Strahltriebwerk
- Naval → Schraubenantrieb
- Cyborg Propulsion → Sturmrüstungs-Beinwerk

## Uwaga

Mod sprawdzono pod względem struktury plików JSON zgodnej z gałęzią 4.3.x silnika. Gdyby po instalacji gra zgłosiła błąd wczytywania (rzecz mało prawdopodobna, format nie zmieniał się od dłuższego czasu), proszę dać znać — poprawię plik natychmiast.
