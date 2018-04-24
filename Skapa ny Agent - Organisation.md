UNDER ARBETE

## Skapa ny - Agent: organisation
Lathunden beskriver de fält som finns representerade i mallen. Om något av fälten i mallen inte behövs kan de raderas genom ett klick på papperskorgsikonen intill fältet. Ett urval av fält kopplade till organisation som är möjliga att lägga till men som inte finns i mallen beskrivs i slutet av lathunden. Några av dessa fält är viktiga och används om man ska skapa organisationer med namn i två led.


### Fält i mall

* Namn (name) (110 ‡a)
  <br/>Föredragen namnform som utgör den auktoriseade namnformen. Här anges endast namnformer som består av ett led.
  <br/>```Exempel: Sveriges släktforskarförbund```

* Verksamhetens starttid/Startdatum för aktivitetsperiod (activityStartDate, 046 ‡s)
  <br/>```Exempel: 1886```
    
* Verksamhetens sluttid/Slutdatum för aktivitetsperiod (activityEndDate, 046 ‡t)
  <br/>```Exempel: 1999``` 
   
* Administativ historik (has Historical Data) (678 ‡a)
  <br/>Anmärkning om administrativ historik. Klicka på pilen och skriv in värde
  <br/>```Exempel: Riksförbund för svenska släktforskare```
  
* Variant (hasVariant = 410 ‡a)
  <br/>I detta fält anges variantnamn och alternativa namnformer som stavningsvaranter, förkortningar etc. Fältet upprepas om flera variantnamn behöver läggas till. Klicka på +ikonen under egenskapen Variant och skapa lokal entitet t ex organisation. Lägg sedan till det fält som behövs t ex namn.
  <br/>```Exempel:Släktforskarförbundet```
  <br/>```Exempel: Federation of Swedish Genealogical Societies```
  
* Se även (seeAlso = 510 ‡a)
  <br/>I detta fält länkas mot annan agent som hör ihop med organisationen. Det kan t ex vara föregångare eller efterföljare. Klicka på +ikonen under egenskapen Se även och länka agent genom att söka på agentens namn.
  <br/>```Exempel:Föreningen Emigrantinstitutets vänner```

* Identifikator (identifiedBy = 024 ‡a ‡2)
  <br/>Isni som identifikator är valfri uppgift men önskvärt om tillgänglig. Välj typ av identifikator i rullmenyn. Klicka sedan på pilen och skriv in värde 
  <br/>```Exempel:  ISNI, 0000000104839039```
    
* Nationalitet (nationality = 043 ‡a)
  <br/>I mallen ligger nationalitetskoden för Sverige (e-sw---) förifylld. Vid behov kan denna raderas och annan nationalitet läggas till. Välj nationalitet genom att länka. Sök på landets namn. 
  <br/>```Exempel: e-uk---```
  
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
  
   
  
### Valbara fält som saknas i mallen
Följande fält är möjliga att lägga till för organisation. Nya fält läggs till med hjälp av +Fält-ikonen

* Är del av (isPartOf) samt Namn (name) = 110 ‡a)
  <br/>Överordnat led i en namnform som består av underavdelning. 
  <br/>```Exempel: Uppsala Universitet```
  
* Namn på underordnad enhet (marc/subordinateUnit =110 ‡b)
  <br/>Underordnade och relaterade organisationer som ska anges som underavdelning. Kännetecknande kan vara att namnet är osjälvständigt och det överordnade begreppet behövs för att man med säkerhet ska kunna identifiera organisationen. Namn på underordnad enhet ingår i den auktoriserade namnformen.
  <br/>```Exempel: Engelska institutionen```

* Tid för grundande/Startdatum (establishDate = 046 ‡q)
  <br/>```Exempel: 1965```

* Tid för upphörande/Slutdatum (terminateDate = 046 ‡r)
  <br/>```Exempel: 2003```
  
* Verksamhetsområde (fieldOfActivity = 372 ‡a ‡2)
  <br/>Ange verksamhetsområde för en organisation vid behov. Klicka på +-ikonen under egenskapen verksamhetsområde. Hämta termen från Svenska ämnesord genom att länka entitet.
  <br/>```Exempel: Släktforskning```  

* Förknippad plats (associatedLocal = 370 ‡c)
  <br/>Vid plats: länka till entitet.
  <br/>```Exempel: Sverige```
 
* Språk (associatedLanguage = 377 ‡a)
  <br/>Ange språk som organisation använder vid behov. Länka till entitet.
  <br/>```Exempel: Engelska```
  
* Andra attribut för person- och organisationsnamn (marc:hasOtherAttributes = 368 ‡a ‡2)
  <br/>Ange en term för att beskriva typ av organisation om det behövs som särskiljande tillägg i den auktoriserade sökingången.
  <br/>Hämta termen från Svenska ämnesord genom att länka entitet.
  <br/>```Exempel: Herrgårdar``` 
  
* Organisatorisk tillhörighet (hasAffiliation = 373 ‡a)
  <br/>Här är det möjligt att ange en samhörande institution.
  <br/>```Exempel: Uppsala universitet``` 
   
    
