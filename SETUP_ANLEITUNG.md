# 🕷️ Spaiderman Blog — Setup Anleitung
## Von 0 auf GitHub Pages in 15 Minuten

---

## ✅ Schritt 1 — GitHub Repository erstellen

1. Gehe zu https://github.com/new
2. **Repository Name:** `24spaiderman7.github.io` (EXAKT so — mit deinem GitHub-Username)
   - Beispiel: wenn dein GitHub-Name `JanSpaiderman` ist → `JanSpaiderman.github.io`
3. **Visibility:** Public ← MUSS public sein für kostenlose GitHub Pages
4. Klick "Create repository"

---

## ✅ Schritt 2 — _config.yml anpassen

Öffne `_config.yml` und ändere:
```yaml
url: "https://DEIN_GITHUB_USERNAME.github.io"
```

---

## ✅ Schritt 3 — Dateien hochladen

**Option A: Browser-Upload (einfachster Weg)**
1. Gehe zu deinem Repository auf GitHub
2. Klick "Add file" → "Upload files"
3. Alle Dateien aus diesem Ordner hochladen (ausser SETUP_ANLEITUNG.md)
4. Klick "Commit changes"

**Option B: Git (schneller für spätere Updates)**
```bash
git init
git add .
git commit -m "🕷️ Spaiderman Blog Launch"
git remote add origin https://github.com/DEIN_USERNAME/DEIN_USERNAME.github.io.git
git push -u origin main
```

---

## ✅ Schritt 4 — GitHub Pages aktivieren

1. Gehe zu Repository Settings → Pages
2. Source: "Deploy from branch"
3. Branch: "main" / "(root)"
4. Save

🕐 Warte 2-5 Minuten → Blog ist live unter `https://DEIN_USERNAME.github.io`

---

## ✅ Schritt 5 — Affiliate-Accounts eröffnen

**Priorität 1: Höchste Provision**

### Ledger Affiliate (10-15% pro Wallet ~149€ = ~15-22€/Verkauf)
- https://affiliate.ledger.com
- Kostenlos anmelden
- Approval: meist 1-3 Tage

### TradingView Partner (30% recurring)
- https://www.tradingview.com/partner-program/
- Beste recurring Commission im Crypto-Space

### NordVPN (40% + recurring)
- https://nordvpn.com/affiliates/
- Sehr gute Auszahlungen, schnelle Approval

### Koinly (20% recurring)
- https://koinly.io/affiliates/
- Crypto-Steuern: Jeder mit Crypto braucht das

### Trezor (12-15%)
- https://affil.trezor.io/signup
- Gute Alternative zu Ledger

### Amazon Associates (1-8%) ← Optional
- https://affiliate-program.amazon.de
- Für sonstige Crypto-Bücher, Hardware etc.
- Niedrigste Provision → letzte Priorität

---

## ✅ Schritt 6 — Affiliate Links eintragen

Öffne `_config.yml` und ersetze alle `DEIN_XYZ_CODE` mit deinen echten Affiliate-Links:

```yaml
affiliate:
  ledger:     "https://shop.ledger.com/?r=DEIN_CODE"
  trezor:     "https://affil.trezor.io/DEIN_CODE"
  koinly:     "https://koinly.io/?via=DEIN_CODE"
  tradingview: "https://www.tradingview.com/?aff_id=DEIN_CODE"
  nordvpn:    "https://nordvpn.com/DEIN_CODE"
```

---

## ✅ Schritt 7 — Optional: Eigene Domain

**Wenn du spaiderman.de oder ähnliches willst:**
1. Domain kaufen (z.B. Strato, IONOS — ca. 10€/Jahr für .de)
2. In GitHub Pages Settings → Custom domain eintragen
3. DNS beim Domain-Anbieter: CNAME auf `DEIN_USERNAME.github.io`

Ohne Domain läuft der Blog gratis unter `username.github.io` — funktioniert für SEO genauso.

---

## 📈 Content-Plan: 2 Artikel/Woche

### Bereits fertig (sofort live):
- ✅ "Die 3 besten Crypto Hardware Wallets 2026"
- ✅ "5 KI-Tools die jeder Crypto Trader braucht"

### Nächste Artikel (Copy-Paste aus diesem System):
**Woche 1:**
- "Bitcoin in Deutschland steuerfrei verkaufen — Der komplette Guide 2026"
- "Ledger Nano X Einrichtung — Schritt für Schritt 2026"

**Woche 2:**
- "Beste Crypto-Exchanges für Deutsche 2026 — Vergleich"
- "DeFi Steuern Deutschland 2026 — Koinly vs CoinLedger"

**Woche 3:**
- "TradingView vs CoinMarketCap — Was brauche ich wirklich?"
- "Crypto sicher verwahren — Komplettanleitung 2026"

---

## 💰 Realistisches Einkommenspotential

| Szenario | Monatliche Besucher | Conversion | Einnahmen |
|----------|---------------------|------------|-----------|
| Monat 1-3 | 100-500 | 0.5% | ~15-50€ |
| Monat 4-6 | 500-2000 | 1% | ~50-200€ |
| Monat 7-12 | 2000-8000 | 1.5% | ~200-600€ |
| Jahr 2 | 8000-20000 | 2% | ~600-2000€ |

**Wichtig:** SEO braucht 3-6 Monate bis Google den Blog rankt.
Die ersten Monate passiert wenig — dann wächst es exponentiell.

---

## 🕷️ MiloZ schreibt Artikel automatisch

MiloZ kann dir jeden Montag und Donnerstag einen neuen Artikel vorschlagen und ausschreiben.

**Template für MiloZ:**
```
Schreib einen SEO-optimierten Blog-Artikel für Spaiderman.blog über:
[THEMA]
- Jekyll Markdown Format
- Produkt-Cards mit Affiliate-Link-Placeholder
- Spaiderman-Style Kommentare
- Mind. 800 Wörter
- Meta-Title und Description für SEO
```

---

## ⚠️ Rechtliches (wichtig!)

1. **Affiliate-Disclaimer:** Ist bereits im Footer + Artikel eingebaut ✅
2. **Impressum:** Für deutsche Blogs Pflicht — füge eine /impressum Seite hinzu
3. **Datenschutz:** GitHub Pages sammelt keine Daten (DSGVO-konform)
4. **Google Analytics:** Optional — kann datenschutzkonform mit Matomo ersetzt werden

---

## 🚀 Done!

Dein Blog läuft. Artikel sind live. Affiliate-Links verdienen.
Jetzt Schritt für Schritt die Affiliate-Konten beantragen und Links eintragen.

**Fragen? MiloZ hilft.**
