
UNDER ARBETE (uppdaterad 2018-11-06)

## Lägga till Agenter i Instans av verk

Hjälptexten beskriver hur man lägger till såväl länkade som olänkade Agenter vid Medverkan och funktion samt som Ämne. Saknas egenskaper för Medverkan och Funktion eller Ämne läggs de till genom att klicka på plustecknet vid Text.

Om det inte finns en Agent att länka mot finns två val. Gå till mallen för Agent - Organisation och skapa en ny Agent som sedan kan länkas in. Om ingen Agentpost skapas använd istället de egenskaper som behövs enligt nedan och skriv in namnet.


### Innehåll

| [Medverkan och funktion](#medverkan-och-funktion) | [Ämne](#amne) | 
| ------ | ----------- |
| [Länkad Person](#skapad-av) | [Länkad Person](#namn) |
| [Katalogiseringsregler](#katalogiseringsregler) | [Namn i två led](#namn) |
| [Katalogiseringsspråk](#katalogiseringsregler) | [Verksamhtens starttid](#verksamhetens-starttid) |
| [Translitterering](#translitterering) | [Verksamhetens sluttid](#verksamhetens-sluttid) |
| [Poststatus](#poststatus) | [Administrativ historik](#administrativ-historik) |
| [Katalogisatörens anmärkning](#poststatus) | [Variant](#variant) |
| [Konsulterad källa](#poststatus) | [Se även](#variant) |
| [Uppdatering av posten](#uppdatering-av-posten) | [Identifikator](#identifikator) |
| [Differentiering av person](#differentiering-av-person) | [Nationalitet](#nationalitet) | |
| [Auktoritetskontrollnivå](#differentiering-av-person) | [**Valbara egenskaper att lägga till i Agent**](#nationalitet) |
| [Beskrivningsnivå](#differentiering-av-person) | [Tid för grundande](#tid-for-grundande) | |
| | [Tid för upphörande](#tid-for-grundande) | |
| | [Verksamhetsområde](#tid-for-grundande) | |
| | [Språk](#tid-for-grundande) | |
| | [Andra attribut för person- och organisationsnamn](#tid-for-grundande) | |
| | [Organisatorisk tillhörighet](#tid-for-grundande) | |
 


### Medverkan och funktion

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

### Organisation som Medverkan och funktion (contribution)

#### Länkad Jurisdiktion
Vid Medverkan och funktion välj typ av medverkan i rullmenyn. Klicka därefter på plustecknet intill den tillagda egenskapen t ex Primär medverkan/Medverkan och välj Agent. Klicka på plustecknet intill Agent. Sök efter Organisationen. För att begränsa sökningen välj Organisation under Alla typer. Om det finns en auktoritetspost för organisationen kommer det nu bli möjligt att länka genom att klicka på plustecknet vid Organisationen.
  <br/>```Exempel: Sverige. Landsbygdsdepartementet```


#### Olänkad Jurisdiktion som består av underordnad enhet (710 ‡a ‡b)
Vid Medverkan och funktion välj typ av medverkan i rullmenyn. Klicka på plustecknet intill den tillagda egenskapen för t ex Primär medverkan/Medverkan och välj Agent. Klicka på plustecknet intill Agent, välj Organisation i rullmenyn för Skapa lokal entitet. Klicka därefter på plustecknet vid Organisation och lägg till egenskaperna Är del av samt Namn på underordnad enhet. Vid Är del av skapas lokal entitet Organisation och egenskapen Namn läggs till. Fyll sedan i organisationens namn och spara posten.
<br/>```Exempel: Jurisdiktion/Är del av/Jurisdiktion/Namn: Sverige samt Jurisdiktion/Namn på underordnad enhet: Högsta domstolen```


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


