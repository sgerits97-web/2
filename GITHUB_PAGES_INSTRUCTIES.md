# NTA 8800 App - GitHub Pages Installatie

## 📋 Wat je nodig hebt:
- Een GitHub account (gratis)
- De web-app bestanden
- 10 minuten tijd

---

## 🚀 Stap-voor-Stap Instructies

### Stap 1: Maak een GitHub Account (als je die nog niet hebt)

1. Ga naar: **https://github.com/signup**
2. Vul je email in
3. Maak een wachtwoord
4. Kies een username (bijvoorbeeld: `jouw-naam-123`)
5. Verifieer je email

---

### Stap 2: Maak een Nieuwe Repository

1. Log in op GitHub
2. Klik op de **groene knop "New"** (of ga naar https://github.com/new)
3. Vul in:
   - **Repository name:** `nta8800-app` (of een andere naam)
   - **Description:** "NTA 8800 Opname Applicatie" (optioneel)
   - Kies: **Public** (moet public zijn voor gratis GitHub Pages)
   - Vink AAN: ☑️ "Add a README file"
4. Klik op **"Create repository"**

---

### Stap 3: Upload de Bestanden

**Methode A: Via Website (Gemakkelijkst)**

1. Je bent nu in je nieuwe repository
2. Klik op **"Add file"** → **"Upload files"**
3. Sleep ALLE bestanden uit de `web-app` folder naar het upload veld:
   - `index.html`
   - `manifest.json`
   - `service-worker.js`
   - `icon.svg`
   - `icon-192.png`
   - `icon-512.png`
   - `netlify.toml` (optioneel, maar kan geen kwaad)
   - `README.md` (optioneel)
   
4. Wacht tot alle bestanden zijn geüpload (groene vinkjes)
5. Scroll naar beneden
6. Bij "Commit changes" typ: `Upload NTA 8800 app`
7. Klik op **"Commit changes"**

**Methode B: Via Git (Voor gevorderden)**

```bash
# Clone de repository
git clone https://github.com/JOUW-USERNAME/nta8800-app.git
cd nta8800-app

# Kopieer alle bestanden uit de web-app folder hier naartoe

# Commit en push
git add .
git commit -m "Add NTA 8800 app"
git push
```

---

### Stap 4: Activeer GitHub Pages

1. In je repository, klik op **"Settings"** (tandwiel icoon bovenaan)
2. Klik in het linkermenu op **"Pages"** (onder "Code and automation")
3. Bij **"Source"** selecteer:
   - Branch: **main** (of **master**)
   - Folder: **/ (root)**
4. Klik op **"Save"**
5. Wacht 30-60 seconden
6. Refresh de pagina
7. Je ziet een blauw/groen vak met: 
   **"Your site is live at `https://jouw-username.github.io/nta8800-app/`"**

---

### Stap 5: Test de App

1. Klik op de URL of kopieer deze
2. Open de URL in een **nieuwe tab** in je browser
3. De app zou nu moeten laden!

---

### Stap 6: Installeer op je iPad

1. Open de URL op je iPad in **Safari**
   
   Bijvoorbeeld: `https://jouw-username.github.io/nta8800-app/`

2. Tik op het **Deel-icoon** (□↑ onderaan het scherm)

3. Scroll naar beneden en tik op **"Zet op thuisscherm"**

4. Geef de app een naam: **"NTA 8800"**

5. Tik op **"Voeg toe"**

6. **Klaar!** De app verschijnt nu op je thuisscherm 🎉

---

## ✅ Checklist

- [ ] GitHub account aangemaakt
- [ ] Repository aangemaakt: `nta8800-app`
- [ ] Alle 8 bestanden geüpload
- [ ] GitHub Pages geactiveerd in Settings
- [ ] URL werkt in browser
- [ ] App geïnstalleerd op iPad thuisscherm
- [ ] App werkt offline

---

## 🔧 Troubleshooting

### "404 - Page not found"
- Wacht 2-3 minuten, GitHub Pages heeft even nodig
- Check of de repository **Public** is (niet Private)
- Controleer of `index.html` bestaat in de root folder

### "Settings → Pages is grijs of niet klikbaar"
- De repository moet **Public** zijn
- Je moet eigenaar zijn van de repository

### "Service Worker laadt niet"
- Controleer of de URL begint met `https://` (niet `http://`)
- Open de browser console (F12) voor error messages

### "App installeert niet op iPad"
- Gebruik **Safari** (niet Chrome of andere browsers)
- Controleer of je de HTTPS versie gebruikt
- Probeer de pagina te herladen

### Updates doorvoeren
1. Ga naar je repository op github.com
2. Klik op het bestand dat je wilt wijzigen
3. Klik op het potlood icoon (Edit)
4. Maak je wijzigingen
5. Klik "Commit changes"
6. Wacht 1-2 minuten
7. Herlaad de app op je iPad (of verwijder + herinstalleer)

---

## 📊 Jouw URL structuur

Als je username is: `janbakker` en je repository heet `nta8800-app`

Dan is je app beschikbaar op:
```
https://janbakker.github.io/nta8800-app/
```

Deel deze URL met collega's - iedereen kan de app installeren!

---

## 🎯 Voordelen van GitHub Pages

✅ **Gratis** - Voor altijd  
✅ **Permanent** - Blijft online  
✅ **HTTPS** - Veilig en vereist voor PWA  
✅ **Snel** - GitHub's servers zijn supersnel  
✅ **Betrouwbaar** - 99.9% uptime  
✅ **Makkelijk updaten** - Gewoon bestanden wijzigen  
✅ **Eigen domein mogelijk** - Kan later custom domain toevoegen  

---

## 💡 Tips

- **Bookmark de URL** op je laptop voor makkelijke toegang
- **Deel de URL** met collega's - zij kunnen de app ook installeren
- **Maak backups** - Exporteer belangrijke opnames als PDF
- **Update de app** - Upload gewoon een nieuw index.html bestand

---

## 🆘 Hulp Nodig?

- GitHub Pages documentatie: https://pages.github.com/
- GitHub Support: https://support.github.com/

---

**Succes met de installatie!** 🚀

Na installatie werkt de app volledig offline en heb je geen internet meer nodig voor de dagelijkse opnames.
