# 🎓 ESCAPE ROOM ACADEMY - Komplett Installationsguide

## 📦 FILER I PAKETET

Du har nu 4 filer totalt:

### 1. **index.html** (Huvudsidan - obligatorisk)
- Detta är startsidan med ämneskort
- MÅSTE heta exakt `index.html` för GitHub Pages
- Innehåller länkar till alla escape rooms

### 2. **matte-escape.html** (Matematik - Svenska)
- Escape room för matematik åk 7-9
- Färgglad och rolig design
- Ämnen: Ekvationer, procent, geometri, talföljder, problemlösning

### 3. **english-escape.html** (Engelska språk - Dark Academia)
- Escape room för engelska åk 7-9
- "The Forbidden Library" tema
- Ämnen: Grammar, vocabulary, tenses, comprehension, idioms

### 4. **README.md** (Dokumentation)
- Förklaring av projektet
- Användningsguide
- Tips för lärare

---

## 🚀 STEG-FÖR-STEG INSTALLATION

### METOD 1: GitHub Pages (Rekommenderad - Gratis hosting!)

#### Steg 1: Förbered filerna
Innan du laddar upp, kontrollera att du har följande filer med EXAKT dessa namn:

```
✅ index.html          (huvudsidan)
✅ matte-escape.html   (matematik)
✅ english-escape.html (engelska)
✅ README.md           (dokumentation)
```

#### Steg 2: Skapa GitHub-konto
1. Gå till [github.com](https://github.com)
2. Klicka på "Sign up" (om du inte har konto)
3. Följ instruktionerna och verifiera din email

#### Steg 3: Skapa nytt repository
1. Klicka på **"+"** i övre högra hörnet
2. Välj **"New repository"**
3. Repository namn: `escape-room-academy` (eller valfritt namn)
4. Välj **"Public"** (måste vara public för GitHub Pages)
5. **KRYSSA INTE I** "Add a README file"
6. Klicka **"Create repository"**

#### Steg 4: Ladda upp filerna
1. På repository-sidan, klicka på **"uploading an existing file"**
2. Dra och släpp ALLA 4 filer samtidigt:
   - index.html
   - matte-escape.html
   - english-escape.html
   - README.md
3. Scrolle ner och klicka **"Commit changes"**
4. Vänta tills uppladdningen är klar (grön checkmark)

#### Steg 5: Aktivera GitHub Pages
1. Klicka på **"Settings"** (högst upp i repositoryt)
2. Klicka på **"Pages"** i vänstermenyn
3. Under **"Source"**:
   - Välj **"Deploy from a branch"**
   - Branch: Välj **"main"**
   - Folder: Välj **"/ (root)"**
4. Klicka **"Save"**
5. Vänta 1-2 minuter

#### Steg 6: Hitta din webbadress
1. Gå tillbaka till **"Settings" → "Pages"**
2. Högst upp ser du nu: **"Your site is live at:"**
3. Din adress är: `https://dittanvändarnamn.github.io/escape-room-academy/`
4. Klicka på länken för att testa!

---

### METOD 2: Lokal användning (Utan internet)

#### För Windows:
1. Skapa en ny mapp på skrivbordet: `EscapeRoomAcademy`
2. Lägg alla 4 filer i mappen
3. Dubbelklicka på `index.html`
4. Din webbläsare öppnar startsidan automatiskt

#### För Mac:
1. Skapa en ny mapp i Dokument: `EscapeRoomAcademy`
2. Lägg alla 4 filer i mappen
3. Högerklicka på `index.html` → "Öppna med" → Chrome/Safari
4. Startsidan öppnas i webbläsaren

#### För Chromebook:
1. Öppna "Filer" appen
2. Skapa ny mapp: `EscapeRoomAcademy`
3. Lägg alla 4 filer i mappen
4. Dubbelklicka på `index.html`

---

## 🔗 LÄNKSTRUKTUR (Hur allt hänger ihop)

```
index.html (Huvudsidan)
    │
    ├─→ matte-escape.html (Klicka på Matematik-kortet)
    ├─→ english-escape.html (Klicka på English-kortet)
    ├─→ [Svenska - Kommer snart]
    └─→ [SO - Kommer snart]
```

### Länkar i index.html:
- Matematik-kortet → `href="matte-escape.html"`
- English-kortet → `href="english-escape.html"`
- Svenska-kortet → Inaktiverad ("Kommer snart")
- SO-kortet → Inaktiverad ("Kommer snart")

---

## ✅ CHECKLISTA - Kontrollera detta!

### Innan uppladdning:
- [ ] Filen heter exakt `index.html` (inte Index.html eller INDEX.html)
- [ ] Filen heter exakt `matte-escape.html` (inte matte-escape.HTML)
- [ ] Filen heter exakt `english-escape.html`
- [ ] Alla filer är i samma mapp
- [ ] Du har inte ändrat något i filerna

### Efter uppladdning till GitHub:
- [ ] Repository är "Public"
- [ ] GitHub Pages är aktiverat
- [ ] Source är satt till "main" branch
- [ ] Du kan se alla 4 filer i repositoryt
- [ ] Du har väntat minst 1-2 minuter efter aktivering

### Testa funktionalitet:
- [ ] Huvudsidan laddas korrekt
- [ ] Matematik-kortet går att klicka på
- [ ] Matematik escape room öppnas när du klickar
- [ ] English-kortet går att klicka på
- [ ] English escape room öppnas när du klickar
- [ ] Svenska och SO visar "Kommer snart"

---

## 🐛 FELSÖKNING

### Problem: "404 Not Found" när jag klickar på escape room
**Lösning:** 
- Kontrollera att alla filer finns i repositoryt
- Kontrollera stavningen på filerna (matte-escape.html, inte matte.html)
- Vänta 2-3 minuter efter uppladdning

### Problem: Huvudsidan visar inte
**Lösning:**
- Kontrollera att filen heter EXAKT `index.html` (små bokstäver)
- Kontrollera att GitHub Pages är aktiverat
- Prova att besöka sidan i inkognitoläge (Ctrl+Shift+N)

### Problem: Länkar fungerar inte
**Lösning:**
- Öppna `index.html` i en texteditor
- Kontrollera att länkarna är:
  - `href="matte-escape.html"` (för matematik)
  - `href="english-escape.html"` (för engelska)

### Problem: Sidan laddar långsamt
**Lösning:**
- Detta är normalt första gången
- GitHub Pages kan ta 1-3 minuter att aktivera
- Uppdatera sidan (F5)

---

## 📱 DELA MED ELEVER

### Skicka länken:
När allt fungerar, dela din GitHub Pages-länk:
```
https://dittanvändarnamn.github.io/escape-room-academy/
```

### Tips för klassrummet:
1. **Projektor:** Visa startsidan på projektorn
2. **QR-kod:** Skapa en QR-kod av länken på [qr-code-generator.com](https://www.qr-code-generator.com/)
3. **Google Classroom:** Lägg till som "länk" i ett uppdrag
4. **Skolans lärplattform:** Bädda in länken

---

## 🎨 ANPASSNING (Avancerat)

### Ändra färger:
Öppna filerna i en texteditor (Notepad, VS Code, etc.)
Sök efter färgkoder som:
- `#667eea` (lila)
- `#764ba2` (mörklila)
- `#f093fb` (rosa)

### Lägga till eget escape room:
1. Kopiera `matte-escape.html`
2. Döp om till t.ex. `svenska-escape.html`
3. Redigera innehållet
4. Uppdatera länken i `index.html`

---

## 📊 STATISTIK & TRACKING (Framtida feature)

Vill du se hur många som använder dina escape rooms?

### Google Analytics (Gratis):
1. Skapa konto på [analytics.google.com](https://analytics.google.com)
2. Få en tracking-kod
3. Lägg till koden i `<head>`-sektionen i alla HTML-filer

### Enkel lösning:
Använd GitHub's inbyggda statistik:
- Gå till ditt repository
- Klicka på "Insights" → "Traffic"
- Se antal besökare

---

## 🎓 ANVÄNDNING I KLASSRUMMET

### Förslag på upplägg:

#### Lektion 1: Introduktion
- Visa startsidan
- Låt eleverna välja escape room
- Jobba individuellt eller i par
- Tid: 30-45 minuter

#### Lektion 2: Tävling
- Dela klassen i grupper
- Vilken grupp klarar escape room snabbast?
- Diskutera strategier efteråt
- Tid: 45 minuter

#### Hemuppgift:
- Ge länken som hemläxa
- Eleverna spelar hemma
- Screenshot av slutskärmen som bevis
- Diskussion nästa lektion

### Bedömning:
- **Formativ:** Observera elevernas problemlösning
- **Summativ:** Använd som repetition innan prov
- **Självskattning:** Låt eleverna reflektera över sina svar

---

## 🤝 SUPPORT & HJÄLP

### Om något inte fungerar:
1. **Läs felsökningen ovan**
2. **Kontrollera checklistan**
3. **Öppna en issue på GitHub** (om du använder GitHub)
4. **Fråga en kollega** som är teknikkunnig

### Resurser:
- [GitHub Pages dokumentation](https://docs.github.com/en/pages)
- [HTML grundkurs](https://www.w3schools.com/html/)
- [GitHub guide för lärare](https://education.github.com/)

---

## 📝 LICENS

Alla filer är fria att:
- ✅ Använda i undervisning
- ✅ Dela med kollegor
- ✅ Modifiera och anpassa
- ✅ Använda kommersiellt

**Krav:** Ingen! Men uppskattning om du:
- ⭐ Stjärnmarkerar projektet på GitHub
- 💬 Delar feedback
- 🤝 Bidrar med förbättringar

---

## 🎉 LYCKA TILL!

Du är nu redo att använda Escape Room Academy!

**Snabbstart:**
1. Ladda upp filerna till GitHub
2. Aktivera GitHub Pages
3. Dela länken med eleverna
4. Njut av engagerade elever! 🚀

---

## 📞 VANLIGA FRÅGOR

**Q: Kostar GitHub något?**  
A: Nej, GitHub är gratis för publika repositories och GitHub Pages.

**Q: Kan eleverna spela utan internet?**  
A: Ja, om du laddar ner filerna lokalt. Men GitHub Pages kräver internet.

**Q: Kan jag ändra texterna?**  
A: Ja! Öppna HTML-filerna i en texteditor och redigera.

**Q: Funkar det på mobil?**  
A: Ja, alla escape rooms är responsiva och fungerar på mobil, surfplatta och dator.

**Q: Kan jag lägga till fler escape rooms?**  
A: Absolut! Skapa nya HTML-filer och lägg till kort i index.html.

**Q: Hur tar jag bort "Kommer snart" från Svenska/SO?**  
A: När du har skapat escape roomsen, ta bort klassen `coming-soon` från kortet i index.html.

---

**Skapad med ❤️ för att göra lärande roligt!**

Version 1.0 | Uppdaterad: 2024-02-05
