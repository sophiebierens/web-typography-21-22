# Web Typography, 2020/2021

Sophie Bierens VID1 - 2022


## De opdracht

De opdracht was om een website te coderen met HTML en CSS voor doven mensen. Op deze website wordt een korte video getoond uit de film Blade Runner 2049. Aan mij de taak om deze video te ondertitelen en grafisch vorm  te geven. Dit moest op zo'n manier gebeuren dat de dove persoon die de video zou zien, een zelfde soort beleving zou ervaren als iemand die niet doof is.  


## Week 1

### Onderzoek
Ik ben begonnen met onderzoek doen naar de film. De film was voor mijn nog één groot vraagteken en daarom ben ik een stuk van de film gaan kijken. Daarnaast heb ik ook een samenvatting gelezen van de film. Ik heb dit beide gedaan om een zo'n duidelijk mogelijk beeld van de film te krijgen. 

### Stappenplan
Na het onderzoeken wat de film inhield ben ik gaan nadenken over een stappenplan wat ik wilde aanpakken en hoe. Ik heb hiervoor eerst het fragment meerdere keren heel goed beluisterd en nagedacht over welke geluiden ik wil gaan vormgeven en hoe. Ik vond het in het begin nog erg lastig om inspiratie op te doen hiervoor. Wat veel in mijn hoofd omging was; wat zijn de mogelijkheden en hoe pak ik dit aan? Ik heb pas sinds twee weken CSS en HTML onder de knie, dus dit was voor mij wel weer even nadenken wat er allemaal kan en of ik het kan. Toch wilde ik mezelf niet teveel beperken hierin, omdat ik van de vorige keer coderen weet dat ik meer kan dan ik misschien soms in eerste instantie denk. 

Ik ben gestart met de lettertypes aanpassen. Hiervoor moest ik eerst kijken wie wat zegt. Hierna heb ik gekeken wat voor lettertype bij welke stem/personage paste. Ik merkte dat stem 1 een erg robot achtige stem had, maar stem 2 weer echt een mannelijke normale stem. Ook komt er een moment waarin er geschreeuwt wordt. Hier wilde ik ook een ander soort lettertype of vormgeving voor gebruiken. 

### Codes
Ik ben begonnen met eigenlijk van alles te proberen in de code te schrijven. Hierdoor kon ik kijken hoe alles uitpakte en wat er leuk uitzag, of wat juist niet. 

Ik heb 

## Week 2

Je *moet* een van deze twee opties kiezen, en je keuze moet je onderbouwen. In je readme staat een uitleg over je overwegingen om de ene of de andere restrictie te kiezen.

### Optie 1: Systeemfont

De eerste optie is dat je gebruik maakt van het zogenaamde *systeemfont* van degene die naar jouw werk kijkt. Dit font verschilt per operating system, en het verschilt soms zelfs per versie van het operating system. Het is ook aan te passen door de gebruiker zelf. 

Je hebt dus geen controle over welk lettertype er precies gebruikt wordt. Het levert dus een onzeker, en beperkt typografisch palet op. Je hebt geen *light* versies, of *extrabold*. En ook geen serif en sans-serif versie van dezelfde familie. In dit geval heb je alleen de beschikking over normal, **bold** en _italic_. Dit heeft natuurlijk ook zijn voordelen!

### Optie 2: Brenner

Je kan er ook voor kiezen om gebruik te maken van de complete Brenner familie. Dit is een zeer uitgebreid en uiterst flexibel font. [Hier kan je je verdiepen in dit font](https://www.typotheque.com/blog/brenner_an_unusual_typeface_family_with_distinct_voices). Als je kiest voor dit font dan heb je de beschikking over een *sans serif*, een *condensed*, een *serif*, een *monotype*, een *slab*, een *display* en een *script* versie. En veel van deze versies hebben varianten van *light* tot *bold*, en allemaal zowel *bold* als *italic*.

Met Brenner zijn er natuurlijk veel en veel meer mogelijkheden dan met systeemfonts. Dat kan zowel een voordeel als een nadeel zijn. 

Voor een overzicht, zie [de brenner.pdf](brenner.pdf).

## Ontwerpkeuzes

### Typografie
Om erachter te komen welk font het beste paste bij mijn video, heb ik onderzoek gedaan naar het font ''Brenner'' via de website [Typotheque](https://www.typotheque.com/blog/brenner_an_unusual_typeface_family_with_distinct_voices). Hier was te lezen dat dit font geen beperkingen heeft op het gebied van contrast. Dit in tegenstelling tot de systeemfonts. In de video wordt onder anderen geschreeuwd en is er gebruik gemaakt van een krachtige robotachtige stem. Voor deze stemmen vond ik dat er ook een krachtig en duidelijk lettertype bij hoorde. Ik heb daarom voor het font ''Brenner'' gekozen omdat je er heel veel kanten mee op kan. Zo past het font ''Brenner Mono'' heel goed bij de robot/computer stem door het typemachine effect. In de film zie je verschillende high tech schermen. Dit deed mij denken aan een soort sci fi game elementen. Ik heb dit op Pinterest opgezocht om zo te kijken hoe ik dit zou kunnen namaken. Ik heb daarom voor deze stem ook nog een border gemaakt die het futoristische effect moet accentureren. Voor de hoofdrolspeler in de film heb ik een neutraler font gekozen. Hij is vrij kalm, volgt de orders die hij krijgt en zegt niet heel veel, ondanks dat het wel een sterke man is. Daarom heb ik voor hem het font ''Brenner Sans'' gekozen. 

### De captions

De captions staan in de html, in het bestand index.html. Je kan aan elke paragraaf eventueel een of meer classes toevoegen. Bijvoorbeeld `voice1` of `voice2 soft`. Classes voeg je handmatig toe in de html.

Met JavaScript worden er een paar dingen extra gedaan: 

- er wordt aan elke paragraaf een unieke class toegevoegd (`p0`, `p1`, etc)
- Elk woord wordt in een aparte `span` gezet. Hierdoor kan je elk woord apart stylen, en eventueel ook [na elkaar laten verschijnen](https://github.com/cmda-minor-vid/web-typography-18-19/blob/master/closed-captions/css.css#L41).

### Tijdens het afspelen

Tijdens het afspeelen wordt er een class `on` op de caption gezet als hij moet verschijnen, en een class `off` als hij klaar is. *Zowel class `on` als class `off` blijft op de caption staan!*

De timimg van de captions kan je aanpassen in [closed-captions/captions.js](closed-captions/captions.js).

Er verschijnen ook classes op de body op momenten dat er geluiden worden afgespeeld, zoals `sound1` en `sound2`. Je kan geluiden toevoegen in [closed-captions/sounds.js](closed-captions/sounds.js).

*let op,* de geluiden zijn niet compleet, dit zal je zelf moeten aanvullen.

## Een eigen fragment (afgeraden, uitgebreide onderbouwing is nodig)

Je kan er ook voor kiezen om een eigen, *beter* fragment te gebruiken. Dit wordt afgeraden. De tijd die je besteedt aan het zoeken naar dat fragment kan je beter besteden aan het werken aan de opdracht. Bovendien blijkt dat er vaak fragmenten worden gekozen die niet goed voldoen aan de opdracht. Als je een ander fragment kiest dan *moet* je dit goed onderbouwd voorleggen aan je docent. De deadline hiervoor is vrijdagochtend in de eerste week.

### Waar moet je op letten bij het kiezen van een eigen fragment.
Lees de opdracht nog eens goed door. Waar gaat het ook al weer precies om? 

Voor een goede onderbouwing van je keuze voor een ander fragment moet je deze vragen in elk geval beantwoorden:

- Welke informatie zit er in de audio die echt niet zichtbaar is?
- Welke rol speelt de audio in het fragment?
- Werkt de scene nog zonder geluid?
- Waarom is dit fragment beter dan het aangeboden fragment?

Je kan dan de nodige HTML en JavaScript genereren door gebruik te maken van [caption generator](https://cmda-minor-vid.github.io/web-typography-18-19/generator/) (in Google Chrome). 

Als je de closed captions wil bewerken dan kan je een tool zoals [Amber Script](https://www.amberscript.com/en) gebruiken. Daar kan je exporteren als `.srt`, en die kan je weer door de generator halen.
