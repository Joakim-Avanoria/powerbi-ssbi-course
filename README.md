# Power BI / SSBI Course Materials

Det här repot innehåller kursmaterial till **Business Intelligence / SSBI med fokus på Power BI**.  
Varje video i kursen har en egen **.pbix**-fil så att du kan öppna exakt samma läge som i genomgången.

---

## Struktur

- `/WWI/` – övningsdata (CSV/Excel) som används i kursen  
- `Video_XX_*.pbix` – en PBIX per video/avsnitt (färdigt läge efter videon)

Exempel:
- `PowerQuery.pbix`
- `DataModeling.pbix`

> Tips: Ladda ner repot lokalt (ZIP eller git clone). Öppna inte PBIX direkt i webbläsaren.

---

## Förkrav

- **Power BI Desktop (Windows)** – rekommenderar senaste versionen  
- Tillräckliga rättigheter att läsa filer lokalt (du behöver packa upp repot på din dator)

**Mac:** Power BI Desktop finns inte native för macOS. Använd i så fall t.ex. VM/Parallels eller en Windows-miljö via remote (om du har tillgång till det).

---

## Kom igång

1. Klicka på **Code → Download ZIP** (eller klona repot)
2. Packa upp ZIP-filen lokalt
3. Öppna önskad `Video_XX_*.pbix` i Power BI Desktop

---

## Om du får fel på datakälla (vanligt)

Om Power BI inte hittar datafilerna (t.ex. efter att du laddat ner ZIP och packat upp):

Kursen använder en parameter (`FolderPath`):
- Öppna PBIX-filen i Power BI Desktop
- Gå till **Home → Transform data**
- Gå till **Manage Parameters**
- Uppdatera `FolderPath` till din lokala sökväg till mappen `/WWI/`

---

## Om datan

Datan i `/WWI/` är **övningsdata** som används i utbildningssyfte. Den är inte kopplad till verkliga kundsystem och ska inte tolkas som “riktig” affärsdata.

Datasetet bygger på **Microsofts exempeldata** (WWI / *Wide World Importers*) och kan vara justerat/förenklat för kursen.

---

## Viktigt

- Ladda inte upp egna filer med konfidentiell information eller personuppgifter till GitHub (t.ex. i en fork).
- Om du delar ditt arbete: tänk på att PBIX-filer kan innehålla kopierad data om du importerat egna källor.

---

## Licens

Det här repot är licensierat under **MIT License** (se `LICENSE`).  
Materialet tillhandahålls i befintligt skick (“as-is”).
