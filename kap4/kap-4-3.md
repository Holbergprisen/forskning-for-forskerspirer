# Kvantitative analyseteknikker

Statistikk kan være forførende, men også fremmedgjørende. Statistikk i seg selv gjør ikke noe mer eller mindre vitenskapelig, det avhenger av hvordan den brukes. Det å lage statistikk fra sitt eget datamateriale er veldig morsomt og utrolig spennende. Spesielt fordi det kan dukke opp ting som man ikke forventet på forhånd. Vi bruker ofte statistikk for å få et konkret og umiddelbart overblikk som vi ikke klarer ved å se «med det blotte øye». Tenk om dere måtte telle gjennom alle spørreskjemaene for hver gang dere lurte på hvor mange som hadde svart seg enig på et av spørsmålene?

<div class="boks">Statistikk brukes vanligvis på to måter. Den vanligste formen for statistikk er beskrivende, den andre måten vi som man gjøre statistikk på er testende. </div>

##Beskrivende statistikk

Beskrivende statistikk er når man gir en tallmessig beskrivelse av datamaterialet, for eksempel kjønnsfordelingen, hvor mange som oppgav et gitt svar på ett spørsmål eller hva gjennomsnittsscoren er på en holdningsskala. Beskrivende statistikk rapporteres stort sett som enkle tall i teksten, i tabeller eller i forskjellige typer grafer og visualiseringer. Det som er viktig i beskrivende statistikk er å balansere mellom å gi en nøytral fremstilling av tallene og markere det som er viktig å legge merke til. Beskrivende statistikk må også tolkes. Noen ganger finner man tydelige tendenser og forskjeller i datamaterialet, og noen ganger det mer subtilt.

Akkurat som med sitater, bør ikke grafer og tabeller stå ukommentert i rapporten. Dere er nødt til å beskrive hva de forteller oss, og hvilken betydning de har for forskningsspørsmålet.

<div>
    <a href="https://plot.ly/~kmelve/59/" target="_blank" title="Personer 16 år og over, etter år, kjønn og utdanningsnivå (ssb.no)" style="display: block; text-align: center;"><img src="https://plot.ly/~kmelve/59.png" alt="Personer 16 år og over, etter år, kjønn og utdanningsnivå (ssb.no)" style="max-width: 100%;width: 1309px;"  width="1309" onerror="this.onerror=null;this.src='https://plot.ly/404.png';" /></a>
    <script data-plotly="kmelve:59" src="https://plot.ly/embed.js" async></script>
</div>

Dere kan lage grafer og tabeller i [Excel][0978-0001], [Numbers][0978-0002] og [Google Docs][0978-0003]. Nettsiden [plot.ly](http://plot.ly) (som jeg har brukt over) kan også være morsom å bruke. Der finner dere også mange eksempler på beskrivende statistikk og spennende måter og visualisere data på. I eksempelet over er et søylediagram over utdannelsesnivå i 2013 for menn og kvinner. Tallene har jeg hentet fra en tabell hos [ssb.no](http://www.ssb.no/utdanning/statistikker/utniv/aar/2014-06-19?fane=tabell&sort=nummer&tabell=181262), som jeg lastet opp på plot.ly. Legg merke til søylene for Universitets- og høgskole, hva ser vi der?

Beskrivende statistikk gir et bilde av datamaterialet hvor dere kan sammenligne proposjoner, antall, se om det er lite eller mye av noe. Det er lett å henge seg opp i noe det er mye av, men det om det kun er en av, kan være vel så interessant. Grafer og tabeller snakker sjelden for seg selv. Selv om dere gjør en kvantitativ analyse, er dere fremdeles nødt til å finne ut hva statistikken *forteller* oss om forskningspørsmålet. Bekrefter, nyanserer eller avkrefter det hypotesene og delspørsmålene? Beskrivende statistikk gir også grobunn for nye spørsmål dere kanskje er nødt til å følge opp.

Når dere jobber med statistikk er det viktig å skille mellom de tabellene og grafene dere jobber med i analyseprosessen, og de dere velger å legge inn i forskningsrapporten. Tabeller og grafer i analysen vil gjerne være mer omfattende, rotete og komplekse enn de dere legger inn i rapporten. I analysen skal dere komme frem til de tallene som beskriver og underbygger det dere har kommet frem til. Dere kan lese mer om hva dere bør tenke på i kapittelet som handler om ferdigstillingen av forskningsrapporten.

##Statistisk testing
Statistisk testing er når vi bruker matematiske modeller på datamaterialet for å si noe om sannsynlighet, sammenhenger og variasjon. Det er i denne grenen det mulig å bruke et kvantitativt datamateriale om et utvalg for å si noe om en populasjon, og samtidig vite noe om sannsynligheten rundt denne generaliseringen. Det er dette de fleste meningsmålinger og spørreundersøkelser bygger på. Om man stiller samme sett med spørsmål til mellom 1 000 og 1 500 *tilfeldig* utvalgte personer kan man si noe om hva «alle» i Norge mener.

På en enkel måte kan vi si at statistisk testing gir oss muligheten til å tallfeste hvor usikre vi er på noe. For å gjøre det er vi nødt til å forsikre oss om at innsamlingen, datamaterialet og analysemetodene oppfyller visse forventninger om sannsynlighet og tilfeldigheter. Om man for eksempel begynner å lese seg opp på utvalgsmetoder (eller *sampling* som det heter på engelsk), finner man fort ut hvor komplisert det kan bli. Mye av grunnen til at det kan bli komplisert, er at i hvert ledd av prosessen, finnes det mange måter å kontrollere og sjekke datamaterialet på.

Det er også mange, og ganske ofte forskere, som glemmer at statistikk også er en egen fagdisiplin med faglige uenigheter, men hvor det også skjer utviklinger. Ofte presenteres statistiske metoder som faste oppskrifter på hvordan man analysere noe. Selv om slike oppskrifter som dere finner i bøker for kvantitative metode som oftest er korrekte, så diskuterer de sjelden bakgrunnen og tolkningsmulighetene innenfor metodene. Et ganske godt eksempel på det er *p-verdien*. Dersom dere noen gang har kommet over en tabell i en forskningsrapport og sett bruk av en eller to stjerner (\*) bak ett tall, så er det meget sannsynlig at forskerne her har oppgitt p-verdien for den statistiske analysen. Under tabellen finner man gjerne `* > 0,05`, som betyr at «p-verdien er under 0,05». Da kan forskningsjournalisten skrive at «funnene var statistisk signifikante». Med andre ord: Sammenhengen eller forskjellen mellom de to variablene er så stor at det ikke bare er tilfeldigheter.

Statistiske tester som ender opp i et resultat med en p-verdi, er kanskje noe av det mest vanlige innenfor kvantitativ forskning. Da er det interessant å vite at det hersker mange misforståelser rundt hva en p-verdi *egentlig er*. Dersom dere dedikerer en og en halv time av livet til å høre på [denne episoden av Udannet](http://u-dan.net/udannet/2014/5/18/p-verdien-gjest-ystein-haaland), vil dere antagelivis vite mer enn de fleste om p-verdien, men også oppdage at statistikk faktisk er ganske interessant.

<div class="boks">
Dersom dere har lyst til å sammenligne gjennomsnitt i to grupper, er dere nødt til å se nærmere på statistisk testing.
</div>

<div class="caption right small">
	<img src="../images/gosset.jpeg" alt="Bilde av William Gosset" />
	<div class="caption-text">William S. Gosset (1876–1937). Ølbrygger og statistikk-hipster
	</div>
</div>

Dere trenger egentlig ikke å kunne så mye matematikk for å gjøre statistisk testing. I dag bruker de fleste programvare som tar seg av alle de matematiske kalkulasjonene. I statistikken er det imidlertidig lett å trå feil, og det er en fordel å kjenne til hvilke antagelser man tar om datamaterialet når man tester det statistisk. Viktige tema her er *representativitet*, *normalfordeling* og *hypotesetesting*.  Den vanligste statistiske testen er å sammenligne gjennomsnitt i to utvalg. Denne går under navnet *Student’s t-test*, eller bare *t-test*, og ble utviklet for rundt 100 år siden av William Sealy Gosset som jobbet i Guiness’ øl-bryggerier. I t-tester sjekker vi om forskjellene i gjennomsnittene hos to utvalg er store nok til at det ikke kan være tilfeldig.

Her er et tenkt eksempel som illustrerer hvorfor dere ikke bare kan sammenligne gjennomsnitt i to grupper uten videre. Dersom dere finner ut at gjennomsnittskarakteren for jentene og guttene i én klasse er omtrent 4, kan dere ikke uten videre anta at det *ikke* er noen forskjeller mellom disse:.

		Guttene: (2 + 3 + 2 + 3 + 6 + 5 + 6 + 5) / 8 = 4
		Jentene: (4 + 5 + 3 + 5 + 3 + 5 + 4 + 5 + 4) / 9 ≈ 4.2

Gjennomsnittene for jentene og guttene er nesten det samme, så ser vi at hos guttene er det én gruppe med dårlige og veldig gode karakterer, og hos jentene er det mer jevnt. Med andre ord, selv om gjennomsnittet for gruppene er like, så er ikke nødvendigvis gruppene like når det kommer til karakterer. Prinsipper om gjennomsnitt, variasjon og spredning er grunnleggende for statistisk testing.

[0978-0001]: http://products.office.com/en-us/excel
[0978-0002]: https://www.apple.com/mac/numbers/
[0978-0003]: https://itunes.apple.com/us/app/google-sheets/id842849113?mt=8

