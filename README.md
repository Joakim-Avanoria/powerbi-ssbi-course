# Power BI / SSBI Course Materials

Det här repot innehåller kursmaterial till **Business Intelligence / SSBI med fokus på Power BI**.
Varje video i kursen har en egen **.pbix**-fil så att du kan öppna exakt samma läge som i genomgången.

## Struktur
- `/WWI/` – övningsdata (CSV/Excel) som används i kursen
- `Video_XX_*.pbix` – en PBIX per video/avsnitt (färdigt läge efter videon)

Exempel:
- `PowerQuery.pbix`
- `DataModeling.pbix`

## Förkrav
- **Power BI Desktop (Windows)** – rekommenderar senaste versionen
- Tillräckliga rättigheter att läsa filer lokalt (du behöver packa upp repot på din dator)

## Kom igång
1. Klicka på **Code → Download ZIP** (eller klona repot)
2. Packa upp ZIP-filen lokalt
3. Öppna önskad `Video_XX_*.pbix` i Power BI Desktop

### Om du får fel på datakälla (vanligt)
Om Power BI inte hittar datafilerna:
- Gå till **Transform data**
- Välj **Data source settings** (under Home)
- Ändra sökvägen så att den pekar på din lokala mapp för `/WWI/`

(Kursen använder en parameter som heter `FolderPath`: ändra den till din lokala sökväg.)

## Om datan
Datan i `/WWI/` är **övningsdata** som används i utbildningssyfte.
Den är inte kopplad till verkliga kundsystem och ska inte tolkas som “riktig” affärsdata.

## Viktigt
Ladda inte upp egna filer med konfidentiell information eller personuppgifter till GitHub (t.ex. i en fork).

## Licens / användning
Materialet är avsett för kursdeltagare och utbildningssyfte.
