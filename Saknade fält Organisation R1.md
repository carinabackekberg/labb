   
 utlyfta fält 2/5

* Förknippad plats (hasAssociatedPlace/associatedCountry = 370 ‡c)?
  <br/>Anges vid behov. Länka till entitet
  <br/>```Exempel: Sverige```
  


3/5 innan ändring inför test, vecka 19

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
  
* Variant (hasVariant = 410 ‡a)
  <br/>I detta fält anges variantnamn och alternativa namnformer som stavningsvarianter, förkortningar etc. Fältet upprepas om flera variantnamn behöver läggas till.
  <br/>```Exempel: ALC```
  <br/>```Exempel: Swedish Centre for Working Life```
  <br/>För att lägga till fält: Klicka på +ikonen under egenskapen variant, och skapa lokal entitet t ex organisation. Lägg sedan till de fält som behövs t ex namn eller flera fält t ex Är del av, och skapa lokal entitet Organisation, lägg sedan till fälten Namn och Namn på underordnad enhet. OBS! Varianter ska inte göras till sökbara länkar.
    
  
### Ett urval valbara fält för Agent- Organisation
Följande fält är möjliga att lägga till för organisation. Nya fält läggs till med hjälp av +Fält-ikonen.

* Är del av/Namn (isPartOf/name = 110 2/- ‡a)
  <br/>Överordnat namn i en auktoriserad namnform som består av underordnad enhet. Fältet används endast tillsammans med Namn på underordnad enhet.
  <br/>```Exempel: Handelshögskolan i Stockholm```
  <br/>För att lägga till fält: Klicka på +ikonen under egenskapen Är del av, och skapa lokal entitet organisation. Lägg sedan till fältet Namn.
  
* Namn på underordnad enhet (marc/subordinateUnit =110 2/- ‡b)
  <br/>Underordnade och relaterade organisationer som ska anges som underavdelning. Kännetecknande kan vara att namnet är osjälvständigt och det överordnade begreppet behövs för att man med säkerhet ska kunna identifiera organisationen. Namn på underordnad enhet ingår i den auktoriserade namnformen. Fältet används endast tillsammans med Är del av.
  <br/>```Exempel: Biblioteket```
