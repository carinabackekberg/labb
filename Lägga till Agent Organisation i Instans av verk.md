
UNDER ARBETE (uppdaterad 2018-11-21)

## Lägga till Agent (byta rubrik?)

Hjälptexten beskriver hur man lägger till Agent vid Medverkan och funktion samt som Ämne i Instans av Verk. Saknas egenskaper för Medverkan och Funktion eller Ämne läggs de till genom att klicka på plustecknet vid Text.

Var noggrann vid sökning efter Agenten och länka om möjligt. Vid behov skapa ny Agent. Använd de mallar som finns vid Skapa ny - Agent tillsammans med de hjälptexter för Agenter som finns i Hjälpsektion. OBS! I nuläget finns det endast mallar för Agent Person och Agent Organisation. Om ny Agent inte skapas använd Skapa lokal entitet.

För information om katalogregler, skrivregler och övriga katalogiseringsanvisningar, se [Anvisningar för katalogisering - RDA](http://www.kb.se/rdakatalogisering/Anvisningar/ "Anvisningar för katalogisering - RDA").

För information om katalogiseringsregler som gäller vid auktoritetsarbete, se 
[Anvisningar för katalogisering (RDA) - Auktoritetsarbete.](http://www.kb.se/rdakatalogisering/Auktoritetsarbete// "Anvisningar för katalogisering (RDA) - Auktoritetsarbete")

För riktlinjer för löpande auktoritetsarbetet i Libris, se [Riktlinjer för det löpande auktoritetsarbetet i Libris](http://www.kb.se/dokument/Riktlinjer%20för%20det%20löpande%20auktoritetsarbetet%20i%20Libris.pdf). 



### Innehåll

| [Agent som Primär medverkan eller Medverkan](#agent-som-primär-medverkan-eller-medverkan)  | [Agent som Ämne](#agent-som-amne)
| ------ | ------- |
| [Länka till entitet](#agent-som-medverkan-och-funktion) | [Länka till entitet](#agent-som-amne) |
| [**Skapa lokal entitet**](#skapa-lokal-entitet) | [**Skapa lokal entitet**](#skapa-lokal-entitet) 
| [Person](#person) | [Person](#person)
| [Organisation](#organisation) | [Fiktiv gestalt](#fiktiv-gestalt) |
| [Jurisdiktion](#jurisdiktion) | [Organisation](#organisation) |
| [Släkt](#jurisdiktion) | [Jurisdiktion](#jurisdiktion) |
| [Möte](#jurisdiktion) | [Släkt](#jurisdiktion)
| | [Möte](#jurisdiktion) |


### Agent som Primär medverkan eller Medverkan

#### Länka till entitet

* Primär medverkan/Medverkan/Agent (contribution/PrimaryContribution/agent = 100, 110, 111, 700, 710, 711)
<br/>Vid Medverkan och funktion välj typ av medverkan i rullmenyn. Klicka på plustecknet vid Agent. Sök efter namnformen som ska länkas. Begränsa sökningen genom att välja typ av Agent. Länka genom att klicka på plustecknet vid Agenten.
<br/>```Exempel:```
  * ```Lindgren, Astrid, 1907-2002```
  * ```Potter, Harry, (fiktiv gestalt)```
  * ```Arbetslivscentrum```
  * ```Sverige. Landsbygdsdepartementet```
  * ```Hamrin (släkt: 1841-)```
  * ```Olympiska spelen, 2012```

* Primär medverkan/Medverkan/Funktion (contribution/PrimaryContribution/role = 100 ‡4, 110 ‡4, 700 ‡4, 710 ‡4)
<br/>Lägg till en funktionskod genom att klicka på plustecknet vid Funktion. Sök efter en funktionskod och länka genom att klicka på plustecknet.
<br/>```Exempel:```
  * ```Författare, aut```
  * ```Illustratör, ill```
  * ```Utgivare, pbl```

### Agent som Amne

#### Länka till entitet

* Ämne/Agent (subject/agent = 600, 610, 611)
<br/>Klicka på plustecknet vid Ämne. Sök efter namnformen som ska länkas. Begränsa sökningen genom att välja typ av Agent. Länka genom att klicka på plustecknet vid Agenten.
<br/>```Exempel:```
  * ```Lindgren, Astrid, 1907-2002```
  * ```Potter, Harry, (fiktiv gestalt)```
  * ```Arbetslivscentrum```
  * ```Sverige. Landsbygdsdepartementet```
  * ```Windsor (kungahus: 1917-)```
  * ```Olympiska spelen, 2012```
    

### Skapa lokal entitet

#### Person

* Person som Primär medverkan/Medverkan (contribution/PrimaryContribution/agent/Person = 100 1/ , 700 1/ )
<br/>Vid Medverkan och funktion välj typ av medverkan i rullmenyn. Klicka på plustecknet vid Agent och välj Person i rullmenyn för Skapa lokal entitet. Skriv in korrekt namnform.
 <br/>```Exempel: Efternamn: Wigg samt Förnamn: Susan```
 <br/>För personnamn i rak följd. Klicka på plustecknet vid Person och välj egenskapen Namn. Skriv in uppgiften.
 <br/>```Exempel: Namn: Sigfús Daðason```
  
* Person som Ämne (Subject/agent/Person = 600 1/4)
<br/>Klicka på plustecknet vid Ämne och välj Person i rullmenyn för Skapa lokal entitet. Skriv in korrekt namnform.
 <br/>```Exempel: Efternamn: Goodman samt Förnamn: Amy```
 <br/>För personnamn i rak följd. Klicka på plustecknet vid Person och välj egenskapen Namn. Skriv in korrekt namnform.
 <br/>```Exempel: Namn: Madonna samt Födelsetid och/eller dödstid: 1958-```
 
 #### Fiktiv gestalt

* Fiktiv gestalt som Ämne (Subject/agent/Person = 600 1/4)
<br/>Klicka på plustecknet vid Ämne och välj Person i rullmenyn för Skapa lokal entitet. Ange personnamnet enligt samma princip som för en verklig person. Tillägget "(fiktiv gestalt)" läggs till via egenskapen Titel eller övrig beteckning.
  <br/>```Exempel:```
  * ```Namn: Bambi samt Titel eller övrig beteckning (fiktiv gestalt)```
  * ```Efternamn: Granger samt Förnamn: Hermione samt Titel eller övrig beteckning (fiktiv gestalt)```

#### Organisation

* Organisation i ett led som Primär medverkan/Medverkan (contribution/PrimaryContribution/agent/Organization = 110 2/ , 710 2/ )
<br/>Vid Medverkan och funktion välj typ av medverkan i rullmenyn. Klicka på plustecknet vid Agent och välj Organisation i rullmenyn för Skapa lokal entitet. Skriv in korrekt namnform.
  <br/>```Exempel: Namn: Västerbottens läns hushållningssällskap```

* Organisation i flera led som Primär medverkan/Medverkan (contribution/PrimaryContribution/agent/Organization = 110 2/ , 710 2/ )
<br/>Vid Medverkan och funktion välj typ av medverkan i rullmenyn. Klicka på plustecknet vid Agent och välj Organisation i rullmenyn för Skapa lokal entitet. Klicka på plustecknet vid Organisation och lägg till egenskaperna Är del av samt Namn på underordnad enhet. Klicka på plustecknet vid egenskapen Är del av och välj återigen Organisation i rullmenyn för Skapa lokal entitet. Skriv in korrekt namnform.
<br/>```Exempel: Organisation/Är del av/Organisation/Namn: Karolinska universitetssjukhuset samt Organisation/Namn på underordnad enhet: Ekonomiavdelningen```
<br/>OBS! Det fungerar inte att konstruera namnformer i fler än två led i nuläget.

* Organisation i ett led som Ämne (Subject/agent/Organization = 610 2/4)
<br/>Klicka på plustecknet vid Ämne och välj Organisation i rullmenyn för Skapa lokal entitet. Skriv in korrekt namnform.
  <br/>```Exempel: Namn: Kastelholms slott```

* Organisation i flera led som Ämne (Subject/agent/Organization = 610 2/4)
<br/>Klicka på plustecknet vid Ämne och välj Organisation i rullmenyn för Skapa lokal entitet. Klicka på plustecknet vid Organisation och lägg till egenskaperna Är del av samt Namn på underordnad enhet. Klicka på plustecknet vid egenskapen Är del av och välj återigen Organisation i rullmenyn för Skapa lokal entitet. Skriv in korrekt namnform.
<br/>```Exempel: Organisation/Är del av/Organisation/Namn: Göteborgs universitet samt Organisation/Namn på underordnad enhet: Rättsvetenskapliga institutionen```
<br/>OBS! Det fungerar inte att konstruera namnformer i fler än två led i nuläget.

#### Jurisdiktion

* Jurisdiktion i ett led som Primär medverkan/Medverkan (contribution/PrimaryContribution/agent/Jurisdiction = 110 1/ , 710 1/ )
<br/>Vid Medverkan och funktion välj typ av medverkan i rullmenyn. Klicka på plustecknet vid Agent och välj Jurisdiktion i rullmenyn för Skapa lokal entitet. Skriv in korrekt namnform.
  <br/>```Exempel: Namn: Löddeköping kommun (Sverige)```

* Jurisdiktion i flera led som Primär medverkan/Medverkan (contribution/PrimaryContribution/agent/Jurisdiction = 110 1/ , 710 1/ )
<br/>Vid Medverkan och funktion välj typ av medverkan i rullmenyn. Klicka på plustecknet vid Agent och välj Jurisdiktion i rullmenyn för Skapa lokal entitet. Klicka på plustecknet vid Jurisdiktion och lägg till egenskaperna Är del av samt Namn på underordnad enhet. Klicka på plustecknet vid egenskapen Är del av och välj återigen Jurisdiktion i rullmenyn för Skapa lokal entitet. Skriv in uppgiften.
<br/>```Exempel: Jurisdiktion/Är del av/Jurisdiktion/Namn: Vänersborgs kommun (Sverige) samt Jurisdiktion/Namn på underordnad enhet: Socialförvaltningen```
<br/>OBS! Det fungerar inte att konstruera namnformer i fler än två led i nuläget.

* Jurisdiktion i ett led som Ämne (Subject/agent/Jurisdiction = 610 1/4)
<br/>Klicka på plustecknet vid Ämne och välj Jurisdiktion i rullmenyn för Skapa lokal entitet. Skriv in korrekt namnform.
   <br/>```Exempel: Namn: Norra Råda kommun (Sverige)```

* Jurisdiktion i flera led som Ämne (Subject/agent/Jurisdiction = 610 1/4)
<br/>Klicka på plustecknet vid Ämne och välj Jurisdiktion i rullmenyn för Skapa lokal entitet. Klicka på plustecknet vid Jurisdiktion och lägg till egenskaperna Är del av samt Namn på underordnad enhet. Klicka på plustecknet vid egenskapen Är del av och välj återigen Jurisdiktion i rullmenyn för Skapa lokal entitet. Skriv in korrekt namnform.
<br/>```Exempel: Jurisdiktion/Är del av/Jurisdiktion/Namn: Storbritannien samt Jurisdiktion/Namn på underordnad enhet: Foreign Office```
<br/>OBS! Det fungerar inte att konstruera namnformer i fler än två led i nuläget.

#### Släkt

* Släkt som Primär medverkan/Medverkan (contribution/PrimaryContribution/agent/Family = 100 3/ , 700 3/ )
<br/>Vid Medverkan och funktion välj typ av medverkan i rullmenyn. Klicka på plustecknet vid Agent och välj Släkt i rullmenyn för Skapa lokal entitet. Skriv in korrekt namnform.
  <br/>```Exempel: Namn: Ibsen (släkt)```
  
* Släkt som Ämne (Subject/agent/Family = 600 3/ )
<br/>Klicka på plustecknet vid Ämne och välj Släkt i rullmenyn för Skapa lokal entitet. Skriv in korekt namnform.
  <br/>```Exempel: Namn: Tiger (släkt) samt Födelsetid och/eller dödstid: 1600-talet```

#### Möte

* Möte som Primär medverkan/Medverkan (contribution/PrimaryContribution/agent/Meeting = 111 2/ , 711 2/ )
<br/>Vid Medverkan och funktion välj typ av medverkan i rullmenyn. Klicka på plustecknet vid Agent och välj Möte i rullmenyn för Skapa lokal entitet. Skriv in korrekt namnform.
  <br/>```Exempel: Namn: International Congress of Byzantine Studies samt Datum: 2006 samt Ordningstal: 21```

* Möte som Ämne (Subject/agent/Meeting = 611 2/ )
<br/>Klicka på plustecknet vid Ämne och välj Möte i rullmenyn för Skapa lokal entitet. Skriv in korrekt namnform.
 <br/>```Exempel: Namn: Nationella cykelhjälmskonferensen samt Datum: 1999 samt Ordningstal: 2```

  
