
UNDER ARBETE

## Redigera befintlig: Agent - Organisation

<br/>Exemplet nedan är baserat på Sveriges släktforskarförbund. Tillägg är fiktiva, enbart för att exemplifiera.

<br/>Första delen av lathunden beskriver fält som redan finns i beskrivningen. Ett urval av fält kopplade till organisation som är möjliga att lägga till beskrivs i slutet av lathunden 

### Befintliga fält i beskrivningen

* Namn (name) (110 ‡a)
  <br/>Föredragen namnform som utgör den auktoriseade namnformen. Här anges endast namnformer som består av ett led.
  <br/>```Exempel: Sveriges släktforskarförbund```
  
* Tid för grundande/Startdatum (establishDate = 046 ‡q)
  <br/>```Exempel: 1886```
  
* Verksamhetsområde (fieldOfActivity = 372 ‡a ‡2)
  <br/>Ange verksamhetsområde för en organisation vid behov. Klicka på +-ikonen under egenskapen verksamhetsområde. Hämta termen från Svenska ämnesord.
  <br/>```Exempel: Släktforskning```
  <br/>[Länk till Att länka entitet]
    
* Administativ historik (has Historical Data) (678 ‡a)
  <br/>Anmärkning om administrativ historik. Klicka på pilen och skriv in värde
  <br/>```Exempel: Riksförbund för svenska släktforskare```    
  
* Variant (hasVariant = 410 ‡a)
  <br/>I detta fält anges variantnamn och alternativa namnformer som stavningsvaranter, förkortningar etc. Fältet upprepas om flera variantnamn behöver läggas till. Klicka på +ikonen under egenskapen Variant och skapa lokal entitet t ex organisation. Lägg sedan till det fält som behövs t ex namn.
  <br/>```Exempel:Släktforskarförbundet```
  <br/>```Exempel: Federation of Swedish Genealogical Societies```
  
* Identifikator (identifiedBy = 024 ‡a ‡2)
  <br/>Välj typ av identifikator i rullmenyn. Klicka sedan på pilen och skriv in värde 
  <br/>```Exempel:  ISNI, 0000000104839039```
  <br/>```Exempel:  VIAF, 156982904```
  
* Nationalitet (nationality = 043 ‡a)
  <br/>Välj nationalitet enligt lista. 
  <br/>```Exempel: e-sw---```
  <br/>[Länk till Att länka entitet]
  
* Samma sak som(samAs)
  <br/>VoyagerID. 
  <br/>resource/auth/394287. Ändras ej



### Fält att lägga till i beskrivningen

* Tid för upphörande/Slutdatum (terminateDate = 046 ‡r)
  <br/>```Exempel: 2003```

* Verksamhetens starttid/Startdatum för aktivitetsperiod (activityStartDate, 046 ‡s)
  <br/>```Exempel: 1886```
    
* Verksamhetens sluttid/Slutdatum för aktivitetsperiod (activityEndDate, 046 ‡t)
  <br/>```Exempel: 1999``` 


  
* Se även (seeAlso = 510 ‡a)
  <br/>I detta fält länkas mot annan agent som hör ihop med organisationen. Det kan t ex vara föregångare eller efterföljare. Klicka på +ikonen under egenskapen Se även och länka agent genom att söka på agentens namn.
  <br/>```Exempel:Föreningen Emigrantinstitutets vänner```
  <br/>[Länk till Att länka entitet]


    

  
### Adminmetadata

Information av administrativ karaktär som inte är direkt förknippad med den auktoriserade namnformen.
      
* Katalogiseringsregler (descriptionConventions = 040 ‡e)
 <br/>Förval: rda. Ändra vid behov.
 <br/>```Exempel: Kod: rda```
  
 * Skapad av (descriptionCreator = 040 ‡a)
 <br/>Förval: inloggad sigel. Ändras ej.
 <br/>```Exempel: library/S```
  
* Katalogiseringsspråk (descriptionLanguage = 040 ‡b)
 <br/>Förval: language/swe. Ändras ej.
  
* Beskrivningsnivå (encodingLevel = 000/?)
 <br/>Val i meny?/Ändras ej?

* Translitterering (marc:romanization = 008/07)
 <br/>marc/NationalStandard. Ändras ej

* Poststatus (recordStatus = = 000/?)
  <br/>Val i meny?/Ändras ej?

* Katalogisatörens anmärkning (cataloguersNote = 667 ‡a)
  <br/>Anmärkningar tänkta för kollegor inom Libriskollektivet. Det kan till exempel vara uppgifter som rör ändring av den auktoriserade namnformen. Motivera gärna ändringen och komplettera alltid med datum/sigel/signatur.
  <br/>```Exempel: Ändrad auktoriserad namnform från Xxx till Yyy 2018-01-03/S/NB/carbac```

* Konsulterad källa (sourceConsulted = 670 ‡a) samt Uppgift från källa (citationNote = 670 ‡b)
  <br/>Välj typ av konsulterad källa i rullgardinsmenyn till vänster. Vid val av "Källa vid belagd uppgift" finns möjlighet att ange såväl källa som uppgift hämtad från källa.
   <br/>```Exempel:```
   <br/>```Uppgift från källa: Startår 1886```
   <br/>```Källa: Wikipedia (Svenska) 2018-04-24```
  
  Den resurs som föranleder auktoriseringen är en obligatorisk källa.
  <br/>```Exempel: Fader okänd / Sveriges släktforskarförbund, 2016```
  <br/>eller
  <br/>```Exempel: Årsberättelse, 1971```
   
* Uppdatering av posten (marc:recordUpdate = 008/31)
  <br/>marc/RecordCanBeUsed. Ändras ej
    
* Differentiering av posten (marc:personalName = 008/32)
  <br/>marc/DifferentiatedPersonalName. Ändras ej

* Auktoritetskontrollnivå (marc:level = 008/33)
  <br/>marc/FullyEstablishedHeading. Ändras ej
  
   
  





UNDER ARBETE

## Skapa - Agent: organisation
Exemplen är hämtade från olika poster

### Adminmetadata

* Kontrollnummer (controllNumber) 
  AuktID från Voyager. Kan inte ändras.  
  ```Exempel: 409156```
  
* Skapad av (descriptionCreator) (040 ‡a)  
  Förval: den sigel som skapat posten. Ska inte ändras.  
  ```Exempel: S```
  
 * Senast ändrad av (descriptionLastModifier) (040 ‡d)  
  Ange den sigel som ändrat posten.  
  ```Exempel: NB```
    
* Katalogiseringsregler (descriptionConventions) (040 ‡e)  
  För post katalogiserad enligt RDA, länka till entitet: Katalogiseringsregler samt skapa lokal entitet med Kod: rda    
  ```Exempel: Katalogiseringsregler (länkad entitet) + lokal entitet, Kod: rda```

* Katalogiseringsspråk (descriptionLanguage) (040 ‡b)  
  Länka till entitet.  
  ```Exempel: Svenska```

* Katalogisatörens anmärkning (cataloguersNote) (667 #a)
  <br/>Anmärkningar tänkta för kollegor inom Libriskollektivet. Det kan till exempel vara uppgifter som rör ändring av den auktoriserade namnformen. Motivera gärna ändringen och komplettera alltid med datum/sigel/signatur.
  <br/>```Exempel: Ändrad auktoriserad namnform från Xxx till Yyy 2010-01-03/S/UL/marjan```

* Konsulterad källa (sourceConsulted) (670 #a)
  <br/>Källa vid belagd uppgift.
   <br/>```Exempel: NE (2018-04-11)```
   <br/>```Exempel: LC i VIAF (2018-04-11)```
  
* Beskrivningsnivå (encodingLevel) (000/Leader/?)

* Auktoritetskontrollnivå (marc:level)
  
* Poststatus (recordStatus = = 000/Leader/?)


### Fält i mall

* Namn (name) (110 ‡a)
  <br/>Föredragen namnform som utgör den auktoriseade namnformen eller del av den auktoriserade namnformen
  <br/>```Exempel: Sveriges släktforskarförbund```
  <br/>```Exempel: Uppsala Universitet```
  
* Namn på underordnad enhet (marc/subordinateUnit) (110 ‡b)
  <br/>Underordnade och relaterade organisationer som ska anges som underavdelning. Kännetecknande kan vara att namnet är osjälvständigt och det överordnade begreppet behövs för att man med säkerhet ska kunna identifiera organisationen. Namn på underordnad enhet ingår i den auktoriserade namnformen.
  <br/>```Exempel: Engelska institutionen```

* Verksamhetens starttid/Startdatum för aktivitetsperiod (activityStartDate, 046 ‡s)
  <br/>```Exempel: 1886```
    
* Verksamhetens sluttid/Slutdatum för aktivitetsperiod (activityEndDate, 046 ‡t)
  <br/>```Exempel: 1999```
  
* Exakt match/har variant (exaktMatch, 410 ‡a ‡b?)
  <br/>I detta fält anges variantnamn och alternativa namnformer. Här anges stavningsvaranter, förkortningar etc. Variantnamn kan till exempel finnas i referenskällor eller i de bibliografiska posterna. Fältet upprepas om flera variantnamn behöver läggas till. Variantnamn med underordnad enhet anges???
  <br/>```Exempel: Släktforskarförbundet```
  <br/>```Exempel: Federation of Swedish Genealogical Societies```
  
* Administativ historik (has Historical Data) (678 ‡a)
  <br/>Anmärkning om administrativ historik. Klicka på pilen och skriv in värde
  <br/>```Exempel: Riksförbund för svenska släktforskare```

* Identifikator (identifiedBy) (024 ‡a ‡2)
  <br/>Välj typ av identifikator i rullmenyn. Klicka sedan på pilen och skriv in värde 
  <br/>```Exempel:  ISNI, 0000000104839039```
    
* Nationalitet (nationality) (043 ‡a)
  <br/>Välj nationalitet i rullmeny?/Välj nationalitet genom att länka. Sök på landets namn. 
  <br/>```Exempel: e-sw---```
  
  
### Valbara fält som saknas i mallen
Följande fält är möjliga att lägga till för organisation. Nya fält läggs till med hjälp av +Fält-ikonen

* Tid för grundande/Startdatum (establishDate, 046 ‡q)
  <br/>```Exempel: 1965```

* Tid för upphörande/Slutdatum (terminateDate, 046 ‡r)
  <br/>```Exempel: 2003```
  
* Verksamhetsområde (fieldOfActivity) (372 ‡a ‡2)
  <br/>Ange verksamhetsområde för en organisation vid behov.
  <br/>Hämta termen från Svenska ämnesord genom att länka entitet.
  <br/>```Exempel: Släktforskning```  

* Förknippad plats (associatedLocal) (370 ‡c)
  <br/>Vid plats: länka till entitet.
  <br/>```Exempel: Sverige```
 
* Språk (associatedLanguage) (377 ‡a)
  <br/>Ange språk som organisation använder vid behov. Länka till entitet.
  <br/>```Exempel: Engelska```
  
* Andra attribut för person- och organisationsnamn (marc:hasOtherAttributes) (368 ‡a ‡2)
  <br/>Ange en term för att beskriva typ av organisation om det behövs som särskiljande tillägg i den auktoriserade sökingången.
  <br/>Hämta termen från Svenska ämnesord genom att länka entitet.
  <br/>```Exempel: Herrgårdar``` 
  
* Organisatorisk tilhörighet (hasAffiliation) (373 ‡a)
  <br/>Här är det möjligt att ange en samhörande institution.
  <br/>```Exempel: Uppsala universitet```  <br/>Ange en term för att beskriva typ av organisation om det behövs som särskiljande tillägg i den auktoriserade sökingången.
  <br/>Hämta termen från Svenska ämnesord genom att länka entitet.
  <br/>```Exempel: Herrgårdar``` 
  
* Organisatorisk tilhörighet (hasAffiliation) (373 ‡a)
  <br/>Här är det möjligt att ange en samhörande institution.
  
  
  UNDER ARBETE - UPPDATERAS KONTINUERLIGT

* Efternamn (FamilyName = 100 i1=1 ‡a)
  <br/>```Exempel: Jansson```

* Förnamn (GivenName = = 100 ‡a)
  <br/>```Exempel: Erik```

* Biografiska uppgifter (hasBiographicalInformation = 678)
  <br/>```Exempel: Väckelsepredikant i Österbotten```
  
* Födelse- och/eller dödstid (lifeSpan = 100 ‡d)
  <br/>Årtal används i första hand som särskiljande tillägg för personer. Redigera om det behövs.
  <br/>```Exempel: 1848-1920```

* Nationalitet/verksamhetsland (Nationality = 043 ‡a)
  <br/>Vid behov kan denna ändras eller raderas. Lägg till ytterligare kod genom att klicka på ```+Nationalitet ```
  <br/>Sök i rutan till vänster, välj önskad nationalitet och klicka på den gröna Lägg till-rutan till höger.
  <br/>```Exempel: ?```

* Kontrollnummer
  <br/>Libris-ID. Ändras ej, raderas ej.

* Samma sak som (SameAs)
  <br/>```Exempel: resource/auth/247521```
  
## Fält att lägga till i beskrivningen

* Födelsedatum (birthDate = 046 ‡f)
  <br/>Ange fullständigt födelsedatum om uppgiften är känd. I annat fall, ange känd uppgift.
  <br/> ```Exempel: 18480219```
  
* Dödsdatum (deathDate = 046 ‡g)
  <br/>Ange fullständigt dödsdatum om uppgiften är känd. I annat fall, ange känd uppgift.
  <br/> ```Exempel: 19201209```

* Variant (hasVariant = 400 ‡a ‡d)
  <br/>I detta fält anges variantnamn och alternativa namnformer. Här anges stavningsvaranter, förkortningar, ändringar till följd av namnbyten etc. Variantnamn kan till exempel finnas i referenskällor eller i de bibliografiska posterna. Fältet upprepas om flera variantnamn behöver läggas till.
  <br/>```Exempel: Efternamn: Jansson ; Förnamn: Eric```
  <br/>```Exempel: Namn: Lagerlœf ; Förnamn: Selma```
  
* Identifikator (identifiedBy = 024 ‡a)
  <br/>Isni som identifikator är valfri uppgift men önskvärt om tillgänglig. 
  <br/> ```Exempel: 0000000121339888 ```

* Nationalitet/verksamhetsland (nationality = 043)
  <br/>I mallen ligger nationalitetskoden för Sverige (e-sw---) förifylld. Vid behov kan denna raderas. Lägg till ytterligare kod genom att klicka på ```+Nationalitet ```
  <br/>Sök i rutan till vänster, välj önskad nationalitet och klicka på den gröna Lägg till-rutan till höger.

* Har yrke eller sysselsättning (hasOccupation = 374)
   <br/>Ange yrke eller sysselsättning om det behövs för att skilja en person från en annan, t.ex. när en persons födelsetid eller dödstid inte är tillgängligt. 
   <br/>Lägg till ytterligare yrke eller sysselsättning genom att klicka på ```+Koncept ```
  <br/>Sök i rutan till vänster, välj önskad term och klicka på den gröna Lägg till-rutan till höger. 
   <br/>```Exempel: Romanförfattare ```
   <br/>```Exempel: Översättare```

### Befintliga fält i Adminmetadata
Information av administrativ karaktär som är väsentlig för auktoritetsposten i sig och inte är direkt förknippad med den auktoriserade namnformen.

* Kontrollnummer
  <br/>Gammalt Libris-ID. Ska inte ändras eller radersa.  

* Katalogiseringsregler (descriptionConventions = 040 ‡e)
  <br/>Radera och lägg till rda vid behov. 
  ```Exempel: marc/CatalogingRulesType-c``` 

* Skapad av (descriptionCreator = 040 ‡a)
  <br/>Förval: den sigel som skapat posten. Ska inte ändras.  
  ```Exempel: S```

* Beskrivningsnivå (encodingLevel = 000/Leader/?)
  Ändras ej?

* Translitterering
  Ändras ej?
  
* Typ av auktoritetspost  
  Ändras ej?

* Poststatus (recordStatus = = 000/Leader/?)
  Ändras ej?

* Uppdatering av posten
  Ändras ej?

* Differentiering av posten
  Ändras ej?

* Auktoritetskontrollnivå
  Ändras ej?

* Katalogiseringsspråk (descriptionLanguage = 040 ‡b)
  Länka till entitet.  
  ```Exempel: svenska (swe)```

* Identifikator?
  <br/>Libris-ID automatgenereras då posten skapas och kan inte ändras.

* Konsulterad källa (sourceConsulted = 670)
  <br/>Källa vid belagd uppgift. Den resurs som föranleder auktoriseringen är obligatorisk källa i auktoritetsposten. Hur ska vi ange resurs som källa?
  <br/>```Exempel: NE 2018-04-12```
  <br/>```Exempel: Källor i tåredalen, 1999```

