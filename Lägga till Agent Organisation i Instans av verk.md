
UNDER ARBETE (uppdaterad 2018-11-16)

## Lägga till Agenter (byta rubrik?)

Hjälptexten beskriver hur man lägger till Agenter vid Medverkan och funktion samt som Ämne i Instans av Verk. Saknas egenskaper för Medverkan och Funktion eller Ämne läggs de till genom att klicka på plustecknet vid Text.

Var noggrann vid sökning efter Agenten och länka om möjligt. Vid behov skapa ny Agent. Använd de mallar som finns vid Skapa ny - Agent tillsammans med de hjälptexter för Agenter som finns i Hjälpsektion. OBS! I nuläget finns det endast mallar för Agent Person och Agent Organisation. Om ny Agent inte skapas använd Skapa lokal entitet.

För information om katalogregler, skrivregler och övriga katalogiseringsanvisningar, se [Anvisningar för katalogisering - RDA](http://www.kb.se/rdakatalogisering/Anvisningar/ "Anvisningar för katalogisering - RDA").

För information om katalogiseringsregler som gäller vid auktoritetsarbete, se 
[Anvisningar för katalogisering (RDA) - Auktoritetsarbete.](http://www.kb.se/rdakatalogisering/Auktoritetsarbete// "Anvisningar för katalogisering (RDA) - Auktoritetsarbete")

För riktlinjer för löpande auktoritetsarbetet i Libris, se [Riktlinjer för det löpande auktoritetsarbetet i Libris](http://www.kb.se/dokument/Riktlinjer%20för%20det%20löpande%20auktoritetsarbetet%20i%20Libris.pdf). 



### Innehåll

| [Agent som Medverkan och funktion](#agent-som-medverkan-och-funktion)  | [Agent som Ämne](#agent-som-amne)
| ------ | ------- |
| [Länka till entitet](#agent-som-medverkan-och-funktion) | [Länka till entitet](#agent-som-amne) |
| [**Skapa lokal entitet**](#skapa-lokal-entitet) | [**Skapa lokal entitet**](#skapa-lokal-entitet) 
| [Person](#person) | [Person](#person)
| [Organisation](#organisation) | [Fiktiv gestalt](#fiktiv-gestalt) |
| [Jurisdiktion](#jurisdiktion) | [Organisation](#organisation) |
| [Släkt](#jurisdiktion) | [Jurisdiktion](#jurisdiktion) |
| [Möte](#jurisdiktion) | [Släkt](#jurisdiktion)
| | [Möte](#jurisdiktion) |


### Agent som Medverkan och funktion

#### Länka till entitet

* Primär medverkan/Medverkan (100, 110, 111, 700, 710, 711)
<br/>Vid Medverkan och funktion välj typ av medverkan i rullmenyn. Klicka på plustecknet vid Agent. Sök efter Agenten som ska länkas. Begränsa sökningen genom att välja typ av Agent. Länka genom att klicka på plustecknet vid Agenten.
<br/>```Exempel:```
  * ```Lindgren, Astrid, 1907-2002```
  * ```Potter, Harry, (fiktiv gestalt)```
  * ```Arbetslivscentrum```
  * ```Sverige. Landsbygdsdepartementet```
  * ```Windsor (kungahus: 1917-)```
  * ```Olympiska spelen, 2012```

* Funktion (100 ‡4, 110 ‡4, 700 ‡4, 710 ‡4)
<br/>Lägg till en funktionskod genom att klicka på plustecknet vid Funktion. Sök efter en funktionskod och länka genom att klicka på plustecknet.
<br/>```Exempel:```
  * ```Författare, aut```
  * ```Illustratör, ill```
  * ```Utgivare, pbl```

### Agent som Amne

#### Länka till entitet

* Ämne (600, 610, 611)
<br/>Klicka på plustecknet vid Ämne. Sök efter Agenten som ska länkas. Begränsa sökningen genom att välja typ av Agent. Länka genom att klicka på plustecknet vid Agenten.
<br/>```Exempel:```
   * ```Lindgren, Astrid, 1907-2002```
  * ```Potter, Harry, (fiktiv gestalt)```
  * ```Arbetslivscentrum```
  * ```Sverige. Landsbygdsdepartementet```
  * ```Windsor (kungahus: 1917-)```
  * ```Olympiska spelen, 2012```
    

### Skapa lokal entitet

#### Person

* Person som Primär medverkan/Medverkan (100, 700)
<br/>Vid Medverkan och funktion välj typ av medverkan i rullmenyn. Klicka på plustecknet vid Agent och välj Person i rullmenyn för Skapa lokal entitet. Skriv in uppgiften.
 <br/>```Exempel: Wigg, Susan```
 
* Person som Ämne (600)
<br/>Klicka på plustecknet vid Ämne och välj Person i rullmenyn för Skapa lokal entitet. Skriv in uppgiften.
 <br/>```Exempel: Goodman, Amy```

#### Fiktiv gestalt

* Fiktiv gestalt som Ämne (600)
<br/>Klicka på plustecknet vid Ämne och välj Person i rullmenyn för Skapa lokal entitet. Ta bort de egenskaper som inte används med papperskorgen t ex Födelse och/eller dödstid. Lägg till Egenskapen Titel eller övrig beteckning för att ange (fiktiv gestalt) samt eventuellt egenskapen Namn istället för egenskaperna Efternamn samt Förnamn. Skriv in uppgiften.
  <br/>```Exempel:```
  * ```Namn: Bambi samt Titel eller övrig beteckning: (fiktiv gestalt)```
  * ```Efternamn/Förnamn: Granger, Hermione samt Titel eller övrig beteckning (fiktiv gestalt)```

#### Organisation

* Organisation i ett led som Primär medverkan/Medverkan (110, 710)
<br/>Vid Medverkan och funktion välj typ av medverkan i rullmenyn. Klicka på plustecknet vid Agent och välj Organisation i rullmenyn för Skapa lokal entitet. Skriv in uppgiften.
  <br/>```Exempel: Västerbottens läns hushållningssällskap```

* Organisation i flera led som Primär medverkan/Medverkan (110 ‡a ‡b, 710 ‡a ‡b)
<br/>Vid Medverkan och funktion välj typ av medverkan i rullmenyn. Klicka på plustecknet vid Agent och välj Organisation i rullmenyn för Skapa lokal entitet. Ta bort egenskapen Namn med papperkorgen. Klicka på plustecknet vid Organisation och lägg till egenskaperna Är del av samt Namn på underordnad enhet. Klicka på plustecknet vid egenskapen Är del av och välj återigen Organisation i rullmenyn för Skapa lokal entitet. Skriv in uppgiften.
<br/>```Exempel: Organisation/Är del av/Organisation/Namn: Karolinska universitetssjukhuset samt Organisation/Namn på underordnad enhet: Ekonomiavdelningen```
<br/>OBS! Det fungerar inte att göra namn i fler än två led i nuläget.

* Organisation i ett led som Ämne (610)
<br/>Klicka på plustecknet vid Ämne och välj Organisation i rullmenyn för Skapa lokal entitet. Skriv in uppgiften.
  <br/>```Exempel: Landsnora kvarn och såg```

* Organisation i flera led som Ämne (610 ‡a ‡b)
<br/>Klicka på plustecknet vid Ämne och välj Organisation i rullmenyn för Skapa lokal entitet. Ta bort egenskapen Namn med papperkorgen. Klicka på plustecknet vid Organisation och lägg till egenskaperna Är del av samt Namn på underordnad enhet. Klicka på plustecknet vid egenskapen Är del av och välj återigen Organisation i rullmenyn för Skapa lokal entitet. Skriv in uppgiften.
<br/>```Exempel: Organisation/Är del av/Organisation/Namn: Göteborgs universitet samt Organisation/Namn på underordnad enhet: Rättsvetenskapliga institutionen```
<br/>OBS! Det fungerar inte att göra namn i fler än två led i nuläget.

#### Jurisdiktion

* Jurisdiktion i ett led som Primär medverkan/Medverkan (110, 710)
<br/>Vid Medverkan och funktion välj typ av medverkan i rullmenyn. Klicka på plustecknet vid Agent och välj Jurisdiktion i rullmenyn för Skapa lokal entitet. Skriv in uppgiften.
  <br/>```Exempel: Löddeköping kommun (Sverige)```

* Jurisdiktion i flera led som Primär medverkan/Medverkan (110 ‡a ‡b, 710 ‡a ‡b)
<br/>Vid Medverkan och funktion välj typ av medverkan i rullmenyn. Klicka på plustecknet vid Agent och välj Jurisdiktion i rullmenyn för Skapa lokal entitet. Ta bort egenskapen Namn med papperkorgen. Klicka på plustecknet vid Jurisdiktion och lägg till egenskaperna Är del av samt Namn på underordnad enhet. Klicka på plustecknet vid egenskapen Är del av och välj återigen Jurisdiktion i rullmenyn för Skapa lokal entitet. Skriv in uppgiften.
<br/>```Exempel: Jurisdiktion/Är del av/Jurisdiktion/Namn: Vänersborgs kommun (Sverige) samt Jurisdiktion/Namn på underordnad enhet: Socialförvaltningen```
<br/>OBS! Det fungerar inte att göra namn i fler än två led i nuläget.

* Jurisdiktion i ett led som Ämne (610)
<br/>Klicka på plustecknet vid Ämne och välj Jurisdiktion i rullmenyn för Skapa lokal entitet. Skriv in uppgiften.
   <br/>```Exempel: Löddeköping kommun (Sverige)```

* Jurisdiktion i flera led som Ämne (610 ‡a ‡b)
<br/>Klicka på plustecknet vid Ämne och välj Jurisdiktion i rullmenyn för Skapa lokal entitet. Ta bort egenskapen Namn med papperkorgen. Klicka på plustecknet vid Jurisdiktion och lägg till egenskaperna Är del av samt Namn på underordnad enhet. Klicka på plustecknet vid egenskapen Är del av och välj återigen Jurisdiktion i rullmenyn för Skapa lokal entitet. Skriv in uppgiften.
<br/>```Exempel: Jurisdiktion/Är del av/Jurisdiktion/Namn: Åmåls kommun (Sverige) samt Jurisdiktion/Namn på underordnad enhet: Utbildningsförvaltningen```
<br/>OBS! Det fungerar inte att göra namn i fler än två led i nuläget.

#### Släkt

* Släkt som Primär medverkan/Medverkan (100, 700)
<br/>Vid Medverkan och funktion välj typ av medverkan i rullmenyn. Klicka på plustecknet vid Agent och välj Släkt i rullmenyn för Skapa lokal entitet. Skriv in uppgiften.
  <br/>```Exempel: Ibsen (släkt)```
  
* Släkt som Ämne (600)
<br/>Klicka på plustecknet vid Ämne och välj Släkt i rullmenyn för Skapa lokal entitet. Skriv in uppgiften.
  <br/>```Exempel: Tiger (släkt), 1600-talet```

#### Möte

* Möte som Primär medverkan/Medverkan (111, 711)
<br/>Vid Medverkan och funktion välj typ av medverkan i rullmenyn. Klicka på plustecknet vid Agent och välj Möte i rullmenyn för Skapa lokal entitet. Skriv in uppgiften.
  <br/>```Exempel: Namn: International Congress of Byzantine Studies samt Datum: 2006 samt Ordningstal: 21```
  <br/>OBS! Det fungerar inte att lägga till Plats för mötet i nuläget.

* Möte som Ämne (611)
<br/>Klicka på plustecknet vid Ämne och välj Möte i rullmenyn för Skapa lokal entitet. Skriv in uppgiften.
 <br/>```Exempel: Namn: Nationella cykelhjälmskonferensen samt Datum: 1999 samt Ordningstal: 2```
  <br/>OBS! Det fungerar inte att lägga till Plats för mötet i nuläget.
  
