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
  ```Exempel: svenska (swe)```

* Katalogisatörens anmärkning (cataloguersNote) (667 #a)
  <br/>Anmärkningar tänkta för kollegor inom Libriskollektivet. Det kan till exempel vara uppgifter som rör ändring av den auktoriserade namnformen. Motivera gärna ändringen och komplettera alltid med datum/sigel/signatur.
  ```Exempel: Författaren vill inte ha sitt födelseår i auktoritetsposten. Enligt e-post 2017-05-12, S/NB/annbjo```

* Konsulterad källa (sourceConsulted) (670 #a)
  <br/>Källa vid belagd uppgift.
  ```Exempel: NE (2018-04-11)```
  ```Exempel: LC i VIAF (2018-04-11)```
  
* Beskrivningsnivå (encodingLevel) (000/Leader/?)

* Auktoritetskontrollnivå (marc:level)
  
* Poststatus (recordStatus = = 000/Leader/?)





### Fält i mall

* Namn (name) (110 ‡a)
  <br/>Föredragen namnform som utgör den auktoriseade namnformen eller del av den auktoriserade namnformen
  <br/>```Exempel: Sveriges släktforskarförbund```
  <br/>```Exempel: Uppsala Universitet```
  
* Namn på underordnad enhet (marc/subordinateUnit) (110 ‡b)
  <br/>Här anges underordnade och relaterade organisationer som ska anges som underavdelning. Kännetecknande kan vara att namnet är osjälvständigt och det överordnade begreppet behövs för att man med säkerhet ska kunna identifiera organisationen. Namn på underordnad enhet ingår i den auktoriserade namnformen.
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
  

### Valbara fält som inte ingår i mallen
<br/>Följande fält är möjliga att lägga till för Organisation. Nya fält läggs till med hjälp av +Fält-ikonen

* Tid för grundande/Startdatum (establishDate, 046 ‡q)
  <br/>```Exempel: 1965```

* Tid för upphörande/Slutdatum (terminateDate, 046 ‡r)
  <br/>```Exempel: 2003```
  
* Verksamhetsområde (fieldOfActivity, 372 ‡a ‡2)

* Typ

* Plats (place, 370 ‡a ‡b ‡c ‡e ‡f ‡s ‡t)

    
