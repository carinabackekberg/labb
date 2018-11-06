
UNDER ARBETE (uppdaterad 2018-11-06)

## Lägga till Agenter i Instans av verk

Hjälptexten beskriver hur man lägger till Agenter vid Medverkan och funktion samt som Ämne. Saknas egenskaper för Medverkan och Funktion eller Ämne läggs de till genom att klicka på plustecknet vid Text.

Var noggrann vid sökning efter Agenten och länka om möjligt. Vid behov skapa ny Agent. Använd de mallar som finns vid Skapa ny - Agent tillsammans med de hjälptexter för Agenter som finns i Hjälpsektion. I undantagsfall, skapas lokal entitet enligt nedan.


### Innehåll


| [Agenter som Medverkan](#medverkan-och-funktion) | [Agenter som Ämne](#agenter-som-amne)
| ------ | ----------- |
| [Länka Medverkan](#lanka-medverkan) | [Länka Ämne](#lanka-amne) |
| [Länka Funktion](#lanka-funktion) |
| [**Skapa lokal entitet**](#skapa-lokal-entitet) | [**Skapa lokal entitet**](#skapa-lokal-entitet)
| [Person som Medverkan](#person) | [Person som Ämne](#namn) |
| [Organisation i ett led som Medverkan](#katalogiseringsregler) | [Fiktiv gestalt som Ämne](#verksamhetens-starttid) |
| [Organisation i flera led som Medverkan](#translitterering) | [Organisation i ett led som Ämne](#verksamhetens-sluttid) |
| [Jurisdiktion i ett led som Medverkan](#poststatus) | [Organisation i flera led som Ämne](#administrativ-historik) |
| [Jurisdiktion i flera led som Medverkan](#poststatus) | [Jurisdiktion i ett led som Ämne](#variant) |
| [Släkt som Medverkan](#poststatus) | [Jurisdiktion i flera led som Ämne](#variant) |
| [Möte som Medverkan](#uppdatering-av-posten) | [Släkt som Ämne](#identifikator) |
| [X](#differentiering-av-person) | [Möte som Ämne](#nationalitet) | |
| | [X](#tid-for-grundande) | |
 


### Agenter som Medverkan

#### Länka Medverkan (100,110,111,700,710,711)
Vid Medverkan och funktion välj typ av medverkan i rullmenyn. Klicka sedan på plustecknet intill Agent. Sök efter Agenten som ska länkas. Begränsa sökningen genom att välja typ av Agent. Om det finns en agentpost länka genom att klicka på plustecknet vid Agenten.
  <br/>```Exempel: Lindgren, Astrid, 1907-2002```
  <br/>```Exempel: Arbetslivscentrum```
  <br/>```Exempel: Windsor (kungahus:, 1917-)```
  <br/>```Exempel: Sverige. Landsbygdsdepartementet```
  

#### Länka Funktion (100,110,700,710 ‡4)
Lägg till en funktionskod genom att klicka på plustecknet intill Funktion. Sök efter en funktionskod och länka genom att klicka på plustecknet.
   <br/>```Exempel: Författare, aut)```
   <br/>```Exempel: Illustratör, ill)```
   <br/>```Exempel: Utgivare, pbl)```

### Skapa lokal entitet

#### Organisation i ett led som medverkan (110 ‡a, 710 ‡a)
Vid Medverkan och funktion välj typ av medverkan i rullmenyn. Klicka på plustecknet intill den tillagda egenskapen för t ex Primär medverkan/Medverkan och välj Agent. Klicka på plustecknet intill Agent, välj Organisation i rullmenyn för Skapa lokal entitet. Klicka därefter på plustecknet vid Organisation och lägg till egenskapen Namn. Fyll i organisationens namn och spara posten.
  <br/>```Exempel: Organisation/Namn: Landsnora kvarn och såg```

#### Organisation i flera led som Medverkan (110 ‡a ‡b, 710 ‡a ‡b)
Vid Medverkan och funktion välj typ av medverkan i rullmenyn. Klicka på plustecknet intill den tillagda egenskapen för t ex Primär medverkan/Medverkan och välj Agent. Klicka på plustecknet intill Agent, välj Organisation i rullmenyn för Skapa lokal entitet. Klicka därefter på plustecknet vid Organisation och lägg till egenskaperna Är del av samt Namn på underordnad enhet. Vid Är del av skapas lokal entitet Organisation och egenskapen Namn läggs till. Fyll sedan i organisationens namn och spara posten.
<br/>```Exempel: Organisation/Är del av/Organisation/Namn: Stockholms universitet samt Organisation/Namn på underordnad enhet: Institutionen för folkhälsovetenskap```


#### Olänkad Jurisdiktion som består av underordnad enhet (710 ‡a ‡b)
Vid Medverkan och funktion välj typ av medverkan i rullmenyn. Klicka på plustecknet intill den tillagda egenskapen för t ex Primär medverkan/Medverkan och välj Agent. Klicka på plustecknet intill Agent, välj Organisation i rullmenyn för Skapa lokal entitet. Klicka därefter på plustecknet vid Organisation och lägg till egenskaperna Är del av samt Namn på underordnad enhet. Vid Är del av skapas lokal entitet Organisation och egenskapen Namn läggs till. Fyll sedan i organisationens namn och spara posten.
<br/>```Exempel: Jurisdiktion/Är del av/Jurisdiktion/Namn: Sverige samt Jurisdiktion/Namn på underordnad enhet: Högsta domstolen```


### Agenter som Ämne

#### Länka Ämne

Klicka på plustecknet vid Ämne. Sök efter Organisationen. För att begränsa sökningen välj Organisation under Alla typer. Om det finns en auktoritetspost för organisationen kommer det nu bli möjligt att länka genom att klicka på plustecknet vid Organisationen.
  <br/>```Exempel: Arbetslivscentrum```

#### Olänkad Organisation i ett led (610 ‡a)
Klicka på plustecknet vid Ämne och välj Organisation i rullmenyn för Skapa lokal entitet. Klicka därefter på plustecknet vid Organisation och lägg till egenskapen Namn. Fyll i organisationens namn och spara posten.
  <br/>```Exempel: Organisation/Namn: Landsnora kvarn och såg```

#### Olänkad Organisation som består av underordnad enhet (610 ‡a ‡b)
Klicka på plustecknet vid Ämne och välj Organisation i rullmenyn för Skapa lokal entitet. Klicka därefter på plustecknet vid  Organisation och lägg till egenskaperna Är del av samt Namn på underordnad enhet. Vid Är del av skapas lokal entitet Organisation och egenskapen Namn läggs till. Fyll sedan i organisationens namn och spara posten.
<br/>```Exempel: Organisation/Är del av/Organisation/Namn: Stockholms universitet samt Organisation/Namn på underordnad enhet: Institutionen för folkhälsovetenskap```


