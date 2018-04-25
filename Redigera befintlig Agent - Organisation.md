
UNDER ARBETE

## Redigera befintlig: Agent - Organisation
<br/>Exemplet nedan är baserat på Sveriges släktforskarförbund. Vissa tillägg är fiktiva, enbart för att exemplifiera.
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
  
* Samma sak som(samAs = VoyagerID)
  <br/>resource/auth/394287. Ändras ej
  
  ### Adminmetadata

Information av administrativ karaktär som inte är direkt förknippad med den auktoriserade namnformen.

* Kontrollnummer (controllNumber = AuktID från Voyager)  
  394287. Ändras ej
      
* Katalogiseringsregler (descriptionConventions = 040 ‡e)
 <br/>Förval: rda. Ändra vid behov.
 <br/>```Exempel: Kod: rda```
 
 * Katalogisatörens anmärkning (cataloguersNote = 667 ‡a)
  <br/>Anmärkningar tänkta för kollegor inom Libriskollektivet. Det kan till exempel vara uppgifter som rör ändring av den auktoriserade namnformen. Motivera gärna ändringen och komplettera alltid med datum/sigel/signatur.
  <br/>```Exempel: Uppdaterad till rda 2018-04-11/S/NB/carbac```

 * Skapad av (descriptionCreator = 040 ‡a)
 <br/>Förval: inloggad sigel. Ändras ej?
 <br/>```Exempel: library/S```
  
* Katalogiseringsspråk (descriptionLanguage = 040 ‡b)
 <br/>Förval: language/swe. Ändras ej
  
* Beskrivningsnivå (encodingLevel = 000/?)
 <br/>Val i meny?/Ändras ej?
 
* Marc:headingMain (marc:headingMain = 000/?)
 <br/>tru står skrivet i ruta.                  Vad är detta? - Ta bort??
 
* Typ av auktoritetspost (marc:kindOfRecord = 000/?)
 <br/>marc/KindOfRecordType-a. Ändras ej
 
* Auktoritetskontrollnivå (marc:level = 008/33)
  <br/>marc/LevelType-a. Ändras ej

* Numrering i serie (marc:numberedSeries = 000/?)
 <br/>"code":"n"                                Vad är detta? - Ta bort??  
     
* Differentiering av posten (marc:personalName = 008/32)
  <br/>marc/PersonalNameType-a. Ändras ej
  
* Uppdatering av posten (marc:recordupdate = 000/?)
  <br/>marc/LevelType-a. Ändras ej
  
* Formatering av icke auktoriserade sökelement (marc:reference = 000/?)
 <br/>"code":"n"                                Vad är detta, ta bort??  

* Translitterering (marc:romanization = 008/07)
 <br/>marc/NationalStandard. Ändras ej
 
* Geografisk precisering (marc:subdivision = 000/?)
 <br/>"code":"n"                                Vad är detta, ta bort??  

* Typ av underindelning (marc:typeOfSeries = 000/?)
 <br/>"code":"n"                                Vad är detta, ta bort??  

* Poststatus (recordStatus = = 000/?)
  <br/>Val i meny?/Ändras ej?
  
* Samma sak som(samAs = VoyagerID) 
  <br/>auth/394287. Ändras ej

* Konsulterad källa (sourceConsulted = 670 ‡a) samt Uppgift från källa (citationNote = 670 ‡b)
  <br/>Välj typ av konsulterad källa i rullgardinsmenyn till vänster. Vid val av "Källa vid belagd uppgift" finns möjlighet att ange såväl källa som uppgift hämtad från källa.
   <br/>```Exempel:```
   <br/>```Uppgift från källa: Startår 1886```
   <br/>```Källa: Wikipedia (Svenska) 2018-04-24```
  
  Den resurs som föranleder auktoriseringen är en obligatorisk källa.
  <br/>```Exempel: Fader okänd / Sveriges släktforskarförbund, 2016```
  <br/>eller
  <br/>```Exempel: Årsberättelse, 1971```


### Fält som är möjliga att lägga till i beskrivningen

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

* Förknippad plats (associatedLocal = 370 ‡c)
  <br/>Anges vid behov.
  <br/>```Exempel: Sverige```
   <br/>[Länk till Att länka entitet]
 
* Språk (associatedLanguage = 377 ‡a)
  <br/>Ange språk som organisation använder vid behov.
  <br/>```Exempel: Engelska```
   <br/>[Länk till Att länka entitet]
  
* Andra attribut för person- och organisationsnamn (marc:hasOtherAttributes = 368 ‡a ‡2)
  <br/>Ange en term för att beskriva typ av organisation om det behövs som särskiljande tillägg i den auktoriserade sökingången.
  <br/>Hämta termen från Svenska ämnesord.
  <br/>```Exempel: Herrgårdar```
   <br/>[Länk till Att länka entitet]
  
* Organisatorisk tillhörighet (hasAffiliation = 373 ‡a)
  <br/>Här är det möjligt att ange en samhörande institution.
  <br/>```Exempel: Uppsala universitet```    

 
