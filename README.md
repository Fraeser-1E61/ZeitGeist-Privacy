# ZeitGeist – Datenschutzerklärung

Statische GitHub Pages Seite für die Datenschutzerklärung der ZeitGeist Android-Apps.

**Live:** https://fraeser-1e61.github.io/ZeitGeist-Privacy

---

## Play Store

URL in der Play Console eintragen unter:  
**App → Store-Eintrag → Datenschutzrichtlinien-URL**

```
https://fraeser-1e61.github.io/ZeitGeist-Privacy
```

> Falls GitHub Pages noch nicht aktiviert: Repo → **Settings → Pages → Deploy from branch main → Save**

---

## Inhalt

| Abschnitt | Thema |
|---|---|
| 01 | Geltungsbereich |
| 02 | Lokale Datenspeicherung |
| 03 | Standortdaten (Opt-In, Nominatim) |
| 04 | Werbung (nur ZeitGeist Free / AdMob) |
| 05 | Export-Einschränkung (nur Free, 30 Tage) |
| 06 | Berechtigungen (Tabelle) |
| 07 | Minderjährige |
| 08 | Kontakt (Vasili Buling, geistzone.dev@gmail.com) |
| 09 | Änderungen |

## Letzte Änderung

2026-03-12 – Full-Version entfernt, 30-Tage-Export-Hinweis ergänzt


### 1. GitHub Repo anlegen
1. GitHub öffnen → **New repository**
2. Name: `zeitgeist-privacy`
3. Sichtbarkeit: **Public** (muss public sein für GitHub Pages)
4. Ohne README anlegen (haben wir schon)

### 2. Diesen Ordner hochladen
```bash
cd /media/DATEN_1TB/Lab/zeitgeist-privacy
git init
git add .
git commit -m "feat: Datenschutzerklärung ZeitGeist"
git remote add origin https://github.com/DEIN-USERNAME/zeitgeist-privacy.git
git push -u origin main
```

### 3. GitHub Pages aktivieren
1. Repo auf GitHub öffnen → **Settings** → **Pages**
2. Source: **Deploy from a branch**
3. Branch: `main` / `/ (root)`
4. **Save** klicken
5. Nach ~1 Minute erreichbar unter:
   `https://DEIN-USERNAME.github.io/zeitgeist-privacy`

---

## ✏️ Vor dem Hochladen anpassen

In `index.html` diese Platzhalter ersetzen:

| Platzhalter | Ersetzen durch |
|---|---|
| `[Entwicklername]` | Dein Name (oder Firmennamen) |
| `[Adresse]` | Deine Adresse (bei privat: nur Stadt + Land reicht) |
| `zeitgeist@example.com` | Deine echte E-Mail-Adresse |

---

## 🔗 URL für Play Store

Nach dem Aktivieren von GitHub Pages trägst du diese URL in der Play Console ein:

```
https://DEIN-USERNAME.github.io/zeitgeist-privacy
```

**Wo in der Play Console:** App → Store-Eintrag → Datenschutzrichtlinien-URL

---

## 📋 Was die Seite abdeckt

- ✅ Lokale Datenspeicherung (keine Cloud)
- ✅ GPS / Standort (Opt-In + Nominatim)
- ✅ OpenStreetMap Datenschutz-Link
- ✅ Google AdMob (nur Basic/Free)
- ✅ Spritpreise-API (nur Full)
- ✅ Android-Berechtigungen erklärt
- ✅ Kinderschutz
- ✅ Kontaktangabe
- ✅ DSGVO-konform für deutsche Apps
