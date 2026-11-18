# Style-guide – Záhradníctvo Zelený kút

## Zadanie
Podľa `text.txt` vytvor vlastné `index.html` a `assets/css/style.css`.

Musíš použiť:
- [ ] sémantické HTML (`header`, `nav`, `main`, `section`, `article`, `footer`)
- [ ] CSS premenné v `:root` (farby z tabuľky nižšie)
- [ ] Google Fonts cez `@import` (nadpisy: Cormorant Garamond, text: Work Sans)
- [ ] **flexbox** aj **grid**
- [ ] mobile first: základ je pre mobil, ďalej len `@media (min-width: ...)`
- [ ] BEM názvy tried (napr. `hlavicka__logo`)
- [ ] `:hover` na odkazoch a tlačidlách
- [ ] žiadny JavaScript

## Farby
| Premenná | Hodnota | Použitie |
|---|---|---|
| `--les` | `oklch(38% 0.07 150)` | tmavozelená – hero, pätička |
| `--listy` | `oklch(65% 0.14 140)` | svetlozelená – akcent |
| `--hlina` | `hsl(25, 35%, 30%)` | hnedá – nadpisy |
| `--svetla` | `hsl(90, 30%, 96%)` | pozadie stránky |
| `--slnko` | `oklch(82% 0.15 85)` | žltá – tlačidlá |

## Fonty

- Nadpisy a logo: **Cormorant Garamond**
- Text: **Work Sans**

## Breakpointy
| Zariadenie | Šírka | Rozloženie |
|---|---|---|
| Mobil | do 599px (základ) | všetko pod sebou, hlavička vycentrovaná |
| Tablet | od 600px | služby sa zalamujú (flex), kroky pod sebou |
| Desktop | od 960px | hlavička v 3 stĺpcoch (menu | logo | odkaz), hero s ikonou, kroky v 3 stĺpcoch |

## Odsadenia
- Bočné odsadenie sekcií: `5%` (na desktope môže byť viac, napr. `8%` alebo `10%`)
- Vertikálne odsadenie sekcií: `3rem` až `5rem`


## Ikonky

<svg viewBox="0 0 24 24" aria-hidden="true" focusable="false"><path d="M13.5 21v-8.2h2.8l.4-3.2h-3.2v-2c0-.9.3-1.6 1.6-1.6h1.7V3.1c-.3 0-1.3-.1-2.5-.1-2.5 0-4.2 1.5-4.2 4.3v2.3H7.3v3.2h2.8V21h3.4Z"/></svg> 

<svg viewBox="0 0 24 24" aria-hidden="true" focusable="false"><rect x="3" y="3" width="18" height="18" rx="5"/><circle cx="12" cy="12" r="4"/><circle class="pata__bodka" cx="17.5" cy="6.8" r="1"/></svg>