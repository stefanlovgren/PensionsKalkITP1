# PensionsKalkITP1
Verktyg och beräkningar gällande svensk pension, med särskilt fokus på tjänstepensionen ITP1 och löneväxling.

**🌐 Testa verktygen direkt i webbläsaren: [PensionsKalkITP1 på GitHub Pages](https://stefanlovgren.github.io/PensionsKalkITP1/index.html)**

## Kom igång
Det krävs ingen server eller installation för att köra kalkylatorerna. Allt körs lokalt på din egen dator.

1. Ladda ner filerna till din dator.
2. Öppna filen `index.html` i din webbläsare (t.ex. Chrome, Firefox eller Safari) för att se översiktsmenyn.
3. Klicka dig vidare till det verktyg du vill använda.

*Tips: All data du matar in sparas endast lokalt i din egen webbläsares `localStorage`. Inga personuppgifter skickas över internet.*

## Verktygsguide

### 1. Ekonomisk Prognos (`FinancialProjection.html`)
Detta verktyg hjälper dig att visualisera en tidslinje över din ekonomi fram till din valda slutålder.
* **Hur man använder:** Mata in ditt födelsedatum, bruttolön, eventuell löneväxling, avgångsvederlag och din dagliga levnadskostnad (använd gärna **🖩 Beräkna** för att bryta ner månadskostnader per kategori eller ladda en färdig profil). Lägg vid behov till egna datum under **✎ Redigera händelser**.
* **Resultat:** Visar kostnad per dag/månad/år samt en detaljerad tabell över milstolpar i framtiden (födelsedagar, nyår, kostnadsintervall, när avgångsvederlaget tar slut och viktiga pensionsåldrar). Du ser hur inkomst (brutto/netto), levnadskostnader, kvarvarande avgångsvederlag och pensionsavsättningar ackumuleras över tid.

### 2. Kalkylator för Löneväxling (`Lonevaxling.html`)
Ett verktyg för att räkna ut den förväntade skattevinsten när du väljer att löneväxla.
* **Hur man använder:** Fyll i din nuvarande bruttolön, hur stor summa du vill växla varje månad, din nuvarande och framtida skattesats, samt arbetsgivarens tillägg (oftast runt 6 %).
* **Resultat:** Kalkylatorn jämför "netto i handen idag" mot "netto i pensionen framöver" och visar den förväntade vinsten. Den varnar också automatiskt ifall din lön efter växling skulle hamna under taket för allmän pension.

### 3. Fördelning av Pensionsavsättningar (`PensionAllocation.html`)
Ett detaljerat kvitto på vart dina pensionspengar faktiskt tar vägen varje månad och år.
* **Hur man använder:** Fyll i inkomstår, din bruttolön och eventuell löneväxling. Du kan även slå på funktionen för att se hur löneväxling påverkar och kompenserar avsättningarna till ITP1.
* **Resultat:** Bryter ner dina avsättningar i Allmän pension (Inkomstpension och PPM), Tjänstepension (ITP1 – Bas, Topp och Flex) och Löneväxling, samt visar hur stor andel av bruttolönen som totalt avsätts till pension.

### 4. Hushållsbudget (`HouseholdBudget.html`)
Få överblick över hushållets månadsekonomi.
* **Hur man använder:** Dela upp utgifter i egna kategorier med underposter (med valfri period: månad, kvartal, halvår eller år), ange nettoinkomster och välj visningsvaluta.
* **Resultat:** Följ saldot i realtid. Budgeten sparas lokalt och du kan växla mellan flera sparade varianter, utgå från färdiga mallar eller exportera/importera dina budgetar.

### 5. Interaktiv Skatte- & Avdragskalkylator (`SkatteAvdragEffekt.html`)
Visuell jämförelse av grundavdrag och jobbskatteavdrag (2026).
* **Hur man använder:** Välj inkomsttyp (lön eller pension), ålder och månadslön samt justera kommunalskatt, prisbasbelopp och skiktgräns för statlig skatt.
* **Resultat:** Visar effektiv skatt, marginalskatt och skattelättnader beroende på ålder och inkomst med hjälp av interaktiva grafer.

### 6. Skattetabell Visualizer (`SkattetabellVisualizer.html`)
Interaktiv visualisering av Skatteverkets allmänna skattetabeller.
* **Hur man använder:** Välj skattetabell (29–42), inkomstintervall och vilka kolumner (1–6, t.ex. lön, pension under/över 66 år) som ska jämföras, samt om grafen ska visa skatt i procent eller kronor.
* **Resultat:** Jämför skatteuttaget visuellt över olika inkomstnivåer och ålderskategorier direkt mot Skatteverkets tabellvärden.

### 7. Pensionssimulator (ITP 1) – Uttagsplanerare (`PensionsSimulator.html`)
Simulera din framtida månadspension från allmän pension (inkomstpension & PPM) och premiebestämd tjänstepension (ITP 1 / ITPK) i dagens penningvärde.
* **Hur man använder:** Ställ in totalt kapital vid uttag (eller använd **🖩 Beräkna** för att uppskatta framtida slutkapital utifrån nuvarande kapital, lön, löneväxling, kvarvarande arbetsår och avkastning), fördelning mellan pensionsdelarna, pensionsålder vid start (med Pensionsmyndighetens delningstal) samt årlig real avkastning och uttagstid för tjänstepensionen.
* **Resultat:** Visar månadspension brutto och netto efter skatt (Göteborg tabell 33 före/efter 68 år samt SINK 20 %) över fyra uttagsfaser med interaktiv graf och tabell i dagens köpkraft.

## Spara och flytta data
Samtliga verktyg sparar dina inställningar automatiskt i webbläsarens `localStorage`. Verktygen för **Ekonomisk Prognos**, **Löneväxling**, **Pensionsfördelning** och **Hushållsbudget** har dessutom knappar för att **Exportera** och **Importera** inställningar som en `.json`-fil, så att du enkelt kan säkerhetskopiera eller flytta dina beräkningar mellan olika datorer och webbläsare.
