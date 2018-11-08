
UNDER ARBETE (uppdaterad 2018-11-08)

## Lägga till Agenter i Instans av verk

Hjälptexten beskriver hur man lägger till Agenter vid Medverkan och funktion samt som Ämne. Saknas egenskaper för Medverkan och Funktion eller Ämne läggs de till genom att klicka på plustecknet vid Text.

Var noggrann vid sökning efter Agenten och länka om möjligt. Vid behov skapa ny Agent. Använd de mallar som finns vid Skapa ny - Agent tillsammans med de hjälptexter för Agenter som finns i Hjälpsektion. I undantagsfall, skapas lokal entitet enligt nedan.

För information om katalogregler, skrivregler och övriga katalogiseringsanvisningar, se [Anvisningar för katalogisering - RDA](http://www.kb.se/rdakatalogisering/Anvisningar/ "Anvisningar för katalogisering - RDA").

För information om katalogiseringsregler som gäller vid auktoritetsarbete, se 
[Anvisningar för katalogisering (RDA) - Auktoritetsarbete.](http://www.kb.se/rdakatalogisering/Auktoritetsarbete// "Anvisningar för katalogisering (RDA) - Auktoritetsarbete")


### Innehåll


| [Agenter som Medverkan](#agenter-som-medverkan) | [Agenter som Ämne](#agenter-som-amne)
| ------ | ----------- |
| [Länka Medverkan](#agenter-som-medverkan) | [Länka Ämne](#lanka-amne) |
| [Länka Funktion](#agenter-som-medverkan) |
| [**Skapa lokal entitet**](#skapa-lokal-entitet) | [**Skapa lokal entitet**](#skapa-lokal-entitet)
| [Person som Medverkan](#person-som-medverkan) | [Person som Ämne](#namn) |
| [Organisation i ett led som Medverkan](#organisation-i-ett-led-som-medverkan) | [Fiktiv gestalt som Ämne](#verksamhetens-starttid) |
| [Organisation i flera led som Medverkan](#organisation-i-flera-led-som-medverkan) | [Organisation i ett led som Ämne](#organisation-i-ett-led-som-amne) |
| [Jurisdiktion i ett led som Medverkan](#jurisdiktion-i-ett-led-som-medverkan) | [Organisation i flera led som Ämne](#organisation-i-flera-led-som-amne) |
| [Jurisdiktion i flera led som Medverkan](#jurisdiktion-i-flera-led-som-medverkan) | [Jurisdiktion i ett led som Ämne](#jurisdiktion-i-ett-led-som-amne) |
| [Släkt som Medverkan](#slakt-som-medverkan) | [Jurisdiktion i flera led som Ämne](#jurisdiktion-i-flera-led-som-amne) |
| [Möte som Medverkan](#mote-som-medverkan) | [Släkt som Ämne](#slakt-som-amne) |
| [X](#x) | [Möte som Ämne](#mote-som-amne) | |
| | [X](#x) | |
 


### Agenter som Medverkan

#### Länka Medverkan
* Länka Medverkan (100,110,111,700,710,711)
<br/>Vid Medverkan och funktion välj typ av medverkan i rullmenyn. Klicka sedan på plustecknet vid Agent. Sök efter Agenten som ska länkas. Begränsa sökningen genom att välja typ av Agent. Om det finns en agentpost länka genom att klicka på plustecknet vid Agenten.
<br/>```Exempel:```
  * ```Lindgren, Astrid, 1907-2002```
  * ```Arbetslivscentrum```
  * ```Windsor (kungahus:, 1917-)```
  * ```Sverige. Landsbygdsdepartementet```

#### Länka Funktion
* Länka Funktion (100 ‡4,110 ‡4,700 ‡4,710 ‡4)
<br/>Lägg till en funktionskod genom att klicka på plustecknet vid Funktion. Sök efter en funktionskod och länka genom att klicka på plustecknet.
<br/>```Exempel:```
  * ```Författare, aut```
  * ```Illustratör, ill```
  * ```Utgivare, pbl```

### Skapa lokal entitet

#### Person som Medverkan
* Person som medverkan (100 ‡a, 700 ‡a)

#### Organisation i ett led som Medverkan
* Organisation i ett led som medverkan (110 ‡a, 710 ‡a)
<br/>Vid Medverkan och funktion välj typ av medverkan i rullmenyn. Klicka på plustecknet vid Agent och välj Organisation i rullmenyn för Skapa lokal entitet. Skriv in namnet.
  <br/>```Exempel: Landsnora kvarn och såg```

#### Organisation i flera led som Medverkan
* Organisation i flera led som Medverkan (110 ‡a ‡b, 710 ‡a ‡b)
<br/>Vid Medverkan och funktion välj typ av medverkan i rullmenyn. Klicka på plustecknet vid Agent och välj Organisation i rullmenyn för Skapa lokal entitet. Ta bort egenskapen Namn med papperkorgen. Klicka istället på plustecknet vid Organisation och lägg till egenskaperna Är del av samt Namn på underordnad enhet. Klicka på plustecknet vid egenskapen Är del av och välj återigen Organisation i rullmenyn för Skapa lokal entitet. Skriv sedan in namnet.
<br/>```Exempel:```
  * ```Organisation/Är del av/Organisation/Namn: Stockholms universitet samt Organisation/Namn på underordnad enhet: Institutionen för folkhälsovetenskap```
  * ```Organisation/Är del av/Organisation/Namn: Svenska kyrkan samt Organisation/Namn på underordnad enhet: Högalids församling```
<br/>OBS! Det fungerar inte att göra namn i fler än två led i nuläget.

#### Jurisdiktion i ett led som medverkan
* Jurisdiktion i ett led som medverkan (710 ‡a)
<br/>Vid Medverkan och funktion välj typ av medverkan i rullmenyn. Klicka på plustecknet vid Agent och välj Jurisdiktion i rullmenyn för Skapa lokal entitet. Skriv in namnet.
  <br/>```Exempel: Stockholms stad (Sverige)```

#### Jurisdiktion i flera led som medverkan
* Jurisdiktion i flera led som medverkan (710 ‡a ‡b)
<br/>Vid Medverkan och funktion välj typ av medverkan i rullmenyn. Klicka på plustecknet vid Agent och välj Jurisdiktion i rullmenyn för Skapa lokal entitet. Ta bort egenskapen Namn med papperkorgen. Klicka istället på plustecknet vid Jurisdiktion och lägg till egenskaperna Är del av samt Namn på underordnad enhet. Klicka på plustecknet vid egenskapen Är del av och välj återigen Jurisdiktion i rullmenyn för Skapa lokal entitet. Skriv in namnet.
<br/>```Exempel:```
  * ```Jurisdiktion/Är del av/Jurisdiktion/Namn: Sverige samt Jurisdiktion/Namn på underordnad enhet: Högsta domstolen```
  * ```Jurisdiktion/Är del av/Jurisdiktion/Namn: Stockholms stad (Sverige) samt Jurisdiktion/Namn på underordnad enhet: Idrottsförvaltningen```
<br/>OBS! Det fungerar inte att göra namn i fler än två led i nuläget.

### Agenter som Ämne

#### Länka Ämne
* Länka Ämne (600,610,611)
<br/>Klicka sedan på plustecknet vid Ämne. Sök efter Agenten som ska länkas. Begränsa sökningen genom att välja typ av Agent. Om det finns en agentpost länka genom att klicka på plustecknet vid Agenten.
<br/>```Exempel:```
  * ```Lindgren, Astrid, 1907-2002```
  * ```Arbetslivscentrum```
  * ```Windsor (kungahus:, 1917-)```
  * ```Sverige. Landsbygdsdepartementet```

#### Organisation i ett led som Ämne
* Organisation i ett led som medverkan (610)
<br/>Klicka på plustecknet vid Ämne och välj Organisation i rullmenyn för Skapa lokal entitet. Skriv in namnet.
  <br/>```Exempel: Organisation/Namn: Landsnora kvarn och såg```

#### Olänkad Organisation som består av underordnad enhet (610 ‡a ‡b)
Klicka på plustecknet vid Ämne och välj Organisation i rullmenyn för Skapa lokal entitet. Klicka därefter på plustecknet vid  Organisation och lägg till egenskaperna Är del av samt Namn på underordnad enhet. Vid Är del av skapas lokal entitet Organisation och egenskapen Namn läggs till. Fyll sedan i organisationens namn och spara posten.
<br/>```Exempel: Organisation/Är del av/Organisation/Namn: Stockholms universitet samt Organisation/Namn på underordnad enhet: Institutionen för folkhälsovetenskap```


