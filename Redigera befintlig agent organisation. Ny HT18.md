## Redigera befintlig: Agent - Organisation

<br/>Lathunden beskriver en ofullständig agentpost för en organisation som behöver kompletteras med ytterligare egenskaper.

För information om katalogiseringsregler som gäller vid auktorisering, se 
[Anvisningar för katalogisering (RDA) - Auktoritetsarbete.](http://www.kb.se/rdakatalogisering/Auktoritetsarbete// "Anvisningar för katalogisering (RDA) - Auktoritetsarbete")

OBS! Glöm inte att redigera Adminmetadata och spara innan vidare navigation i verktyget. Verktyget är fortfarande under utveckling och viss åtskillnad från lathunden, t.ex. avseende ordning på egenskaper kan förekomma.


### Innehåll

| [Adminmetadata](#adminmetadata) | [Agent](#agent) | 
| ------ | ----------- |
| [Skapad av](#skapad-av) | [Namn](#namn) |
| [Katalogiseringsregler](#katalogiseringsregler) | [Namn i två led](#namn-i-två-led) |
| [Katalogiseringsspråk](#katalogiseringsspråk) | [Verksamhtens starttid](#verksamhetens-starttid) |
| [Translitterering](#translitterering) | [Verksamhetens sluttid](#verksamhetens-sluttid) |
| [Poststatus](#poststatus) | [Administrativ historik](#administrativ-historik) |
| [Katalogisatörens anmärkning](#katalogisatörens-anmärkning) | [Variant](#variant) |
| [Konsulterad källa](#konsulterad-källa) | [Se även](#se-även) |
| [Uppdatering av posten](#uppdatering-av-posten) | [Identifikator](#identifikator) |
| [Differentiering av person](#differentiering-av-person) | [Nationalitet](#nationalitet) | |
| [Auktoritetskontrollnivå](#auktoritetskontrollnivå) |
| [**Valbara egenskaper att lägga till i Adminmetadata**](#valbara-egenskaper-att-lägga-till-i-adminmetadata) | [**Valbara egenskaper att lägga till i Agent**](#valbara-egenskaper-att-lägga-till-i-agent) | |
| | [Tid för grundande](#tid-för-grundande) | |
| | [Tid för upphörande](#tid-för-upphörande) | |
| | [Verksamhetsområde](#verksamhetsområde) | |
| | [Språk](#språk) | |
| | [Andra attribut för person- och organisationsnamn](#organisatorisk-tillhörighet) | |
| | [Organisatorisk tillhörighet](#organisatorisk-tillhörighet) | |
 



### Agent

#### Namn
* Namn (name) (110 ‡a)
  <br/>Föredragen namnform som utgör den auktoriserade namnformen.
  <br/>```Exempel: Sveriges släktforskarförbund```

#### Tid för grundande  
* Tid för grundande/Startdatum (establishDate = 046 ‡q)
  <br/>```Exempel: 1886```

#### Verksamhetsområde
* Verksamhetsområde (fieldOfActivity = 372 ‡a ‡2)
  <br/>Ange verksamhetsområde för en organisation vid behov.
  <br/>```Exempel: Släktforskning```
  <br/>Länka i första hand termen från en kontrollerad vokabulär som Svenska ämnesord. 
För att lägga till: Klicka på plusikonen vid egenskapen Verksamhetsområde, välj Allmänt ämnesord som typ vid sökning. Välj önskad term och klicka på plustecknet. (Skapa lokal entitet används endast då det inte finns auktoriserad entitet att länka till).

#### Adminstrativ historik
* Administativ historik (has Historical Data = 678 ‡a)
  <br/>Anmärkning om administrativ historik är obligatorisk uppgift för Organisationer.
  <br/>```Exempel: Riksförbund för svenska släktforskare. Grundat 1886```

#### Variant
* Variant (hasVariant = 410 ‡a ‡b)
  <br/>Här anges variantnamn och alternativa namnformer som stavningsvarianter, förkortningar etc.
  <br/>```Exempel:```
   * ```Släktforskarförbundet```
   * ```Federation of Swedish Genealogical Societies```
   <br/>För att lägga till variantnamn: Klicka på plustecknet vid egenskapen variant, och välj typ t ex organisation. Lägg sedan till de egenskaper som behövs t ex namn.
   
  ```Exempel på organisation i två led:```
  * ```Är del av/Organisation/Namn: Stockholm University samt Namn på underordnad enhet: Centre for Medieval Studies ```
  * ```Är del av/Jurisdiktion/Namn: Sverige samt Namn på underordnad enhet: Smittskyddsinstitutet```
  <br/>För att ange auktoriserad namnform som består av underordnad enhet: klicka på plustecknet vid egenskapen variant, och välj typ t ex organisation. Till organisation läggs, genom att klicka på plustecknet längst ut till höger vid organisation, egenskaperna Är del av samt Namn på underordnad enhet. Vid Är del av skapas lokal entitet Organisation och egenskapen Namn läggs till.
  
  OBS! Varianter ska inte göras till sökbara länkar.

#### Identifikator
* Identifikator (identifiedBy = 024 ‡a ‡2)
  <br/>Identifikator t ex ISNI kan läggas till om tillgänglig. ISNI kan hämtas från t ex VIAF.
  <br/>```Exempel: Värde: 0000000104839039 samt Typanmärkning: ISNI ```
  
#### Nationalitet
* Nationalitet/verksamhetsland (nationality = 043 ‡a)
  <br/>Nationalitet/verksamhetsland för organisationen. Vid behov kan denna ändras eller flera nationaliteter läggas till.
  <br/>```Exempel: e-sw---```
  <br/>För att lägga till: Klicka på plustecknet vid egenskapen Nationalitet/verksamhetsland. Välj Nationalitet som typ vid sökning. Välj önskad nationalitet och klicka på plustecknet. (Skapa lokal entitet används endast då det inte finns auktoriserad entitet att länka till).
  
* Samma sak som (sameAs)
  <br/>```Exempel: resource/auth/394287```
    
  
### Adminmetadata

Information av administrativ karaktär som är väsentlig för auktoriseringen i sig men inte är direkt förknippad med den auktoriserade namnformen.

* Kontrollnummer (controllNumber = 001)
  <br/>LibrisID. Ändras ej.
  
* Skapad av (descriptionCreator = 040 ‡a)
 <br/>Förval: Sigel för skapare av agenten. Ändras ej.
 <br/>```Exempel: S```
      
* Katalogiseringsregler (descriptionConventions = 040 ‡e)
 <br/>Förval: rda. Ändra vid behov.
 <br/>```Exempel: Kod: rda```
 
 * Katalogisatörens anmärkning (cataloguersNote = 667 ‡a)
  <br/>Anmärkningar tänkta för kollegor inom Libriskollektivet. Det kan till exempel vara uppgifter som rör ändring av den auktoriserade namnformen. Motivera gärna ändringen och komplettera alltid med datum/sigel/signatur.
  <br/>```Exempel: Ändrat auktoriserad namnform från Xxx till Yyy 2010-01-03/S/UL/marjan```
  
* Katalogiseringsspråk (descriptionLanguage = 040 ‡b)
 <br/>Förval: language/swe. Ändras ej.
 
* Senast ändrad av (descriptionLastModifier)
 <br/>Förval: Sigel som gjort senaste ändring. Ändras automatiskt vid sparande.
  
* Beskrivningsnivå (encodingLevel = 000)
 <br/>Ändras ej.
 
 * Konverteringsdatum (generationDate = 000)
 <br/>Ändras ej.
 
 * Beskrivningsprocess (generationProcess = 000)
 <br/>Ändras ej.
 
* Marc:headingMain (marc:headingMain = 008/14)
 <br/>Ändras ej.
 
* Typ av auktoritetspost (marc:kindOfRecord = 008/9)
 <br/>Ändras ej.
 
* Auktoritetskontrollnivå (marc:level = 008/33)
  <br/>Kontrollerad/godkänd
  <br/>Om "Preliminär (ej kontrollerad)" ändra till Kontrollerad/godkänd.

* Numrering i serie (marc:numberedSeries = 008/13)
 <br/>Ändras ej.
     
* Differentiering av posten (marc:personalName = 008/32)
  <br/>Ändras ej.
  
* Uppdatering av posten (marc:recordUpdate = 008/31)
  <br/>Ändras ej.
  
* Formatering av icke auktoriserade sökelement (marc:reference = 008/29)
 <br/>Ändras ej. 

* Translitterering (marc:romanization = 008/07)
 <br/>Ändras ej
 
* Geografisk precisering (marc:subdivision = 008/6)
 <br/>Ändras ej.  

* Typ av underindelning (marc:subjectSubdivision = 008/7)
 <br/>Ändras ej.  

* Typ av serie (marc:typeOfSeries = 008/12)
 <br/>Ändras ej.  

* Poststatus (recordStatus = 000)
  <br/>Ändras ej. Vid uppdatering ändras status automatiskt.
  
* Samma sak som (sameAs)
  <br/>```Exempel: auth/394287```.

* Konsulterad källa (sourceConsulted) innehåller Benämning (label = 670 ‡a) samt Uppgift från källa (citationNote = 670 ‡b)
  <br/>Ange källa och vid behov vilken uppgift som hämtats från källan. 
  <br/>Den resurs som föranleder auktoriseringen är en obligatorisk källa.
  <br/>```Exempel: Benämning: Fader okänd / Sveriges släktforskarförbund, 2016```
  <br/>```Exempel: Benämning: Material i Kungliga bibliotekets vardagstryckssamling. Uppgift från källa: Namnformen: Stockholm vatten och avfall```
  <br/>Ytterligare relevanta källor kan vara.
  <br/>```Exempel: Benämning: Wikipedia (Svenska) 2018-04-24. Uppgift från källa: Startår 1886```
  <br/>```Exempel: Benämning: Företagets webbplats 2018-08-17. Uppgift från källa: Datum för namnbyte```
  <br/>OBS! Förkortningen t.p., isbd-interpunktion och parenteser som inte behövs för förståelse/läsbarhet behöver inte anges.
  <br/>För att lägga till: Klicka på +ikonen under konsulterad källa. Välj typ av konsulterad källa i rullmenyn. Vid val av "Källa vid belagd uppgift" finns möjlighet att ange såväl Benämning (källa) som Uppgift hämtad från källa.
  
### Valbara egenskaper att lägga till i Adminmetadata
  
  
### Valbara egenskaper att lägga till i Agent

* Tid för upphörande/Slutdatum (terminateDate = 046 ‡r)
  <br/>```Exempel: 2003```

* Verksamhetens starttid/Startdatum för aktivitetsperiod (activityStartDate, 046 ‡s)
  <br/>```Exempel: 1886```
    
* Verksamhetens sluttid/Slutdatum för aktivitetsperiod (activityEndDate, 046 ‡t)
  <br/>```Exempel: 1999``` 
  
* Se även (seeAlso = 510)
  <br/>Här länkas mot annan agent som hör ihop med organisationen. Det kan t ex vara föregångare eller efterföljare. 
  <br/>```Exempel: Föreningen Emigrantinstitutets vänner```
 <br/>För att lägga till: Klicka på +ikonen under egenskapen Se även, välj typen Organisation i sökrutan till vänster. Sök efter auktoriserad namnform och klicka på Lägg till-rutan till höger. (Finns ingen länkbar organisation behöver en ny skapas som kan länkas. Spara och avsluta innan ny organisation skapas. Använd befintlig mall för Skapa ny: Agent - Organisation).

* Språk (associatedLanguage = 377 ‡a)
  <br/>Ange språk som organisation använder vid behov.
  <br/>```Exempel: Engelska```
  <br/>Klicka på +ikonen under egenskapen Språk. Välj Språk som typ och sök i rutan till vänster. Välj önskat språk och klicka på den gröna Lägg till-rutan till höger. (Skapa lokal entitet används endast då det inte finns auktoriserad entitet att länka till).
    
* Andra attribut för person- och organisationsnamn (marc:hasOtherAttributes = 368 ‡a ‡2)
  <br/>Ange en term för att beskriva typ av organisation om det använts som särskiljande tillägg i den auktoriserade sökingången.
  <br/>```Exempel: Herrgårdar```
  <br/>Länka i första hand termen från en kontrollerad vokabulär som Svenska ämnesord. 
För att lägga till: Klicka på +ikonen under egenskapen Andra attribut för person- och organisationsnamn, välj Allmänt ämnesord som typ och sök i rutan till vänster, välj önskad term och klicka på den gröna Lägg till-rutan till höger. (Skapa lokal entitet används endast då det inte finns auktoriserad entitet att länka till).

Glöm inte att redigera Adminmetadata och spara entiteten innan vidare navigation i verktyget!
