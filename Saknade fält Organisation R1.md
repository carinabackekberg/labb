
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

