# Verkaufsseite — Lebendiger Gemüsegarten (Kanal Einfacher Gemüsegarten)

Statische Seite in einer einzigen HTML-Datei. Ohne Build, ohne Frameworks und ohne externe Abhängigkeiten.

## Wichtige Links

- **Verkaufsseite:** `index.html`
- **Checkout Hotmart:** `https://pay.hotmart.com/V107356357I?checkoutMode=2`

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

## Veröffentlichung auf Vercel

```bash
cd /Users/juananjos/Documents/pagina-vendas-de
git init
git add .
git commit -m "Verkaufsseite Lebendiger Gemüsegarten"
gh repo create einfacher-gemusegarten --public --source=. --push
vercel --prod --yes
```
