# NTA 8800 Opname App

> Progressive Web App voor energie-opnames volgens NTA 8800 norm

[![Live Demo](https://img.shields.io/badge/demo-live-success)](https://jouw-username.github.io/nta8800-app/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

## 📱 Over deze App

Een volledig offline werkende Progressive Web App voor het uitvoeren en documenteren van NTA 8800 energie-opnames. Speciaal geoptimaliseerd voor iPad gebruik met touch interface.

### ✨ Functies

- 📋 **Complete formulieren** voor alle NTA 8800 velden
- 🎨 **Tekencanvas** voor schetsen en aantekeningen (2/3 van scherm)
- 📄 **PDF Export** van volledige opname incl. tekeningen
- 💾 **Lokale opslag** - alle data blijft op je apparaat
- 🔌 **Offline werkend** - geen internet nodig na installatie
- 📱 **Touch geoptimaliseerd** voor tablet gebruik
- 🏗️ **Constructie tabellen** voor isolatie en materialen
- ☀️ **PV-panelen calculator** met oriëntatie en vermogen
- 🔥 **Verwarmings- en ventilatiesystemen** registratie

### 📊 Data Secties

1. Rekenzones & Gebouwgegevens
2. Gebruiksoppervlak (meerdere bouwlagen)
3. Constructies (gevels, daken, vloeren)
4. Verwarming & Tapwater
5. Ventilatie & Koeling
6. PV-Panelen configuratie
7. Vrije aantekeningen
8. Canvas tekening/schets

---

## 🚀 Installatie

### Voor Gebruikers (iPad/Tablet)

1. Open deze URL in **Safari**: `https://jouw-username.github.io/nta8800-app/`
2. Tik op **Delen** (□↑) → **"Zet op thuisscherm"**
3. De app werkt nu als native app, volledig offline!

> ⚠️ **Belangrijk:** Gebruik Safari voor PWA installatie, niet Chrome of Firefox

### Voor Developers

```bash
# Clone repository
git clone https://github.com/jouw-username/nta8800-app.git
cd nta8800-app

# Lokaal draaien
python3 -m http.server 8000
# Of: npx http-server

# Open browser
open http://localhost:8000
```

---

## 📁 Bestanden

```
nta8800-app/
├── index.html              # Hoofd applicatie (single page)
├── manifest.json           # PWA configuratie
├── service-worker.js       # Offline functionaliteit
├── icon.svg                # App icoon (SVG)
├── icon-192.png           # PWA icoon 192x192
├── icon-512.png           # PWA icoon 512x512
├── netlify.toml           # Netlify configuratie (optioneel)
├── .gitignore             # Git ignore regels
└── README.md              # Deze file
```

---

## 🔧 Technologie

- **Pure HTML/CSS/JavaScript** - Geen frameworks
- **Progressive Web App (PWA)** - Installeerbaar & offline
- **Service Worker** - Voor offline caching
- **LocalStorage** - Voor data persistentie
- **Canvas API** - Voor tekenfunctionaliteit
- **jsPDF** - Voor PDF generatie
- **PDF.js** - Voor PDF viewing (optioneel)

---

## 💾 Data Opslag

Alle opnames worden lokaal opgeslagen in de browser's localStorage:
- Formuliergegevens
- Constructie tabellen
- PV-panelen configuraties
- Canvas tekeningen (als base64 PNG)
- Aantekeningen en opmerkingen

**Let op:** Data blijft bewaard zolang je de browser data niet wist. Exporteer belangrijke opnames regelmatig als PDF!

---

## 📱 Browser Ondersteuning

| Browser | Desktop | Mobile/Tablet |
|---------|---------|---------------|
| Safari  | ✅      | ✅ (Aanbevolen)|
| Chrome  | ✅      | ⚠️ (Geen PWA) |
| Firefox | ✅      | ⚠️ (Geen PWA) |
| Edge    | ✅      | ⚠️            |

> PWA installatie werkt alleen in Safari op iOS/iPadOS

---

## 🔒 Privacy & Beveiliging

- ✅ Alle data blijft **lokaal** op je apparaat
- ✅ Geen server, geen database, geen accounts
- ✅ Geen tracking of analytics
- ✅ Geen internet vereist na installatie
- ✅ HTTPS voor veilige overdracht
- ✅ Open source - bekijk de code zelf

---

## 🛠️ Updates

De app update automatisch wanneer:
1. Je de pagina herlaadt in de browser
2. Je de app opnieuw installeert

Of handmatig:
1. Verwijder de app van je thuisscherm
2. Wis Safari cache (optioneel)
3. Herinstalleer via de URL

---

## 📝 Licentie

MIT License - Vrij te gebruiken voor commerciële en niet-commerciële doeleinden.

---

## 🤝 Bijdragen

Verbeteringen en suggesties zijn welkom!

1. Fork het project
2. Maak een feature branch (`git checkout -b feature/verbetering`)
3. Commit je wijzigingen (`git commit -m 'Voeg functie toe'`)
4. Push naar de branch (`git push origin feature/verbetering`)
5. Open een Pull Request

---

## 📞 Support

Voor vragen of problemen:
- Open een [Issue](https://github.com/jouw-username/nta8800-app/issues)
- Check de browser console voor foutmeldingen (F12)

---

## 🎯 Roadmap

Mogelijke toekomstige features:
- [ ] Export naar Excel/CSV
- [ ] Import van bestaande opnames
- [ ] Foto's toevoegen aan opname
- [ ] Template systeem
- [ ] Multi-taal ondersteuning
- [ ] Dark mode
- [ ] Cloud sync (optioneel)

---

**Versie:** 1.0.0  
**Laatste update:** Mei 2026  
**Status:** ✅ Production Ready

---

Gemaakt met ❤️ voor NTA 8800 adviseurs

