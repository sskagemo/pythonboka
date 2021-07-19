En bok om Python -- hvorfor det?
================================

Python er et av verdens mest populære programmeringsspråk, og det er mange grunner til det. Og det er også mange grunner til at det er lurt å lære å programmere. Så den korte oppsummeringen er at en bok, på norsk, om Python, skal gjøre det enklere for flere å lære programmering. 

Nedenfor er mer om de forskjellige grunnene.

Grunner til å lære programmering
--------------------------------

Mange har allerede tatt til orde for at "alle" bør lære å programmere, og at programmering er en kunnskap som bør sidestilles med å kunne lese, skrive og regne. Noen omtaler programmering som en "superpower". En ting er at vi idag omgir oss med digitale hjelpemidler som kan løse mange oppgaver for oss, for eksempel tekstbehandling og regneark. Men det er et stort sprang fra å være prisgitt de verktøyene andre har laget, til å selv kunne lage hjelpemidlene som passer nøyaktig til de oppgavene _du_ trenger å løse.

En av mine favorittbøker for å lære Python tar utgangspunkt i nettopp det siste, at det ikke finnes ferdige verktøy for akkurat de oppgavene _du_ skal løse, og som er laget for å håndtere akkurat den kombinasjonen av datakilder og verktøy og tjenester: "Automate the Boring Stuff with Python" av Al Sweigart. Den er [gratis tilgjengelig som nettsider](https://automatetheboringstuff.com/2e/) og finnes også som fysisk bok.

Et eksempel jeg selv har erfaring med er å forsøke å orientere meg i båtmarkedet på Finn.no. Finn.no tilbyr mulighet til å lagre annonser som favoritter, og du kan velge mellom å vise et utvalg av opplysninger i en listevisning, eller se på detaljene. Men jeg fikk ikke nok detaljer i listevisningen, og mistet samtidig oversikten i detaljvisningen, så jeg laget en løsning som plukket ut den informasjonen jeg ville ha for de annonsene jeg valgte, og fikk et regneark som passet bedre for meg. Det kunne jeg også dele med han jeg skulle kjøpe båt sammen med, i motsetning til om jeg lagret favoritter og tok notater i Finn. Hadde jeg holdt på lenger kunne jeg antagelig også begynt å rangere annonser etter om prisen var uvanlig lav eller høy.

En som har tatt dette et steg lenger, er investeringsdirektør i Nordea Markets, Robert Næss. I et intervju i Dagens Næringsliv 2. januar 2021 står det følgende: "Hva gjør forvalter og Nordea-topp Robert Næss når han skal planlegge fremtidige investeringer? Han sjekker Finn.no.". Og han sjekker ikke Finn.no manuelt, men har automatisert prosessene:

"- Hver dag laster jeg ned alle boligannonsene på finn, sjekker prisutviklingen. For hele landet. Har laget en for Danmark også. Og en for fritidseiendommer, biler og båter. Og stillinger."

Det fremgår ikke fra intervjuet, men i en annen podcast ... )

For læring og forståelse:

"- Jeg har jobbet mye med det og programmert min egen prototype på en kryptovaluta. Under det arbeidet har jeg funnet ut at Bitcoin faktisk fungerer dårlig teknisk."
Fra intervju i [Nettavisen](https://www.nettavisen.no/okonomi/investeringsdirektor-advarer-bitcoin-er-for-tomsinger/s/12-95-3424126959)


Jeg er (ikke overraskende) en tilhenger av at programmering blir et fag i skolen, og programmering er nå en del av de nye læreplanene for grunnskolen. 


Grunner til å velge Python som første programmeringsspråk
---------------------------------------------------------

Det finnes selvsagt andre programmeringsspråk som er gode kandidater hvis du lurer på hvilket du skal velge, og jeg skal ikke påstå at Python er det desidert beste valget. Men ved valg av språk kan det være ulike hensyn å vurdere: Det bør være lett å komme igang og lett å forstå språket. Samtidig bør det også ganske raskt være mulig å gjøre noe med språket som er nyttig. Og helst bør språket "vokse", sånn at du etterhvert kan løse også avanserte oppgaver. Hvor mye et språk kan brukes til henger også sammen med hvor populært det er. Jo flere som bruker det, jo større er sannsynligheten for at det allerede er noen som har brukt det til lignende oppgaver, og at det finnes moduler og verktøy som 

Et siste poeng er eierskapet til språket. Noen språk eies og forvaltes av kommersielle selskap, mens andre, som Python, er åpen kildekode og forvaltes av en uavhengig organisasjon, Python Software Foundation.



Som du sikkert har gjettet mener jeg Python er et programmeringsspråk som har de egenskapene jeg har nevnt her.

Lett å bruke
____________

interaktiv
ikke kompilering


Lett å forstå
_____________

Python er laget for å være lett å lese (fordi kode skrives en gang men leses mange ganger) og derfor kan det nesten leses som engelsk. Nedenfor er noen eksempler på kode (det som kommer etter >>> og ... er kode som er skrevet inn, og det som står uten tegn foran er "svaret" når koden kjøres)

```python
>>> 3 + 3 # dette taster vi inn, og når vi trykker enter kommer resultatet på neste linje
6

>>> if 3 + 3 == 6:
...     print('Python regner riktig!')
Python regner riktig!
>>>
```

Gjøre avanserte ting
____________________

Riktignok er det sånn at når du kan så mye programmering at du skal gjøre avanserte ting, vil du sannsynligvis også raskt kunne lære nye språk. Det er egentlig alene en grunn til å starte å lære programmering, for så fort du har lært et programmeringsspråk blir det mye enklere å lære det neste. Men selv om det blir relativt enkelt å lære seg nye språk når du først har lært et, er det selvsagt ikke noen ulempe om det du språket du allerede har brukt tid på å lære, også er fleksibelt og avansert nok til kunne brukes til det meste.

Men Python har også noen svakheter ...
______________________________________

Python er ikke et perfekt språk, så det er verdt å nevne noen av svakhetene også. Det handler også ofte om valg og balansering av hensyn, for å få mer av noe må man gi opp noe annet. 

* Hastighet: Python er regnet som et tregt språk; når Python-kode kjøres brukes det relativt mye minne og det går relativt tregt sammenlignet med en del andre språk. Men som nevnt er denne svakheten ikke til hinder for at Python brukes i driftskritiske systemer, og i stor skala. Når det er enkelt å utvikle ny funksjonalitet, er det også enklere å forbedre systemer for å komme rundt flaskehalser. Ofte er det andre ting enn selve kjøringen av koden som er kritisk for om et system er tregt eller ikke.

* Interaktivitet i nettlesere: Python er mye brukt for å lage nettsider, mer presist for å styre det som skjer på serverne som leverer nettsidene til nettleseren. Men på et område, interaktivitet i nettleseren, er det et annet språk som dominerer totalt, nemlig JavaScript. JavaScript er et språk som det er innebygget støtte for i alle nettleserne. Med utviklingen av nettleserteknologi, er det ikke usannsynlig at Python også blir et alternativ til JavaScript for å styre nettlesere i fremtiden.

* Mobil: Python er foreløpig ikke et av de foretrukne språkene for å lage app-er på de ulike mobil-plattformene, Android og Apple iOS.

* 


Grunner til å skrive en bok om programmering på norsk 
-----------------------------------------------------

Vel, jeg må innrømme at den aller viktigste grunnen til at jeg har begynt å skrive denne boken, er at jeg har lyst til å gjøre det. Så jeg skal kanskje ikke påstå at det finnes noen objektive grunner til at denne boken bare _må_ skrives. 