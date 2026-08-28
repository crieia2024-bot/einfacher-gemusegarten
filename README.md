# Verkaufsseite — Lebendiger Gemüsegarten (Kanal Einfacher Gemüsegarten)

Statische Seite in einer einzigen HTML-Datei. Ohne Build, ohne Frameworks und ohne externe Abhängigkeiten.

## Wichtige Links

- **Veröffentlichte Website (Vercel):** https://einfacher-gemusegarten.vercel.app
- **GitHub Repository:** https://github.com/crieia2024-bot/einfacher-gemusegarten
- **Checkout Hotmart:** `https://pay.hotmart.com/T107366167D?checkoutMode=2`

---

## Preis anpassen

Der Preis (9,99 €) lässt sich direkt in `index.html` anpassen:

```bash
grep -Fn '9,99 €' index.html
```

---

## Lokale Vorschau

```bash
cd /Users/juananjos/Documents/pagina-vendas-de && python3 -m http.server 4400
```
Öffne `http://localhost:4400` im Browser mit aktivierter mobiler Ansicht (DevTools).

---

## Veröffentlichung / Aktualisierung auf Vercel

```bash
cd /Users/juananjos/Documents/pagina-vendas-de
git add .
git commit -m "Aktualisierung"
git push
```
