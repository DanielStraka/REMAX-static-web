# REMAX-static-web

Semestrální práce pro předmět webové technologie.

Statický web realitní kanceláře REMAX vytvořený v čistém HTML a CSS bez použití frameworků.

## Stránky

| Soubor | Popis |
|---|---|
| `index.html` | Hlavní stránka — banner, statistiky, doporučené nemovitosti, sekce O nás, hodnocení zákazníků, Hall of Fame |
| `buy.html` | Přehled nemovitostí k prodeji s filtrováním podle kategorie |
| `sell.html` | Formulář pro prodej nemovitosti (dvoustupňový průvodce) |
| `offices.html` | Přehled poboček s adresami a kontaktními údaji |
| `kontakt.html` | Kontaktní stránka s přehledem managementu |

## Struktura projektu

```
REMAX-static-web/
├── index.html
├── buy.html
├── sell.html
├── offices.html
├── kontakt.html
├── style.css          # Globální styly (header, footer, index)
├── buy.css
├── sell.css
├── offices.css
├── kontakt.css
├── print.css          # Tiskové styly
├── script.js
└── images/
```

## Technologie

- **HTML5**
- **CSS3** — grid, flexbox, media queries, animace
- Bez JavaScriptových frameworků — `script.js` zajišťuje pouze přepínání kroků ve formuláři na sell.html

## Responzivita

Web používá dva breakpointy:
- **Desktop:** `min-width: 801px` — plné rozložení s gridy
- **Mobil:** `max-width: 800px` — zjednodušené jednostoupancové rozložení

Stránka `offices.html` má vlastní breakpointy:
- **Velký desktop:** `min-width: 1301px` — karty poboček s obrázky
- **Menší obrazovky:** `max-width: 1300px` — obrázky skryty, pouze textový obsah

## Barevná paleta

| Barva | Hex | Použití |
|---|---|---|
| Modrá | `#004fac` | Primární barva, texty, pozadí |
| Červená | `#DC143C` | Akcenty, tlačítka, zvýraznění |
| Světle modrá | `#006ce7` | Sekundární modrá |
| Bílá | `#FAF9F6` | Pozadí, texty na tmavém pozadí |

