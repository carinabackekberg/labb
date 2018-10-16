UNDER ARBETE 18-10-16 (överflyttad till skarpt 18-10-X)


## Skapa ny: Agent - Person
Lathunden beskriver de egenskaper och klasser som finns representerade i mallen. Om något av inmatningsfälten i mallen inte behövs kan de raderas med hjälp av papperskorgen intill. Ett urval av egenskaper relevanta för person som är möjliga att lägga till men som inte finns i mallen beskrivs i slutet av lathunden. 

För information om katalogiseringsregler som gäller vid auktorisering, se 
[Anvisningar för katalogisering (RDA) - Auktoritetsarbete.](http://www.kb.se/rdakatalogisering/Auktoritetsarbete// "Anvisningar för katalogisering (RDA) - Auktoritetsarbete")

OBS! Var noggrann vid sökning/testlänkning för att säkerställa att auktoriserad namnform inte redan finns. Glöm inte att redigera Adminmetadata och spara innan vidare navigation i verktyget. Verktyget är fortfarande under utveckling och viss åtskillnad från lathunden, t.ex. avseende ordning på egenskaper kan förekomma. 

Exemplet nedan baseras på den auktoriserade namnformen Lagerlöf, Selma, 1858-1940 (i de fall det är möjligt och relevant). Tillägg är fiktiva, enbart för att exemplifiera.


### Innehåll

| [Adminmetadata](#adminmetadata) | [Agent](#agent) | 
| ------ | ----------- |
| [Skapad av](#skapad-av) | [Namn](#namn) |
| [Katalogiseringsregler](#katalogiseringsregler) | [Namn i två led](#namn) |
| [Katalogiseringsspråk](#katalogiseringsregler) | [Verksamhtens starttid](#verksamhetens-starttid) |
| [Translitterering](#translitterering) | [Verksamhetens sluttid](#verksamhetens-sluttid) |
| [Poststatus](#poststatus) | [Administrativ historik](#administrativ-historik) |
| [Katalogisatörens anmärkning](#poststatus) | [Variant](#variant) |
| [Konsulterad källa](#poststatus) | [Se även](#variant) |
| [Uppdatering av posten](#uppdatering-av-posten) | [Identifikator](#identifikator) |
| [Differentiering av person](#differentiering-av-person) | [Nationalitet](#nationalitet) | |
| [Auktoritetskontrollnivå](#differentiering-av-person) | [**Valbara egenskaper att lägga till i Agent**](#nationalitet) |
| [Beskrivningsnivå](#differentiering-av-person) | [Tid för grundande](#tid-for-grundande) | |
| | [Tid för upphörande](#tid-for-grundande) | |
| | [Verksamhetsområde](#tid-for-grundande) | |
| | [Språk](#tid-for-grundande) | |
| | [Andra attribut för person- och organisationsnamn](#tid-for-grundande) | |
| | [Organisatorisk tillhörighet](#tid-for-grundande) | |
 



### Mall för beskrivning av Agent - Person
Beskrivning av agenten som ska auktoriseras. 

* Efternamn (FamilyName = 100 1/- ‡a)
  <br/>Enkelt eller sammansatt släktnamn/efternamn. Föredragen namnform som tillsammans med förnamn utgör den auktoriserade namnformen.
  <br/>```Exempel:```
  * ```Enkelt efternamn: Lagerlöf```
  * ```Sammansatt släktnamn (dubbla efternamn): Lindmark Månsson```
  <br/>Om flera efternamn ska ingå i den auktoriserade namnformen skrivs de direkt efter varandra.

* Förnamn (GivenName = 100 ‡a)
  <br/>Förnamn som tillsammans med efternamn utgör den auktoriserade namnformen. 
  <br/>```Exempel:```
  * ```Enkelt förnamn: Selma```
  * ```Flera förnamn: Helena Johanna```
  <br/>Om flera förnamn ska ingå i den auktoriserade namnformen skrivs de direkt efter varandra.
  
* Födelse- och/eller dödstid (lifeSpan = 100 ‡d)
  <br/>Årtal används i första hand som särskiljande tillägg för personer. 
  <br/>```Exempel:```
  * ```1858-1940```
  * ```1968-```

* Födelsedatum (birthDate = 046 ‡f)
  <br/>Ange fullständigt födelsedatum om uppgiften är känd. I annat fall, ange känd uppgift.
  <br/> ```Exempel:```
  * ```18581120```
  * ```1902```
  
* Dödsdatum (deathDate = 046 ‡g)
  <br/>Ange fullständigt dödsdatum om uppgiften är känd. I annat fall, ange känd uppgift.
  <br/>```Exempel:```
  * ```19400316```
  * ```1977```

* Variant (hasVariant = 400 ‡a ‡d)
  <br/>Här anges variantnamn och alternativa namnformer samt födelse- och/eller dödstid. Hit hör stavningsvaranter, förkortningar, ändringar till följd av namnbyten, hänvisning från det andra ledet av sammansatt efternamn etc. Variantnamn kan t.ex. finnas i referenskällor eller i den bibliografiska informationen. Egenskapen upprepas om flera variantnamn behöver läggas till. 
  <br/>```Exempel:```
  * ```Enkelt efternamn: Lagerlöf```
  <br/>```Förnamn: Selma Ottiliana Lovisa``` 
  <br/>```Födelse- och/eller dödstid: 1858-1940```
  * ```Stvningsvariant på efternamn: Lagerlœf``` 
  <br/>```Förnamn: Selma```
  <br/>```Födelse- och/eller dödstid: 1858-1940```
  * ```Sammansatt släktnamn (dubbla efternamn): Månsson Lindmark```
  <br/>```Förnamn: Helena``` 
  <br/>```Födelse- och/eller dödstid: 1954-```
  <br/>För att lägga till ytterligare Variant: Klicka på +ikonen under egenskapen Variant, och välj typ (Person). Klicka på +ikonen inom den tillagda egenskapen Person, sök efter och lägg till Efternamn, Förnamn, Födelse- och/eller dödstid (ELLER Namn och Födelse- och/eller dödstid)

#### Se även
* Se även (seeAlso = 500 ‡a ‡d)
  <br/>Här länkas se även-hänvisning till en annan auktoriserad namnform, t.ex. till en pseudonym eller då en upphovsperson är verksam under mer än en identitet. T.ex. Smith, Rosamund, 1938- som se-hänvisning från den auktoriserade namnformen för Oates, Joyce Carol, 1938-.
  <br/>```Exempel:``` 
  * ```Efternamn: Smith``` 
  <br/>``` Förnamn: Rosamond``` 
  <br/>```Födelse- och/eller dödstid: 1938-``` 
  <br/>För att lägga till: Klicka på +ikonen under egenskapen Se även, välj typen Person i sökrutan till vänster. Sök efter auktoriserad namnform och klicka på Lägg till-rutan till höger. (Finns ingen länkbar entitet behöver en skapas, dvs. Skapa ny Agent med länkning till den första. Avsluta och spara den ursprungliga först.)

* Verksamhetsområde (fieldOfActivity = 372)
  <br/>Personens verksamhetsområde beskriver vad personen är intresserad av eller ägnar sig åt och det behöver inte ha med yrkesutövning att göra. Hämta i första hand termen från en kontrollerad vokabulär som Svenska ämnesord och länka. 
   <br/>```Exempel: Fågelskådning```
   <br/>För att lägga till: Klicka på +ikonen under egenskapen Verksamhetsområde, välj Allmänt ämnesord som typ och sök i rutan till vänster, välj önskad term och klicka på den gröna Lägg till-rutan till höger. (Skapa lokal entitet används endast då det inte finns auktoriserad entitet att länka till.)

* Har yrke eller sysselsättning (hasOccupation = 374)
   <br/>Ange yrke eller sysselsättning om det behövs för att skilja en person från en annan, t.ex. när en persons födelsetid eller dödstid inte är tillgängligt. Hämta i första hand termen från en kontrollerad vokabulär som Svenska ämnesord och länka.
   <br/>```Exempel:```
   * ```Romanförfattare```
   * ```Översättare```
   <br/>För att lägga till: Klicka på +ikonen under egenskapen Har yrke eller sysselsättning, välj Allmänt ämnesord som typ och sök i rutan till vänster, välj önskad term och klicka på den gröna Lägg till-rutan till höger. (Skapa lokal entitet används endast då det inte finns auktoriserad entitet att länka till.)

#### Identifikator
* Identifikator (identifiedBy = 024 ‡a ‡2)
  <br/>Isni som identifikator är valfri uppgift men önskvärt om tillgänglig (uppgiften hämtas förslagsvis från VIAF). 
  <br/>```Exempel: 0000000121339888 ```
   <br/>För att lägga till: Klicka på +-ikonen under Identifikator, välj typ (ISNI). Klicka på +-ikonen inom Identifikator, sök efter och lägg till Värde.

#### Nationalitet
* Nationalitet/verksamhetsland (nationality = 043)
  <br/>I mallen ligger nationalitetskoden för Sverige (e-sw---) förifylld. Vid behov kan denna raderas. 
  <br/>För att lägga till: Klicka på +ikonen under egenskapen Nationalitet/verksamhetsland. Välj Nationalitet som typ och sök i rutan till vänster. Välj önskad nationalitet och klicka på den gröna Lägg till-rutan till höger. (Skapa lokal entitet används endast då det inte finns auktoriserad entitet att länka till.)

* Biografiska uppgifter (hasBiographicalInformation = 678)
  <br/>Används för att ange biografisk information är information om personens liv eller historia.
  <br/>```Exempel:```
  * ```Skönlitterär författare, nobelpristagare 1909, första kvinnliga ledamot av Svenska akademien 1914.```
  <br/>Lägg till egenskapen genom att klicka på +ikonen i verktygsmenyn. Klicka på +ikonen inom den tillagda egenskapen och välj Benämning där uppgifterna anges.
  
### Adminmetadata
Information av administrativ karaktär som är väsentlig för auktoriseringen i sig men inte är direkt förknippad med den auktoriserade namnformen.

### Kontrollnummer
* Kontrollnummer (controlNumber = 001)
  <br/>Libris-ID. Genereras automatiskt vid sparande. Ändras ej.
  
* Skapad av (descriptionCreator = 040 ‡a)
  <br/>Förval: Inloggad sigel. Ändras ej.<br/>```Exempel: S```
  
* Katalogiseringsregler (descriptionConventions = 040 ‡e)
  <br/>Förval: rda. Ändra vid behov. 
  <br/>```Exempel:```
  * ```Kod: rda```

* Translitterering (marc:romanization = 008/07)
  <br/>Ändras ej.
  
* Typ av auktoritetspost (marc:kindOfRecord = 008/09)
  <br/>Ändras ej.

* Marc:headingMain (008/14)
  <br/>Ändras ej.

* Katalogisatörens anmärkning (cataloguersNote = 667 ‡a)
  <br/>Anmärkningar tänkta för kollegor inom Libriskollektivet. Det är önskvärt att alla nya auktoriserade namnformer kompletteras med datum/sigel/signatur. I övrigt kan det t.ex. vara uppgifter som rör ändring av den auktoriserade namnformen. Motivera gärna ändringen och komplettera alltid med datum/sigel/signatur. 
  <br/>```Exempel:``` 
  * ```2018-08-27 S/MSS/evaann```
  * ```Författaren vill inte ha sitt födelseår kopplat till den auktoriserade namnformen. Enligt e-post 2017-05-12, S/NB/annbjo```

* Konsulterad källa (sourceConsulted) innehåller Benämning (label = 670 ‡a) samt Uppgift från källa (citationNote = 670 ‡b)
  <br/>Ange källa och vid behov vilken uppgift som hämtats från källan. Den resurs som föranleder auktoriseringen är obligatorisk källa. 
  <br/>```Exempel på obligatorisk källa:``` 
  * ```Benämning: Jerusalem / Selma Lagerlöf, 1901 Uppgift från källa: Selma Lagerlöf```
  * ```Benämning: Harry Potter och hemligheternas kammare / J. K. Rowling, 2000 Uppgift från källa: Rowling, J. K.```

  <br/>```Exempel på kompletterande källa:``` 
  * ```Benämning: NE 2018-04-12. Uppgift från källa: Levnadstid 1848-1920```
  * ```Benämning: Wikipedia (svenska) 2018-04-12 Uppgift från källa: Dödstid 1867```
  * ```Benämning: NE 2016-10-01 Uppgift från källa: Fullständigare namnform: Joanne Kathleen```
  * ```Benämning: LC i VIAF 2017-11-21 Uppgift från källa: Fullständigare namnform: Rowling, J. K.```
  <br/>OBS! Förkortningen t.p., isbd-interpunktion och parenteser som inte behövs för förståelse/läsbarhet behöver inte anges.      
  <br/>För att lägga till: Klicka på +ikonen under Konsulterad källa. Välj typ av konsulterad källa i rullmenyn. 
Vid val av "Källa vid belagd uppgift" finns möjlighet att ange såväl Benämning (källa) som Uppgift hämtad från källa.
  
* Poststatus (recordStatus = 000/Leader/)
  <br/>Val i meny. Välj Ny post vid skapande av ny auktoriserad agent. Vid uppdatering ändras status automatiskt.

* Uppdatering av posten (marc:recordUpdate = 008/31)
  <br/>Ändras ej.

* Differentiering av posten (marc:personalName = 008/32)
  <br/>Ändras ej.

* Auktoritetskontrollnivå (marc:level = 008/33)
  <br/>Ändras ej.

* Katalogiseringsspråk (descriptionLanguage = 040 ‡b)
  <br/>Förval: language/swe. Ändras ej.

* Beskrivningsnivå
  <br/>**OBS! Egenskapen måste för närvarande läggas till manuellt EFTER att den nya agenten först har sparats.**
  <br/>För att lägga till: Skapa och spara agenten, klicka på +ikonen i verktygsmenyn, sök efter och lägg till Beskrivningsnivå, välj Fullständig i rullgardinsmenyn.


### Valbara egenskaper relevanta för Agent - Person
Vid behov är det möjligt att lägga till egenskaper som inte ingår i mallen. Nya egenskaper läggs till med hjälp av den runda +ikonen i verktygsmenyn.

* Namn (name = 100 0/- ‡a)
  <br/>Används för namn i rak följd istället för Förnamn och Efternamn. Kan användas i kombination med Förnamn och Efternamn endast för att ange variantnamn.
  <br/>```Exempel:```
  * ```Namn: Bang``` 
  <br/>Som variantnamn till den auktoriserade namnformen Alving, Barbro, 1909-1987
  <br/>För att lägga till: Klicka på +ikonen under egenskapen Se även, välj typen Person i sökrutan till vänster. Sök efter auktoriserad namnform och klicka på Lägg till-rutan till höger. (Finns ingen länkbar entitet behöver en skapas, dvs. Skapa ny Agent med länkning till den första. Avsluta och spara den ursprungliga först.)

* Fullständigare namnform (fullerFormOfName = 100 ‡q och 378)
  <br/>Används för att ange fullständig namnform i de fall då fortkortning används i den auktoriserade namnformen.
  <br/>```Exempel:```
  * ```Efternamn: Smith```
  * <br/>```Förnamn: A. D.```
  * <br/>```Fullständigare namnform: Adam David```

* Titel eller övrig beteckning (marc:titlesAndOtherWordsAssociatedWithAName = 100 ‡c ‡d)
  <br/>Används vid behov som särskiljande tillägg till den auktoriserade namnformen. 
  <br/>```Exempel: påve```
  
* Andra attribut för person- och organisationsnamn (hasOtherAttributes = 368)
  <br/>Används vid behov som särskiljande tillägg för att ange akademiska titlar, kyrkliga ämbeten, militära tjänstegrader (till exempel kapten), hederstitlar etc. Hämta i första hand termen från en kontrollerad vokabulär som Svenska ämnesord.
  <br/>```Exempel: Professorer```

* Ordningstal (marc:numeration = 100 ‡b)
  <br/>Används som särskiljande tillägg till den auktoriserade namnformen för kungligheter samt för påvar, biskopar och andra personer med religiösa yrken.
  <br/>```Exempel:```
  * ```XXII```
  * ```2```
  
#### Glöm inte att redigera Adminmetadata och spara entiteten innan vidare navigation i verktyget!





  
### Adminmetadata

Information av administrativ karaktär som är väsentlig för auktoriseringen i sig men inte är direkt förknippad med den auktoriserade namnformen.

#### Skapad av
* Skapad av (descriptionCreator = 040 ‡a)
 <br/>Förval: inloggad sigel. Ändras ej.
 <br/>```Exempel: library/S```

#### Katalogiseringsregler
* Katalogiseringsregler (descriptionConventions = 040 ‡e)
 <br/>Förval: rda. Ändra vid behov.
 <br/>```Exempel: Kod: rda```

#### Katalogiseringsspråk
* Katalogiseringsspråk (descriptionLanguage = 040 ‡b)
 <br/>```Exempel: Svenska```Ändras ej.

#### Translitterering
* Translitterering (marc:romanization = 008/07)
 <br/>Ändras ej.

#### Poststatus
* Poststatus (recordStatus = = 000)
  <br/>Val i meny. Välj Ny post vid skapande av ny auktoriserad agent. Vid uppdatering ändras status automatiskt.

#### Katalogisatorens anmärkning
* Katalogisatörens anmärkning (cataloguersNote = 667 ‡a)
  <br/>Anmärkningar tänkta för kollegor inom Libriskollektivet. Det kan till exempel vara uppgifter som rör ändring av den auktoriserade namnformen. Motivera gärna ändringen och komplettera alltid med datum/sigel/signatur. Det är önskvärt att alla nya auktoriserade namnformer kompletteras med datum/sigel/signatur. 
  <br/>```Exempel:```
  * ```2018-08-28/S/NB/carbac```
  * ```Ändrat auktoriserad namnform från Xxx till Yyy 2010-01-03/S/UL/marjan```

#### Konsulterad källa
* Konsulterad källa (sourceConsulted) innehåller Benämning (label = 670 ‡a) samt Uppgift från källa (citationNote = 670 ‡b)
  <br/>Ange källa och vid behov vilken uppgift som hämtats från källan. 
  <br/>Den resurs som föranleder auktoriseringen är en obligatorisk källa.
  <br/>```Exempel:```
  * ```Benämning: Fader okänd / Sveriges släktforskarförbund, 2016```
  * ```Benämning: Material i Kungliga bibliotekets vardagstryckssamling. Uppgift från källa: Namnformen: Stockholm vatten och avfall```
  
   Ytterligare relevanta källor kan vara.
   <br/>```Exempel:```
   * ```Benämning: Wikipedia (Svenska) 2018-04-24. Uppgift från källa: Startår 1886```
   * ```Benämning: Företagets webbplats 2018-08-17. Uppgift från källa: Datum för namnbyte```
  
  OBS! Förkortningen t.p., isbd-interpunktion och parenteser som inte behövs för förståelse/läsbarhet behöver inte anges.
  <br/>För att lägga till: Klicka på plustecknet vid konsulterad källa. Välj typ av konsulterad källa i rullmenyn.
 
 #### Uppdatering av posten
* Uppdatering av posten (marc:recordUpdate = 008/31)
  <br/>Ändras ej.

#### Differentiering av person
* Differentiering av person (marc:personalName = 008/32)
  <br/>Ändras ej.

#### Auktoritetskontrollnivå
* Auktoritetskontrollnivå (marc:level = 008/33)
  <br/>Ändras ej.
 
#### Beskrivningsnivå 
 * Beskrivningsnivå
  <br/>**OBS! Egenskapen måste för närvarande läggas till manuellt EFTER att den nya agenten först har sparats.**
  <br/>För att lägga till: Skapa och spara agenten, klicka på plustecknet i verktygsmenyn, sök efter och lägg till Beskrivningsnivå, välj Fullständig i rullgardinsmenyn.
   

### Agent

#### Namn   
* Namn 
  <br/>(name) (110 ‡a)
  <br/>Föredragen namnform som utgör den auktoriserade namnformen.
  <br/>```Exempel: Arbetslivscentrum```
  <br/>För namnformer som består av överordnad och underordnad enhet används istället egenskaperna Är del av tillsammans med Namn på underordnad enhet. Om egenskapen Namn används måste egenskaperna Är del av samt Namn på underordnad enhet raderas. Klicka i så fall på papperskorgen vid respektive egenskap.
  
#### Namn i två led 
* Är del av/Namn
  <br/>(isPartOf/name = 110 2/- ‡a)
  <br/>Överordnat namn i en auktoriserad namnform som består av underordnad enhet. Egenskapen används endast tillsammans med Namn på underordnad enhet.
  <br/>```Exempel: Stockholms universitet```
  
* Namn på underordnad enhet (marc/subordinateUnit =110 2/- ‡b)
  <br/>Underordnade och relaterade organisationer som ska anges som underavdelning. Kännetecknande kan vara att namnet är osjälvständigt och det överordnade begreppet behövs för att man med säkerhet ska kunna identifiera organisationen. Namn på underordnad enhet ingår i den auktoriserade namnformen. Egenskapen används endast tillsammans med Är del av. Om dessa två egenskaper används måste egenskapen Namn raderas. Klicka i så fall på papperskorgen vid egenskapen Namn. 
  <br/>```Exempel: Centrum för medeltidsstudier```
  
 #### Verksamhetens starttid  
* Verksamhetens starttid/Startdatum för aktivitetsperiod (activityStartDate = 046 ‡s)
  <br/>```Exempel: 1977```
  
 #### Verksamhetens sluttid    
* Verksamhetens sluttid/Slutdatum för aktivitetsperiod (activityEndDate = 046 ‡t)
  <br/>```Exempel: 1994```
  
 #### Administrativ historik
* Administativ historik (hasHistoricalData = 678 ‡a)
  <br/>Anmärkning om administrativ historik.
  <br/>```Exempel: Statligt forskningsinstitut inom arbetslivsområdet. 1994 ändrades namnet till Institutet för arbetslivsforskning```

#### Variant
* Variant (hasVariant = 410 ‡a ‡b)
  <br/>Här anges variantnamn och alternativa namnformer som stavningsvarianter, förkortningar etc.
  <br/>```Exempel:```
   * ```ALC```
   * ```Swedish Centre for Working Life```
   <br/>För att lägga till variantnamn: Klicka på plustecknet vid egenskapen variant, och välj typ t ex organisation. Lägg sedan till de egenskaper som behövs t ex namn.
   
  ```Exempel på organisation i två led:```
  * ```Är del av/Organisation/Namn: Stockholm University samt Namn på underordnad enhet: Centre for Medieval Studies ```
  * ```Är del av/Jurisdiktion/Namn: Sverige samt Namn på underordnad enhet: Smittskyddsinstitutet```
  <br/>För att ange auktoriserad namnform som består av underordnad enhet: klicka på plustecknet vid egenskapen variant, och välj typ t ex organisation. Till organisation läggs, genom att klicka på plustecknet längst ut till höger vid organisation, egenskaperna Är del av samt Namn på underordnad enhet. Vid Är del av skapas lokal entitet Organisation och egenskapen Namn läggs till.
  
  OBS! Varianter ska inte göras till sökbara länkar.

#### Se även
* Se även (seeAlso = 510)
  <br/>Här länkas mot annan agent som hör ihop med organisationen. Det kan t ex vara föregångare eller efterföljare.
  <br/>```Exempel: Institutet för arbetslivsforskning```
  <br/>För att lägga till: Klicka på plustecknet vid egenskapen Se även, välj typen Organisation i sökrutan till vänster. Sök efter auktoriserad namnform och klicka på plustecknet. (Om organisationen inte finns behöver en ny post skapas som kan länkas). Spara och avsluta innan ny organisation skapas. Använd befintlig mall för Skapa ny: Agent - Organisation).




  
### Valbara egenskaper att lägga till i Agent
 <br/>Vid behov är det möjligt att lägga till egenskaper som inte ingår i mallen. Nya egenskaper läggs till med hjälp av det runda plustecknet i verktygsmenyn.

#### Tid for grundande
* Tid för grundande/Startdatum (establishDate = 046 ‡q)
  <br/>```Exempel: 1965```

#### Tid för upphörande
* Tid för upphörande/Slutdatum (terminateDate = 046 ‡r)
  <br/>```Exempel: 2003```

#### Verksamhetsområde
* Verksamhetsområde (fieldOfActivity = 372 ‡a ‡2)
  <br/>Ange verksamhetsområde för en organisation vid behov.
  <br/>```Exempel: Design```
  <br/>Länka i första hand termen från en kontrollerad vokabulär som Svenska ämnesord. 
För att lägga till: Klicka på plusikonen vid egenskapen Verksamhetsområde, välj Allmänt ämnesord som typ vid sökning. Välj önskad term och klicka på plustecknet. (Skapa lokal entitet används endast då det inte finns auktoriserad entitet att länka till).

#### Språk
* Språk (associatedLanguage = 377 ‡a)
  <br/>Ange språk som organisation använder vid behov.
  <br/>```Exempel: Engelska```
  <br/>Klicka på plustecknet vid egenskapen Språk. Välj Språk som typ vid sökning. Välj önskat språk och klicka på plustecknet. (Skapa lokal entitet används endast då det inte finns auktoriserad entitet att länka till).

#### Andra attribut for person- och organisationsnamn
* Andra attribut för person- och organisationsnamn (marc:hasOtherAttributes = 368 ‡a ‡2)
  <br/>Ange en term för att beskriva typ av organisation om det använts som särskiljande tillägg i den auktoriserade sökingången.
  <br/>```Exempel: Herrgårdar```
  <br/>Länka i första hand termen från en kontrollerad vokabulär som Svenska ämnesord. 
För att lägga till: Klicka på plustecknet vid egenskapen Andra attribut för person- och organisationsnamn, välj Allmänt ämnesord som typ vid sökning. Välj önskad term och klicka på plustecknet. (Skapa lokal entitet används endast då det inte finns auktoriserad entitet att länka till).

#### Organisatorisk tillhörighet
 * Organisatorisk tillhörighet (hasAffiliation = 373 ‡a)
  <br/>Här är det möjligt att ange en samhörande organisation.
  <br/>```Exempel: Uppsala universitet``` 
  <br/>För att lägga till: Klicka på plustecknet vid egenskapen Organisatorisk tillhörighet, och skapa lokal entitet t ex organisation. Lägg sedan till benämning och skriv in uppgiften. OBS! Organisatorisk tillhörighet ska inte göras till sökbar länk.

<br/>Glöm inte att redigera Adminmetadata och spara entiteten innan vidare navigation i verktyget!


