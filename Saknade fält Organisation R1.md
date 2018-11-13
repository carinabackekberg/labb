
anmärkningar 4/10. Egenskaperna ligger kvar så länge.

Det går inte längre att länka mot svenska ämnesord vid Andra attribut för person- och organisationsnamn!

* Andra attribut för person- och organisationsnamn (marc:hasOtherAttributes = 368 ‡a ‡2)
  <br/>Ange en term för att beskriva typ av organisation om det använts som särskiljande tillägg i den auktoriserade sökingången.
  <br/>```Exempel: Herrgårdar```
  <br/>Länka i första hand termen från en kontrollerad vokabulär som Svenska ämnesord. 
För att lägga till: Klicka på plustecknet vid egenskapen Andra attribut för person- och organisationsnamn, välj Allmänt ämnesord som typ vid sökning. Välj önskad term och klicka på plustecknet. (Skapa lokal entitet används endast då det inte finns auktoriserad entitet att länka till).

Det går inte längre att välja namn vid organisatorisk tillhörighet. Benämning istället?   
 
 * Organisatorisk tillhörighet (hasAffiliation = 373 ‡a)
  <br/>Här är det möjligt att ange en samhörande institution.
  <br/>```Exempel: Uppsala universitet``` 
  <br/>För att lägga till: Klicka på plustecknet vid egenskapen Organisatorisk tillhörighet, och skapa lokal entitet t ex organisation. Lägg sedan till den egenskap som behövs t ex namn. OBS! Organisatorisk tillhörighet ska inte göras till sökbar länk.
 
 Egenskap utlyft 2/5

* Förknippad plats (hasAssociatedPlace/associatedCountry = 370 ‡c)?
  <br/>Anges vid behov. Länka till entitet
  <br/>```Exempel: Sverige```
  
Tabell med tre spalter

### Innehåll

| [Adminmetadata](#adminmetadata) | [Agent](#agent) | [Valbara egenskaper att lägga till i Agent](#valbara-egenskaper-att-lägga-till-i-Agent) | 
| ------ | ----------- |  ----------- |
| [Skapad av](#skapad-av) | [Namn](#namn) | [Verkets titel](#verkets-titel) |
| [Katalogiseringsregler](#katalogiseringsregler) | [Namn i två led](#namn-i-två-led) | [Språk](#språk) |
| [Katalogiseringsspråk](#katalogiseringsspråk) | [Verksamhtens starttid](#verksamhetens-starttid) | [Medverkan och funktion](#medverkan-och-funktion) |
| [Translitterering](#translitterering) | [Verksamhetens sluttid](#verksamhetens-sluttid) | [Klassifikation](#klassifikation) |
| [Poststatus](#poststatus) | [Administrativ historik](#administrativ-historik) | [Ämne](#amne) |
| [Katalogisatörens anmärkning](#katalogisatörens-anmärkning) | [Variant](#variant) | [Genre](#genre) |
| [Konsulterad källa](#konsulterad-källa) | [Se även](#se-även) | [Innehållstyp](#innehållstyp) |
| [Uppdatering av posten](#uppdatering-av-posten) | [Identifikator](#identifikator) | |
| [Differentiering av person](#differentiering-av-person) | [Nationalitet eller verksamhetsland](#nationalitet-eller-verksamhetsland) | |
| [Auktoritetskontrollnivå](#auktoritetskontrollnivå) |
| | [**Valbara egenskaper att lägga till i Agent**](#valbara-egenskaper-att-lägga-till-i-Agent) |
| | [Mått](#mått) | |
| | [Bilagor](#bilagor) | |
| | [Medietyp](#medietyp) | |
| | [Bärartyp](#bärartyp) | |
|  | [Seriemedlemskap](#seriemedlemskap) | |
| | [Anmärkning](#anmärkning) | |
|  | [Innehållsanmärkning](#innehållsanmärkning) | |
| | [Målgrupp](#målgrupp) | |
| | [Annat bärarformat](#annat-bärarformat) | | 




3/5 innan ändring inför test, vecka 22

UNDER ARBETE

## Skapa ny: Agent - Organisation

Lathunden beskriver de fält som finns representerade i mallen. Om något av fälten i mallen inte behövs kan de raderas genom ett klick på papperskorgsikonen intill fältet. Ett urval av fält kopplade till organisation som är möjliga att lägga till, men som inte finns i mallen, beskrivs i slutet av lathunden.

OBS! Var noggrann vid sökning/testlänkning för att säkerställa att auktoriserad namnform inte redan finns. Glöm inte att redigera Adminmetadata och spara innan vidare navigation i verktyget.

Exemplet nedan är baserat på Arbetslivscentrum. Tillägg kan vara fiktiva och enbart med som exempel.

### Mall för beskrivning av Agent - Organisation

Beskrivning av agenten som ska auktoriseras.

* Namn (name) (110 ‡a)
  <br/>Föredragen namnform som utgör den auktoriserade namnformen. För namnformer som består av överordnad och underordnad enhet används istället fälten Är del av/namn tillsammans med Namn på underordnad enhet. Dessa fält beskrivs under rubriken Valbara fält som inte ingår i mallen.
  <br/>```Exempel: Arbetslivscentrum```
  
* Variant (hasVariant = 410 ‡a samt 410 ‡a ‡b)
  <br/>I detta fält anges variantnamn och alternativa namnformer som stavningsvarianter, förkortningar etc. Fältet upprepas om flera variantnamn behöver läggas till.
  <br/>```Exempel: ALC```
  <br/>```Exempel: Swedish Centre for Working Life```
  <br/>För att lägga till fält: Klicka på +ikonen under egenskapen variant, och skapa lokal entitet t ex organisation. Lägg sedan till de fält som behövs t ex namn. 
  <br/>För att ange auktoriserad namnform som består av underordnad enhet: Klicka på +ikonen under egenskapen variant, och skapa lokal entitet organisation. Till organisation läggs, genom att klicka på +ikonen längst ut till höger vid organisation, fälten Är del av samt Namn på underordnad enhet. Vid Är del av skaps lokal entitet Organisation och fältet Namn läggs till.
  <br/>```Exempel: Är del av/Organisation /Namn: Stockholm University samt Namn på underordnad enhet: Centre for Medieval Studies```
  <br/>OBS! Varianter ska inte göras till sökbara länkar.
    
  
### Ett urval valbara fält för Agent- Organisation
Följande fält är möjliga att lägga till för organisation. Nya fält läggs till med hjälp av +Fält-ikonen.

* Är del av/Namn (isPartOf/name = 110 2/- ‡a)
  <br/>Överordnat namn i en auktoriserad namnform som består av underordnad enhet. Fältet används endast tillsammans med Namn på underordnad enhet.
  <br/>```Exempel: Stockholms universitet```
  <br/>För att lägga till fält: Klicka på +ikonen under egenskapen Är del av, och skapa lokal entitet organisation. Lägg sedan till fältet Namn.
  
* Namn på underordnad enhet (marc/subordinateUnit =110 2/- ‡b)
  <br/>Underordnade och relaterade organisationer som ska anges som underavdelning. Kännetecknande kan vara att namnet är osjälvständigt och det överordnade begreppet behövs för att man med säkerhet ska kunna identifiera organisationen. Namn på underordnad enhet ingår i den auktoriserade namnformen. Fältet används endast tillsammans med Är del av.
  <br/>```Exempel: Centrum för medeltidsstudier```
  
 
 
 
  
  UNDER ARBETE (uppdaterad 2018-11-06)

## Lägga till Agent - Organisation i Instans av Verk

Utgå från Instans av verk. Hjälptexten beskriver hur man lägger till såväl länkad som olänkad Organisation. Det går att lägga till Organisation vid Medverkan och funktion (710) samt som Ämne (610). Saknas egenskaper för Medverkan och Funktion eller Ämne läggs de till genom att klicka på plustecknet vid Text.

Om det inte finns en Agent att länka mot finns två val. Gå till mallen för Agent - Organisation och skapa en ny Agent som sedan kan länkas in. Om ingen Agentpost skapas använd istället de egenskaper som behövs enligt nedan och skriv in namnet.

### Organisation som Medverkan och funktion (contribution)

#### Länkad Organisation
Vid Medverkan och funktion välj typ av medverkan i rullmenyn. Klicka därefter på plustecknet intill den tillagda egenskapen t ex Primär medverkan/Medverkan och välj Agent. Klicka på plustecknet intill Agent. Sök efter Organisationen. För att begränsa sökningen välj Organisation under Alla typer. Om det finns en auktoritetspost för organisationen kommer det nu bli möjligt att länka genom att klicka på plustecknet vid Organisationen.
  <br/>```Exempel: Arbetslivscentrum```

#### Olänkad Organisation i ett led (710 ‡a)
Vid Medverkan och funktion välj typ av medverkan i rullmenyn. Klicka på plustecknet intill den tillagda egenskapen för t ex Primär medverkan/Medverkan och välj Agent. Klicka på plustecknet intill Agent, välj Organisation i rullmenyn för Skapa lokal entitet. Klicka därefter på plustecknet vid Organisation och lägg till egenskapen Namn. Fyll i organisationens namn och spara posten.
  <br/>```Exempel: Organisation/Namn: Landsnora kvarn och såg```

#### Olänkad Organisation som består av underordnad enhet (710 ‡a ‡b)
Vid Medverkan och funktion välj typ av medverkan i rullmenyn. Klicka på plustecknet intill den tillagda egenskapen för t ex Primär medverkan/Medverkan och välj Agent. Klicka på plustecknet intill Agent, välj Organisation i rullmenyn för Skapa lokal entitet. Klicka därefter på plustecknet vid Organisation och lägg till egenskaperna Är del av samt Namn på underordnad enhet. Vid Är del av skapas lokal entitet Organisation och egenskapen Namn läggs till. Fyll sedan i organisationens namn och spara posten.
<br/>```Exempel: Organisation/Är del av/Organisation/Namn: Stockholms universitet samt Organisation/Namn på underordnad enhet: Institutionen för folkhälsovetenskap```

#### Funktionskod (710 ‡4)
Lägg även till en funktionskod genom att klicka på plustecknet vid Primär medverkan/Medverkan och välj Funktion. Klicka på plustecknet intill Funktion. Sök efter funktionskod t ex Utgivare. Länka funktionskoden genom att klicka på plustecknet.


### Organisation som Ämne (subject)

#### Länkad Organisation
Klicka på plustecknet vid Ämne. Sök efter Organisationen. För att begränsa sökningen välj Organisation under Alla typer. Om det finns en auktoritetspost för organisationen kommer det nu bli möjligt att länka genom att klicka på plustecknet vid Organisationen.
  <br/>```Exempel: Arbetslivscentrum```

#### Olänkad Organisation i ett led (610 ‡a)
Klicka på plustecknet vid Ämne och välj Organisation i rullmenyn för Skapa lokal entitet. Klicka därefter på plustecknet vid Organisation och lägg till egenskapen Namn. Fyll i organisationens namn och spara posten.
  <br/>```Exempel: Organisation/Namn: Landsnora kvarn och såg```

#### Olänkad Organisation som består av underordnad enhet (610 ‡a ‡b)
Klicka på plustecknet vid Ämne och välj Organisation i rullmenyn för Skapa lokal entitet. Klicka därefter på plustecknet vid  Organisation och lägg till egenskaperna Är del av samt Namn på underordnad enhet. Vid Är del av skapas lokal entitet Organisation och egenskapen Namn läggs till. Fyll sedan i organisationens namn och spara posten.
<br/>```Exempel: Organisation/Är del av/Organisation/Namn: Stockholms universitet samt Organisation/Namn på underordnad enhet: Institutionen för folkhälsovetenskap```




Kopia
UNDER ARBETE (uppdaterad 2018-11-13)

## Lägga till Agenter

Hjälptexten beskriver hur man lägger till Agenter vid Medverkan och funktion samt som Ämne i Instans av Verk. Saknas egenskaper för Medverkan och Funktion eller Ämne läggs de till genom att klicka på plustecknet vid Text.

Var noggrann vid sökning efter Agenten och länka om möjligt. Vid behov skapa ny Agent. Använd de mallar som finns vid Skapa ny - Agent tillsammans med de hjälptexter för Agenter som finns i Hjälpsektion. OBS! I nuläget finns det endast mallar för Agent Person och Agent Organisation.

Enligt de riktlinjer som finns för löpande auktoritetsarbetet i Libris skapas inte alltid auktoritetsposter, se [Riktlinjer för det löpande auktoritetsarbetet i Libris](http://www.kb.se/dokument/Riktlinjer%20för%20det%20löpande%20auktoritetsarbetet%20i%20Libris.pdf). För dessa fall följ anvisningarna nedan för att skapa olika typer av olänkade agenter.

För information om katalogregler, skrivregler och övriga katalogiseringsanvisningar, se [Anvisningar för katalogisering - RDA](http://www.kb.se/rdakatalogisering/Anvisningar/ "Anvisningar för katalogisering - RDA").

För information om katalogiseringsregler som gäller vid auktoritetsarbete, se 
[Anvisningar för katalogisering (RDA) - Auktoritetsarbete.](http://www.kb.se/rdakatalogisering/Auktoritetsarbete// "Anvisningar för katalogisering (RDA) - Auktoritetsarbete")


### Innehåll


| [Agenter som Medverkan](#agenter-som-medverkan) | [Agenter som Ämne](#agenter-som-amne)
| ------ | ----------- |
| [Länka Medverkan](#agenter-som-medverkan) | [Länka Ämne](#agenter-som-amne) |
| [Länka Funktion](#agenter-som-medverkan) |
| [**Skapa olänkad Agent**](#skapa-olänkad-agent) | [**Skapa olänkad Agent**](#skapa-olänkad-agent)
| [Person som Medverkan](#person-som-medverkan) | [Person som Ämne](#agenter-som-amne) |
| [Organisation som Medverkan](#organisation-i-ett-led-som-medverkan) | [Fiktiv gestalt som Ämne](#agenter-som-amne) |
| [Jurisdiktion som Medverkan](#jurisdiktion-som-medverkan) | [Organisation som Ämne](#organisation-som-amne) |
| [Släkt som Medverkan](#jurisdiktion-som-medverkan) | [Jurisdiktion som Ämne](#organisation-som-amne) |
| [Möte som Medverkan](#jurisdiktion-som-medverkan) | [Släkt som Ämne](#organisation-som-amne) |
| | [Möte som Ämne](#organisation-som-amne) |
 


### Agenter som Medverkan

#### Länka Medverkan
* Länka Medverkan (100, 110, 111, 700, 710, 711)
<br/>Vid Medverkan och funktion välj typ av medverkan i rullmenyn. Klicka på plustecknet vid Agent. Sök efter Agenten som ska länkas. Begränsa sökningen genom att välja typ av Agent. Länka genom att klicka på plustecknet vid Agenten.
<br/>```Exempel:```
  * ```Lindgren, Astrid, 1907-2002```
  * ```Potter, Harry, (fiktiv gestalt)```
  * ```Arbetslivscentrum```
  * ```Sverige. Landsbygdsdepartementet```
  * ```Windsor (kungahus: 1917-)```
  * ```Olympiska spelen, 2012```

#### Länka Funktion
* Länka Funktion (100 ‡4, 110 ‡4, 700 ‡4, 710 ‡4)
<br/>Lägg till en funktionskod genom att klicka på plustecknet vid Funktion. Sök efter en funktionskod och länka genom att klicka på plustecknet.
<br/>```Exempel:```
  * ```Författare, aut```
  * ```Illustratör, ill```
  * ```Utgivare, pbl```

### Skapa olänkad Agent

#### Person som Medverkan
* Person som medverkan (100 ‡a, 700 ‡a)
<br/>Vid Medverkan och funktion välj typ av medverkan i rullmenyn. Klicka på plustecknet vid Agent och välj Person i rullmenyn för Skapa lokal entitet. Skriv in namnet.
 <br/>```Exempel: Karlsson, Dag, 1940-```
 
#### Organisation som Medverkan

* Organisation i ett led som medverkan (110 ‡a, 710 ‡a)
<br/>Vid Medverkan och funktion välj typ av medverkan i rullmenyn. Klicka på plustecknet vid Agent och välj Organisation i rullmenyn för Skapa lokal entitet. Skriv in namnet.
  <br/>```Exempel: Västerbottens läns hushållningssällskap```

* Organisation i flera led som Medverkan (110 ‡a ‡b, 710 ‡a ‡b)
<br/>Vid Medverkan och funktion välj typ av medverkan i rullmenyn. Klicka på plustecknet vid Agent och välj Organisation i rullmenyn för Skapa lokal entitet. Ta bort egenskapen Namn med papperkorgen. Klicka istället på plustecknet vid Organisation och lägg till egenskaperna Är del av samt Namn på underordnad enhet. Klicka på plustecknet vid egenskapen Är del av och välj återigen Organisation i rullmenyn för Skapa lokal entitet. Skriv sedan in namnet.
<br/>```Exempel: Organisation/Är del av/Organisation/Namn: Karolinska universitetssjukhuset samt Organisation/Namn på underordnad enhet: Ekonomiavdelningen```
<br/>OBS! Det fungerar inte att göra namn i fler än två led i nuläget.

#### Jurisdiktion som Medverkan

* Jurisdiktion i ett led som medverkan (110 ‡a, 710 ‡a)
<br/>Vid Medverkan och funktion välj typ av medverkan i rullmenyn. Klicka på plustecknet vid Agent och välj Jurisdiktion i rullmenyn för Skapa lokal entitet. Skriv in namnet.
  <br/>```Exempel: Luleå kommun (Sverige)```

* Jurisdiktion i flera led som medverkan (110 ‡a ‡b, 710 ‡a ‡b)
<br/>Vid Medverkan och funktion välj typ av medverkan i rullmenyn. Klicka på plustecknet vid Agent och välj Jurisdiktion i rullmenyn för Skapa lokal entitet. Ta bort egenskapen Namn med papperkorgen. Klicka istället på plustecknet vid Jurisdiktion och lägg till egenskaperna Är del av samt Namn på underordnad enhet. Klicka på plustecknet vid egenskapen Är del av och välj återigen Jurisdiktion i rullmenyn för Skapa lokal entitet. Skriv in namnet.
<br/>```Exempel: Jurisdiktion/Är del av/Jurisdiktion/Namn: Vänersborgs kommun (Sverige) samt Jurisdiktion/Namn på underordnad enhet: Socialförvaltningen```
<br/>OBS! Det fungerar inte att göra namn i fler än två led i nuläget.

#### Släkt som Medverkan
* Släkt som Medverkan (100, 700)
<br/>Vid Medverkan och funktion välj typ av medverkan i rullmenyn. Klicka på plustecknet vid Agent och välj Släkt i rullmenyn för Skapa lokal entitet. Skriv in namnet.
  <br/>```Exempel: Ibsen (släkt)```
  
#### Möte som Medverkan
* Möte som Medverkan (111, 711)
<br/>Vid Medverkan och funktion välj typ av medverkan i rullmenyn. Klicka på plustecknet vid Agent och välj Möte i rullmenyn för Skapa lokal entitet. Skriv in namnet.
  <br/>```Exempel: Namn: International Congress of Byzantine Studies samt Datum: 2006 samt Ordningstal: 21```
  <br/>OBS! Det fungerar inte att lägga till Plats för mötet i nuläget.

### Agenter som Amne

#### Länka Ämne
* Länka Ämne (600, 610, 611)
<br/>Klicka på plustecknet vid Ämne. Sök efter Agenten som ska länkas. Begränsa sökningen genom att välja typ av Agent. Länka genom att klicka på plustecknet vid Agenten.
<br/>```Exempel:```
   * ```Lindgren, Astrid, 1907-2002```
  * ```Potter, Harry, (fiktiv gestalt)```
  * ```Arbetslivscentrum```
  * ```Sverige. Landsbygdsdepartementet```
  * ```Windsor (kungahus: 1917-)```
  * ```Olympiska spelen, 2012```
  
#### Person som Ämne
* Person som Ämne (600)
<br/>Klicka på plustecknet vid Ämne och välj Person i rullmenyn för Skapa lokal entitet. Skriv in namnet.
 <br/>```Exempel: Goodman, Amy```

#### Fiktiv gestalt som Ämne
* Fiktiv gestalt som Ämne (600)
<br/>Klicka på plustecknet vid Ämne och välj Person i rullmenyn för Skapa lokal entitet. Ta bort de egenskaper som inte används med papperskorgen t ex Födelse och/eller dödstid. Lägg till Egenskapen Titel eller övrig beteckning för att ange (fiktiv gestalt) samt eventuellt egenskapen Namn istället för egenskaperna Efternamn samt Förnamn. Skriv in namnet.
  <br/>```Exempel:```
  * ```Namn: Bambi samt Titel eller övrig beteckning: (fiktiv gestalt)```
  * ```Efternamn/Förnamn: Granger, Hermione samt Titel eller övrig beteckning (fiktiv gestalt)```

#### Organisation som Amne
* Organisation i ett led som Ämne (610)
<br/>Klicka på plustecknet vid Ämne och välj Organisation i rullmenyn för Skapa lokal entitet. Skriv in namnet.
  <br/>```Exempel: Landsnora kvarn och såg```

* Organisation i flera led som Ämne (610 ‡a ‡b)
<br/>Klicka på plustecknet vid Ämne och välj Organisation i rullmenyn för Skapa lokal entitet. Ta bort egenskapen Namn med papperkorgen. Klicka istället på plustecknet vid Organisation och lägg till egenskaperna Är del av samt Namn på underordnad enhet. Klicka på plustecknet vid egenskapen Är del av och välj återigen Organisation i rullmenyn för Skapa lokal entitet. Skriv sedan in namnet.
<br/>```Exempel: Organisation/Är del av/Organisation/Namn: Göteborgs universitet samt Organisation/Namn på underordnad enhet: Rättsvetenskapliga institutionen```
<br/>OBS! Det fungerar inte att göra namn i fler än två led i nuläget.

#### Jurisdiktion som Ämne
* Jurisdiktion i ett led som Ämne (610)
<br/>Klicka på plustecknet vid Ämne och välj Jurisdiktion i rullmenyn för Skapa lokal entitet. Skriv in namnet.
  <br/>```Exempel: Luleå kommun (Sverige)```

* Jurisdiktion i flera led som Ämne (610 ‡a ‡b)
<br/>Klicka på plustecknet vid Ämne och välj Jurisdiktion i rullmenyn för Skapa lokal entitet. Ta bort egenskapen Namn med papperkorgen. Klicka istället på plustecknet vid Jurisdiktion och lägg till egenskaperna Är del av samt Namn på underordnad enhet. Klicka på plustecknet vid egenskapen Är del av och välj återigen Jurisdiktion i rullmenyn för Skapa lokal entitet. Skriv sedan in namnet.
<br/>```Exempel: Jurisdiktion/Är del av/Jurisdiktion/Namn: Åmåls kommun (Sverige) samt Jurisdiktion/Namn på underordnad enhet: Utbildningsförvaltningen```
<br/>OBS! Det fungerar inte att göra namn i fler än två led i nuläget.

#### Släkt som Ämne
* Släkt som Ämne (600)
<br/>Klicka på plustecknet vid Ämne och välj Släkt i rullmenyn för Skapa lokal entitet. Skriv in namnet.
  <br/>```Exempel: Tiger (släkt), 1600-talet```
  
#### Möte som Ämne
* Möte som Ämne (611)
<br/>Klicka på plustecknet vid Ämne och välj Möte i rullmenyn för Skapa lokal entitet. Skriv in namnet.
 <br/>```Exempel: Namn: Nationella cykelhjälmskonferensen samt Datum: 1999 samt Ordningstal: 2```
  <br/>OBS! Det fungerar inte att lägga till Plats för mötet i nuläget.
  
