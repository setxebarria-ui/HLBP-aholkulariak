# 🎯 HLBP - Sistema Profesionala

**Aholkularien eskuhartzeak kudeatzeko aplikazioa — 93 aholkulari, 810 ikastetxe**

## 📱 Ezaugarriak

### ✅ Aholkularien Aplikazioa (AHL001-AHL093)
- Login segurua (kodigo bakoitzari)
- Dashboard pertsonalizatua (bere ikastetxeak bakarrik)
- Eskuhartzeen erregistroa, motaren araberako eremuekin:
  - Ebaluazio psikopedagogikoak (AGH / AEN)
  - Txosten psikopedagogikoak
  - Eskolatze proposamen-txostenak
  - CNE-en kudeaketa
  - Jokabide kasuak
  - ZIP / LIP gelako eginbeharrak
  - Ikaslearen eskuhartze plana
- Egoera: Eginda / Egin gabe
- Historiala eta zentroetako erregistroa

### ⚙️ Administratzaileak
- **MASTER**: 93 aholkularien panel orokorra — gehitu, aldatu, baja eman
- **ADMIN001-ADMIN018**: Berritzegune bakoitzaren jarraipena

## 🔐 Segurtasuna eta datu babesa

- **Izen errealik EZ kodean**: aholkulariak kodigoz identifikatzen dira
- Izenak `data.js` fitxategian daude — **fitxategi hori ez dago GitHub-en** (`.gitignore`)
- Bertsio publikoak `data.example.js` erabiltzen du ("Aholkulari 1", "Aholkulari 2"...)
- Ikasleak ID kodez erregistratzen dira, inoiz ez izen-abizenez
- Datuak nabigatzailean gordetzen dira (localStorage), ez zerbitzarietan

### Benetako izenak konfiguratzeko (lokala bakarrik):
1. Kopiatu `data.example.js` → `data.js`
2. Aldatu izen generikoak benetakoengatik
3. `data.js` ez da inoiz GitHub-era igoko (`.gitignore`-k blokeatzen du)

## 🚀 Nola Erabili

### Lokalean:
1. Ireki `HLBP_Sistema_Profesional.html` nabigatzailean
2. Edo zerbitzari batekin: `npx http-server . -p 8000`

## 💾 Datuak

- **Gordetzea**: nabigatzailean (localStorage)
- **Esportazioa**: CSV (Excel-erako) eta JSON backup-a

## 🛠️ Teknologia

- HTML5 + CSS3 + JavaScript (fitxategi bakarra + datu-fitxategiak)
- LocalStorage
- 100% Euskaraz

## 📝 Lizentzia

MIT
