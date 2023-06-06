# Abstractica
## For Tobias &amp; Kim, Exam 2023


Tirsdag d. 31. januar
Introduktion til valgfaget, Abstractica. Teams blev lavet. Jeg var ikke fysisk til stede, hvorfor jeg ikke blev inddelt i nogen gruppe. Mit indtryk er at valgfaget er gået væk fra at arbejde i Aduino, men jeg har ikke fået spurgt om dette. 


Tirsdag d. 7. februar
Der er blevet lavet et par opgaver i forbindelse med projektet, Abstractica. Opgaverne er tildelt diverse teams. Ved siden af studiet skal vi føre disse logbooks der umiddelbart fungerer som studypoints. Jeg fik opdateret IntelliJ, clonet 'Abstractica' fra GitHub, og med hjælp fra Tobias fungerede koden (bygget og runnet) før jeg tog hjem. Tobias startede med at gennemgå JavaCSG. Derudover skal jeg vist have downloadet Prusa-slicer, som jeg kunne se var nævnt på Discord. 


Onsdag d. 8. februar
Jeg har brugte dagen i dag på at kigge lidt rundt i, hvad jeg synes, den komplekse Abstractica kode. CSG som Tobias talte om i går, har jeg lært står for Constructive Solid Geometry. Tobias bruger denne metode til at opbygge sine komplekse 3D-modeller ved hjælp af den kombination mellem geometriske former og sæt-operationer; snit, union og komplement. 


Torsdag d.9. februar 
Kort zoom-møde vedr. Lyngby-holdet og Bornholm-holdet som fejlagtig var blevet koblet sammen. Det blev besluttet at Lyngby-holdet holder sig til fysisk fremmøde om tirsdagen fra kl. 0900-12.30. Derudover vil der blive afholdt ekstra undervisningsdage når tiden tillader det. På tirsdag vil Tobias fortsætte gennemgangen af JavaCSG. 


Tirsdag d. 14. februar
I dag talte Tobias om SOLID, EDMA, og hvad der menes med de forskellige begreber. 
SOLID er et begreb der præsenterer fem designprincipper som anvendes i OOP. Her blev specielt den sidste, Dependency Inversion Principle diskuteret. Tobias fremlagde sit syn på princippet, blandt andet at de komplekse klasser bør være lige så afhængige af de mindre komplekse klasser. Hvis jeg forstod det korrekt. DIP lægger vægt på at komplekse klasser ikke skal være afhængige af de lav komplekse klasser, men i stedet afhænge af abstraktioner (koncepter og interfaces). På denne måde sikre man, at man kan ændre på de mindst komplekse klasser uden at det skal påvirke de højniveauklasser. 


Tirsdag d. 21. februar
Mit barn var syg, og desværre var der ikke online undervisning, hvorfor jeg ikke kunne følge med denne dag.


Tirsdag d. 28. februar
Undervisning aflyst.

Tirsdag d. 7. marts
I dag ser jeg en video om abstraktioner lavet af Tobias. Video:
https://cphbusiness.cloud.panopto.eu/Panopto/Pages/Viewer.aspx?id=8b446229-0d37-457a-96c2-afba01133eea
- Noter fra videoen:
-- Abstraktion i programmering: Værktøjer til at skjule detaljer for at gøre ting simplere. Hvis man laver noget der er abstrakt, gør man sig uafhængig af detaljer.
-- Domænemodel: Interfaces kan ”visualisere” en domænemodel, og være up2date med koden. 
…


Tirsdag d. 14. marts 
Gennemgik kode, og Tobias fortalte om Factory pattern som han har gjort brug af i hans kode. Factory pattern… Som jeg kan forstå, giver det udvikleren lov til at være meget fleksibel med sin kode f.eks. når man vil oprette objekter, så vil fabriksklassen tage sig af dette. 
Nedenstående skærmbillede af Tobias’ kode. I stedet for at oprette objektet direkte i koden, så bliver det oprettet indirekte via metoden i fabriksklassen. 
![kodesnit](https://github.com/swes42/Abstractica/assets/69907277/244667f3-efb3-4f80-a439-3f7dee48329f)
 
Jeg synes det er virkelig svært at ændre mit mindset fra facade-mønsteret til factory-mønsteret. Hver uge skulle vi aflevere nye programmeringsopgaver i dette designmønster, så jeg er meget vant til det og for mit vedkommende giver det umiddelbart bedst overblik. 
I og med at jeg synes Tobias’ system allerede er lidt komplekst at sætte sig ind i, kunne jeg godt se en fordel ved at have brugt facade-mønsteret fremfor factory. Men det skulle kun være til egen fordel, hvis jeg skulle ”lave videre” på koden… Dog har jeg læst, at factory-designet skulle være nemt at tilgå. Så jeg tror kun der er tale om vanesag. 


Fredag d. 17. marts
Privat zoom-møde m. Kim om privat situation. Vi kom frem til at jeg kan arbejde på Abstracticas community del, og d. 27. marts har vi møde om design og kravspecifikation. Til næste møde m. Kim, skal jeg undersøge internettet mhp. inspiration. Kim foreslog www.thingiverse.com, og hjemmesider der relaterede dertil. Rigtig rart at få ro på oven i kasketten og føle at jeg kunne bidrage med noget. Jeg har følt mig meget alene på studiet, og ikke kunne finde en struktur som jeg følte mig tryg ved – før samtalen med Kim, og det vi planlagde. 


Tirsdag d. 21. marts 
Gennemgang af spilleopgaven, hvor 2 studerende viste deres kode på skærmen. Herefter talte vi om den typiske domænemodel, og fordele og ulemper ved brug af UML-værktøjet. Tobias talte om, at fordelen var en god oversigt af ens lag i koden - ulempen kunne være, at det typisk IKKE stemmer overens med ens kode netop af den grund, at man kommer til at ændre i sin kode, men glemmer ændringen i domænemodellen. Hvilket jeg er meget enig i og prøvet før mange gange. Derfor fremlagde Tobias, at man kunne gøre klasserne op i interfaces. Interfacene samles i en package, og vil på denne måde være domænemodellen. Og man vil derfor ikke komme ud for uoverensstemmelse, i og med, at koden ikke vil compile hvis der er fejl. I denne forbindelse startede Tobias et projekt (Game Lobby/Game server) ud fra Factory Design. Til slut gav Tobias en status på byggesystemet. 


D. 22. marts til 28. marts
Undersøgt nettet for lignende sider som Abstracticas også gerne skulle ende ud som, dertil lavede en lille smule funktionelle krav.


Mandag d. 27. marts
Mødet rykket til tirsdag d. 28 kl.13.30 på zoom.
Tirsdag d. 28. marts
Til at præsentere for Kim, har jeg oprettet et whiteboard hvor jeg har indsat nogen screenshots af forskellige hjemmesider jeg synes der minder om Thingiverse, og som kunne være inspiration til skabningen af Abstractica siden. Hjemmesider jeg har kigget på er;
Thingiverse.com, Pinshape.com, Thangs.com, YouMagine.com, Printables.com, MyMiniFactory.com, GrabCAD.com… listen kunne blive lang. 😊 
Derudover har jeg oprettet et Word dokument "Kravspecifikation Abstractica", hvori jeg har skrevet om scope, funktionelle krav herunder tænkt over use cases, prioriteret de enkelte use cases og udarbejdet et use case diagram over de 4 vigtigste funktioner vha. UML-værktøjet. Til næste gang vil jeg gerne have lavet fully dressed på én eller flere use cases, og dertil måske lave en user story på en use case for netop at gøre det "let tilgængeligt" for en læser udefra, at forstå hvad man gerne vil have systemet til at gøre. Dertil vil jeg nok også have skrevet om ikke-funktionelle krav, og måske have lavet et mock-up af Abstractica hjemmesiden?
  
Efter mødet
Kim hjalp med at indsnævre hvad fokus ville være til opstart af hjemmesiden, som var CRUD posts. Hvilket gav god mening. Jeg har tænkt for meget i sikkerheds-banerne, og hvilke rettigheder den enkelte bruger skulle have. Men som Kim sagde, kunne jeg blot lave en dummy-hjemmeside. Til mødet havde jeg trælse problemer med min computer, hvilket jeg håber vil være fikset inden næste møde som blev efter påskeferien; 14.april kl. 1330. Vi aftalte at jeg skulle lave et mockup af hjemmesiden.


Tirsdag d. 11. april
Kim holder oplæg om forretningsmæssige aspekter af automatisering. Spændende emne at tale om fordi det er så relevant. Vi skulle se https://www.youtube.com/watch?v=hIXhnWUmMvw&t=924s, og herefter drøfte videoklippet Kim fortalte om en løn-situation han havde oplevet, hvor han skulle betale for at arbejde. Og dét med at vi tit og ofte stoler for meget på automatiseringen – og en god opfordring til altid at stille sig kritisk. Kim fortalte også om hvad der kunne hjælpe virksomheder til digitalisering.


Fredag d. 14. april
Pc-problemer gjorde at jeg ikke kunne vise Kim mit mockup, og jeg tegnede derfor mockup i hånden. Kim synes det var et fedt forslag, og ville gerne have at jeg kunne prøve at lave en mockup på en app til næste møde som blev; 25. april kl. 12.30. Derudover synes han også at jeg skulle prøve at lave et logo, hvilket kunne være meget sjov at lege med. Til logo-delen bruger jeg min computers indbyggede tegneprogram der hedder; paint 3d. Til mockup benytter jeg hjemmesiden; wondershare.com. 


Tirsdag d. 18. april
Hovedopgave kickoff lå samme dag som undervisning hvorfor jeg var fraværende.
Jeg skrev til én fra klassen, hvad det havde handlet om i dag. Vedkommende svarede at det havde været svært og avanceret 3D-modellering der var blevet vist. Og at det havde set en video omkring PrusaSlicer. 


D. 14. april til 25. april 
Arbejdes med mockup af app + hjemmelavet logo. 


Tirsdag d. 25. april
Tobias sagde at vi skulle undersøge hjemmesiden Stemfie.org og prøve at printe quick-print samples ud. Printeren skulle først varmes op til 215 grader, og markerer sine levels. Derefter downloadede jeg 3mf filen fra https://www.stemfie.org/parts/28-3d-printing/60-samples/117-stemfie-quick-print-sample og konverterede filen i PrusaSlicer til en g-code fil. Hvis jeg havde downloadet i stl fil, ville jeg først skulle konvertere til en 3mf fil. Printet blev vellykket, og som vist på billedet. Tobias fortalte at skolen havde købt en ny cool printer, som ville blive leveret inden længe. Jeg kan ikke huske hvad den hed.


Figur 1: https://www.stemfie.org/parts/28-3d-printing/60-samples/117-stemfie-quick-print-sample
 
Figur 2: Billede af hvordan printet blev. Der mangler nogle dele. 
Min klassekammerat prøvede at ændre i infill, fra 20% til 50% hvilket resulterede i at der var én af skruerne der fik support (som hvis hun havde klikket ”ja” til support).
Jeg fortalte Tobias at jeg var i gang med en mockup til Abstracticas app, men Tobias mente ikke at der skulle laves en app til projektet. Derfor jeg stoppede processen for app-delen, og skulle drøfte dette med Kim senere til mødet. 
Samme dag, efter undervisning
Efter undervisning: jeg drøftede appdelen m. Kim, og kom frem til at der fokuseres på en mockup af Abstractica hjemmesiden. Denne mockup skal Tobias og Kim se, og hvis det bliver godkendt, skal jeg i gang med en prototype asap. Derudover vil jeg skifte mockup program, da Wondershare var dårligt at arbejde i. Jeg er siden da blevet anbefalet Figma.com, som jeg vil afprøve. Ny dag for møde: 10/5.


Torsdag d. 27. april
Figma er dårlig aswell! Jeg har fundet noget jeg synes der er godt: https://www.canva.com/ - der vil jeg arbejde med mine mockups.


Tirsdag d. 2. maj
Set den nye printer i aktion. Tobias skulle printe nogle beams, og jeg så hvordan andet lag gik lynhurtigt. Printeren hed P1P mener jeg. 
Logo blev færdig og uploadet til: https://docs.google.com/document/d/1XumUMbpcODDmR0A--phCoR7Ws4O4I53G455trvnNyzY/edit
Har taget sin tid i og med at det er lavet fra bunden af, og første gang jeg skulle bruge programmet. 
 
Tirsdag d. 9. maj
Arbejdet med mockup til at præsentere til Kim. 
 
 
Onsdag d. 10. maj 
Møde med Kim, som desværre blev aflyst. Nogle dage efter blev jeg syg, og så måtte vi rykke det til fredag d. 19. maj. 


Fredag d. 19. maj
Fremviste mockup til Kim, og han kom med konstruktiv feedback. Sagde blandt andet, at når brugeren loggede ind kunne det være en fordel at have ’mindre støj’, og gøre brugersiden mere målrettet på hvad brugeren synes var spændende og hvem brugeren følger’s opslag. 
 
 
Refleksion af valgfaget: 
Helt overordnet har jeg lært, at Tobias har opbygget et kodesystem med implementering af factory pattern. Han bruger et CSG-bibliotek til at fremskabe 3D-modeller i STL-format. Jeg kunne også forstå problematikken i, at når man kørte 3d-koden i Java, var det træls at openSCAD ikke åbnede STL filen automatisk. Nu når jeg sidder og tænker over det, bliver jeg i tvivl om problematikken måske var at STL-filen, ikke bliver en 3MF fil med det samme? Men at man skal over i OpenSCAD og konvertere? Så lige nu er det STL  3MF  G-code. 
Mht. 3D printeren lærte jeg at før printprocessen overhovedet kan gå i gang, skal 3D-modellen slices ligesom en lagkage, ved hjælp af PrusaSlicer. Det er simpelthen for at printeren får instrukser om hvordan den skal skabe 3D-modellen lag for lag. Printeren skal forberedes før den kan printes, og det vil sige man tjekker om den er ren på pladen, om filamentet er indlæst og sat korrekt, tjekke temperaturen og hastigheden. Herefter kan jeg så gå i gang med at overføre den g-code fil fra USB’en til printeren. Det er især i starten, at man skal holde øje med om printet går som forventet, da det typisk lægger ’vejen’ for resten af printet. 
Jeg har på nuværende tidspunkt ikke udviklet noget kode til hjemmesiden endnu, hvilket jeg virkelig gerne ville have nået. Men pga. hovedopgaven er jeg blevet alt for presset, og har derfor ikke kunne lave to systemer på én gang. Hvis jeg mod forventning skulle nå at udvikle noget, vil det blive uploadet i en separat mappe på https://github.com/swes42/Abstractica.
Mine tanker vedrørende selve strukturen på studiet, er at det har føltes en smule ustruktureret. Jeg tror at jeg/vi har været vant til at de andre lærere har været meget klar i reglerne om gruppedannelsen, og selve dét at afholde gruppemøder. Det blev meget overladt til os selv, og jeg blevet ”tabt” mellem grupperne, da jeg skulle spørge om jeg måtte være med. Så jeg kan selvfølgelig ikke tale på gruppernes vegne, om hvorvidt det har været  disciplinerede nok til at afholde kontinuerlige møder. Men personligt, kunne jeg virkelig godt have tænkt mig et lang bedre overblik på hvilke programmer vi ville komme igennem. Eventuelt en uge før valgfaget starter, kunne man få en besked med ”Der her skal du have downloaded, og hvorfor du skal have det downloaded”. Og så på første dagen, er der allerede kridtet grupper ud med hver deres ansvar og roller, og eventuelle opgaver. Og så kunne man måske indføre, at der ved hver gang afholdes sådan slags briefing mellem alle grupperne – netop fordi der arbejdes sammen om Abstractica. Ja, man kunne endda måske sige at man arbejder efter SCRUM. Det ville nok tilføre valgfaget en del mere struktur og opsamling på hvad der er opnået – hvilket kun ville gavne projektet, tænker jeg. 

