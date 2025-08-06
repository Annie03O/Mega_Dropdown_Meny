# Dropdown-meny (utan JavaScript)

Detta är ett frontendtest för en praktikplats. Uppgiften gick ut på att återskapa en dropdown-funktion liknande den på [ASICS produktsida](https://www.asics.com/se/sv-se/metaspeed-edge-paris/p/1013A124-400.html), med följande krav:

## ✅ Krav

- Enbart HTML och CSS (ingen JavaScript)
- Klickbar dropdown (ej hover)
- CSS-animation för mjuk öppning/stängning
- Fyra flikar med varierande text
- Den sista fliken ska visa en stor bild
- Alla klassnamn ska vara på svenska
- Endast en meny ska vara öppen åt gången

## 🛠️ Lösning

Dropdown-funktionen är byggd med:
- `<input type="radio">` + `<label>` för klickbar logik
- `:checked`-selektor i CSS för att visa innehåll
- `max-height` + `opacity` + `transition` för mjuk animation
- Flexbox för layout
- Svenskspråkiga klassnamn i både HTML och CSS

## 📁 Filer

| Filnamn            | Beskrivning                      |
|--------------------|----------------------------------|
| `drop-down-menu.html` | Huvudfilen med menyer och struktur |
| `style.css`         | CSS-styling och animationer     |
| `collage.png`       | Bild som används i sista fliken |

## 🖥️ Så kör du

1. Klona eller ladda ner repot
2. Öppna `drop-down-menu.html` i valfri webbläsare

> 💡 Inga externa beroenden krävs – allt fungerar offline.

## 👩‍💻 Utvecklare

**Annie Olofsson**  
Frontendutvecklare under utbildning  
📧 annielolofsson@gmail.com  

