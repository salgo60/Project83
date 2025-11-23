# Project83

**Mål:** Nå 83 kg och bygga långsiktig hälsa genom vandring, dataanalys, GPS-spårning och strukturerad veckouppföljning.

Project83 kombinerar hälsa, friluftsliv och öppen data. Här samlas:
- GPX-filer från alla vandringar (SAT, skridsko, hundrastparker, vardagsrundor)
- Withings-data (vikt, steg, blodtryck m.m.)
- Automatiska analyser via Jupyter Notebooks
- FAIRDATA kopplingar till OSM och Wikidata

## 🥾 Syfte
Att dokumentera och analysera resan mot bättre kondition, mer friluftsliv och målet 83 kg. Projektet bygger på långsiktighet och glädje i att vandra, samla data och bygga öppna resurser.

## 📦 Struktur
```
Project83/
├── gpx/                # Alla GPS-spår, sorterade per år
│   ├── 2025/
│   ├── 2024/
│   └── ...
│
├── metadata/           # Indexfiler för GPX, länkar till OSM/Wikidata
│
├── notebooks/          # Jupyter Notebooks för analys
│   ├── withings_analysis.ipynb
│   ├── gpx_analysis.ipynb
│   └── weekly_report.ipynb
│
├── reports/            # Vecko- och månadsrapporter
│   ├── weekly/
│   └── monthly/
│
└── README.md
```

## 📊 Data som analyseras
- **GPX:** distans, höjd, rutter, tempo, kartor
- **Stegdata:** daglig aktivitet och långtidstrender
- **Viktdata:** morgonrutiner och 10/30-dagars trend
- **Blodtryck:** morgon/kvällslogg
- **Sömn och puls:** vid tillgänglighet

## 🧭 Notebooks
### `withings_analysis.ipynb`
Analys av vikt, steg och trender enligt:
- Stegmål som fungerar bäst för viktminskning
- Konditionsdalar och toppar
- 10- och 30-dagars rullande medelvärden

### `gpx_analysis.ipynb`
Läser in GPX-filer och skapar:
- Folium-kartor
- Veckosammanställningar
- Distans- och höjdstatistik
- "Footprint heatmaps"

### `weekly_report.ipynb`
Automatisk vecko-rapport:
- Steg, distans, vikt
- 10/30-dagars trend
- Sammanfattning + rekommendationer

## 🌍 OSM & Wikidata
Projektet arbetar med FAIRDATA genom att:
- Dokumentera hundrastparker i OSM
- Lägga till öar, leder och platser i Wikidata
- Koppla GPX-rutter till OSM-ID (P402) och way-id (P10689)
- Länka bilder och objekt från öar i skärgården

## 🧠 Mål 2025–2026
- Gå ned till **83 kg** genom daglig rörelse
- Återfå konditionen från SAT-perioden 2025
- Dokumentera friluftslivet som öppna data
- Skapa en komplett livslång GPS-logg
- Underhålla vecko- och månadsrapporter

## 📬 Kontakt
Frågor, idéer eller förslag? Öppna gärna en issue i repo:t!
