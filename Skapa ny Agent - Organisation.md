UNDER ARBETE

## Skapa ny - Agent: organisation
Lathunden beskriver de fält som finns representerade i mallen. Om något av fälten i mallen inte behövs kan de raderas genom ett klick på papperskorgsikonen intill fältet. Ett urval av fält kopplade till organisation som är möjliga att lägga till men som inte finns i mallen beskrivs i slutet av lathunden. Några av dessa fält är viktiga och används om man ska skapa organisationer med namn i två led.


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
  
### Adminmetadata

Information av administrativ karaktär som inte är direkt förknippad med den auktoriserade namnformen.
      
* Katalogiseringsregler (descriptionConventions = 040 #e)
    Förval: rda. Ändra vid behov.
    Exempel: Kod: rda
  
 * Skapad av (descriptionCreator = 040 ‡a)  
  Förval: inloggad sigel. Ändras ej.  
  ```Exempel: S```
  
* Katalogiseringsspråk (descriptionLanguage = 040 #b)
    Förval: language/swe. Ändras ej.
  
* Beskrivningsnivå (encodingLevel = 000/?)
  Val i meny?/Ändras ej?

* Translitterering (marc:romanization = 008/07)
  Ändras ej

* Poststatus (recordStatus = = 000/?)
  Val i meny?/Ändras ej?

* Katalogisatörens anmärkning (cataloguersNote = 667 #a)
  <br/>Anmärkningar tänkta för kollegor inom Libriskollektivet. Det kan till exempel vara uppgifter som rör ändring av den auktoriserade namnformen. Motivera gärna ändringen och komplettera alltid med datum/sigel/signatur.
  <br/>```Exempel: Ändrad auktoriserad namnform från Xxx till Yyy 2010-01-03/S/UL/marjan```

* Konsulterad källa (sourceConsulted = 670 #a #b)
  <br/>Välj typ av konsulterad källa i rullgardinsmenyn till vänster. Vid val av "Källa vid belagd uppgift" finns möjlighet att ange såväl källa som vilken information som är hämtad från från källan.
   <br/>```Exempel:```
   <br/>```Uppgift från källa: Startår 1886```
   <br/>```Källa: Wikipedia (Svenska) 2018-04-24```
  
  Den resurs som föranleder auktoriseringen en obligatorisk källa.
   <br/>```Exempel: Fader okänd / Sveriges släktforskarförbund, 2016```
eller
   <br/>```Exempel: Årsberättelse, 1971```
   
* Uppdatering av posten (marc:recordUpdate = 008/31)
    Ändras ej
    
* Differentiering av posten (marc:personalName = 008/32)
    Ändras ej

* Auktoritetskontrollnivå (marc:level = 008/33)
    Ändras ej
  
   
  
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
  


  
  Skapa ny Agent - Person

Beskrivning av agenten som ska auktoriseras. Lathunden beskriver de fält som finns representerade i mallen. Om något av fälten i mallen inte behövs kan de raderas genom ett klick på papperskorgsikonen intill fältet. Ett urval av fält kopplade till person som är möjliga att lägga till men som inte finns i mallen beskrivs i slutet av lathunden.

    Efternamn (FamilyName = 100 #a)
    Enkelt eller sammansatt släktnamn/efternamn. Föredragen namnform som tillsammans med förnamn utgör den auktoriserade namnformen.
    Exempel: Lagerlöf

    Förnamn (GivenName = 100 #a)
    Förnamn som tillsammans med efternamn utgör den auktoriserade namnformen.
    Exempel: Selma
    Om flera förnamn ska ingå i den auktoriserade namnformen skrivs de direkt efter varandra.

    Födelse- och/eller dödstid (lifeSpan = 100 #d)
    Årtal används i första hand som särskiljande tillägg för personer.
    Exempel: 1858-1940
    Exempel: 1968-

    Födelsedatum (birthDate = 046 #f)
    Ange fullständigt födelsedatum om uppgiften är känd. I annat fall, ange känd uppgift.
    Exempel: 18581120
    Exempel: 1902

    Dödsdatum (deathDate = 046 #g)
    Ange fullständigt dödsdatum om uppgiften är känd. I annat fall, ange känd uppgift.
    Exempel: 19400316
    Exempel: 1977

    Variant (hasVariant = 400 #a #d)
    I detta fält anges variantnamn och alternativa namnformer. Här anges stavningsvaranter, förkortningar, ändringar till följd av namnbyten etc. Variantnamn kan till exempel finnas i referenskällor eller i de bibliografiska posterna. Fältet upprepas om flera variantnamn behöver läggas till.
    Exempel: Efternamn: Lagerlöf Förnamn: Selma Ottiliana Lovisa
    Exempel: Efternamn: Lagerlœf Förnamn: Selma
    För att lägga till fält: Klicka på +-ikonen under egenskapen Variant, välj Person under Skapa lokal entitet. Klicka på +-ikonen till höger om det nytillagda Person-fältet, sök efter och lägg till fält (Efternamn, Förnamn och Födelse- och/eller dödstid ELLER Namn och Födelse- och/eller dödstid) för att ange information.

    Se även (seeAlso = 500 #a #d)
    I detta fält anges se även-hänvisning till en annan auktoritetspost, t.ex. till en pseudonym eller då en upphovsperson är verksam under mer än en identitet.
    Exempel: Efternamn: Smith Förnamn: Rosamond Födelse- och/eller dödstid: 1938- som se-hänvisning från auktoritetsposten för Oates, Joyce Carol, 1938-
    För att lägga till fält: Klicka på +-ikonen under egenskapen Variant, välj Person som typ och sök i rutan till vänster. Välj auktoriserad entitet (Person) att länka till och och klicka på Lägg till-rutan till höger. (Skapa lokal entitet används endast då det inte finns auktoriserad entitet att länka till.)

    Verksamhetsområde (fieldOfActivity = 372)
    Personens verksamhetsområde beskriver vad personen är intresserad av eller ägnar sig åt och det behöver inte ha med yrkesutövning att göra. Hämta i första hand termen från en kontrollerad vokabulär som Svenska ämnesord.
    För att lägga till fält: Klicka på +-ikonen under egenskapen Har yrke eller sysselsättning, välj Allmänt ämnesord som typ och sök i rutan till vänster, välj önskad term och klicka på den gröna Lägg till-rutan till höger. (Skapa lokal entitet används endast då det inte finns auktoriserad entitet att länka till.)
    Exempel: Fågelskådning

    Har yrke eller sysselsättning (hasOccupation = 374)
    Ange yrke eller sysselsättning om det behövs för att skilja en person från en annan, t.ex. när en persons födelsetid eller dödstid inte är tillgängligt. Hämta i första hand termen från en kontrollerad vokabulär som Svenska ämnesord.
    För att lägga till fält: Klicka på +-ikonen under egenskapen Har yrke eller sysselsättning, välj Allmänt ämnesord som typ och sök i rutan till vänster, välj önskad term och klicka på den gröna Lägg till-rutan till höger. (Skapa lokal entitet används endast då det inte finns auktoriserad entitet att länka till.)
    Exempel: Romanförfattare
    Exempel: Översättare

    Identifikator (identifiedBy = 024 #a #2)
    Isni som identifikator är valfri uppgift men önskvärt om tillgänglig.
    Exempel: 0000000121339888

    Nationalitet/verksamhetsland (nationality = 043 #a)
    I mallen ligger nationalitetskoden för Sverige (e-sw---) förifylld. Vid behov kan denna raderas.
    För att lägga till fält: Klicka på +-ikonen under egenskapen Nationalitet/verksamhetsland. Välj Nationalitet som typ och sök i rutan till vänster. Välj önskad nationalitet och klicka på den gröna Lägg till-rutan till höger. (Skapa lokal entitet används endast då det inte finns auktoriserad entitet att länka till.)

    
    

Valbara fält som inte ingår i mallen

Vid behov är det möjligt att lägga till fält som inte ingår i mallen. Nya fält läggs till med hjälp av +-ikonen.

    Namn
    Används för namn i rak följd istället för fälten Förnamn och Efternamn. Kan användas i kombination med fälten Förnamn och Efternamn endast för att ange variantnamn.
    Exempel: Namn: Bang Som variantnamn till den auktoriserade namnformen Alving, Barbro, 1909-1987

    Fullständigare namnform (fullerFormOfName = 100 #q och 378)
    Används för att ange fullständig namnform i de fall då fortkortning används i den auktoriserade namnformen
    Exempel: Efternamn: Smith
    Exempel: Förnamn: A. D.
    Exempel: Fullständigare namnform: Adam David

    Titel eller övrig beteckning (marc:titlesAndOtherWordsAssociatedWithAName = 100 #c)
    Används vid behov som särskiljande tillägg till den auktoriserade namnformen.
    Exempel: påve

    Andra attribut för person- och organisationsnamn (hasOtherAttributes = 368)
    Används vid

  
