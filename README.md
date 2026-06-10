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
Detta verktyg hjälper dig att visualisera en tidslinje över din ekonomi fram till pensionen.
* **Hur man använder:** Mata in ditt födelsedatum, bruttolön, löneväxling och din dagliga levnadskostnad (använd gärna knappen för budgetkalkylatorn om du vill bryta ner dina utgifter). 
* **Resultat:** Ger dig en detaljerad tabell över milstolpar i framtiden (som t.ex. hur länge ett avgångsvederlag räcker och viktiga åldrar). Du ser hur din inkomst, dina kostnader och dina pensionsavsättningar ackumuleras över tid.

### 2. Kalkylator för Löneväxling (`Lonevaxling.html`)
Ett verktyg för att räkna ut den garanterade skattevinsten när du väljer att löneväxla.
* **Hur man använder:** Fyll i din nuvarande bruttolön, hur stor summa du vill växla varje månad, din nuvarande och framtida skattesats, samt arbetsgivarens tillägg (oftast runt 6%).
* **Resultat:** Kalkylatorn jämför "netto i handen idag" mot "netto i pensionen framöver" och visar vinsten. Den varnar också automatiskt ifall din lön efter växling skulle hamna under taket för allmän pension.

### 3. Fördelning av Pensionsavsättningar (`PensionAllocation.html`)
Ett detaljerat kvitto på vart dina pensionspengar faktiskt tar vägen varje månad och år.
* **Hur man använder:** Fyll i din bruttolön och eventuell löneväxling. Du kan även slå på funktionen för att se hur löneväxling påverkar avsättningarna till ITP1.
* **Resultat:** Bryter ner dina avsättningar i Allmän pension (Inkomstpension och PPM), Tjänstepension (ITP1 - Bas, Topp och Flex) och Löneväxling. Den visar också hur stor procent av din bruttolön som totalt sparas till pensionen.

## Spara och flytta data
Både den ekonomiska prognosen och pensionsfördelningen har knappar för att **Exportera** och **Importera**. Detta laddar ner en liten `.json`-fil till din dator som du senare kan ladda upp igen för att återställa alla dina inmatningar och inställningar ifall du byter dator eller rensar webbläsaren.
