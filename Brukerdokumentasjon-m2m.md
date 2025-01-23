
# <a name='Brukerveiledning - M2M-klienter'></a>Brukerveiledning - M2M-klienter


INNHOLDSLISTE
<!-- vscode-markdown-toc -->
* [M2M-klienter](#M2M-klienter)
* [API-ressurser](#API-ressurser)
	* [Legg til ny API-ressurs](#LeggtilnyAPI-ressurs)
* [Tilgang](#Tilgang)

<!-- vscode-markdown-toc-config
	numbering=false
	autoSave=true
	/vscode-markdown-toc-config -->
<!-- /vscode-markdown-toc -->

---

## Innlogging
[Klikk her for veiledning for innlogging.](LoggInn.md)

Det er bare Falk Administrator som kan sette opp og aktivere Maskin til Maskin-klienter.

## <a name='M2M-klienter'></a>M2M-klienter
Falk Admininistrator har et menyvalg i fanen Administrere for å se og administrere maskin til maskin-klienter: M2M-klienter. 

Når du velger M2M-klienter vil du få en oversikt som viser M2M-klientene i Falk. 
Hver M2M-klient blir vist som en rad i oversikten, sammen med antallet API-scope og hvor mange rettigheter M2M-klienten har. I tillegg kan du se om en M2M-klient er aktiv.

![Oversikten M2M-klienter i Falk.](img\Falk2.5\m2m-klienter.png)

Ved å velge en M2M-klient i oversikten åpner du den og får opp mer informasjon om får tilgang til å endre på den. Fanen Konfigurasjon er i fokus når du åpner klienten og viser 
- navnet til klienten og identifikatoren sammen med en avkryssingsboks som viser om M2M-klienten er aktiv eller inaktiv, 
- listen API-ressurser som viser de API-ressursene som finnes og hvilke scopes som er satt opp og aktive eller inaktive for hver API-ressurs, 
- liste med navet til de applikasjonene som er satt opp med denne klienten. Du har mulighet til å klikke på et navn for å navigere til den applikasjonen herfra.  

![Fanen Konfigurasjon som viser API-ressursene i en liste og knappen for å endre.](img\Falk2.5\m2m-klient-Konfigurasjon.png)
 
I fanen Konfigurasjon for M2M-klienten har du også knappen for å endre og oppdatere M2M-klienten. Velg knappen Endre for å åpne M2M-klienten og gjøre endringer. 

![M2M-klient i redigeringsmodus.](img\Falk2.5\m2mklient-KonfigurasjonEndre.png)

Når du velger å endre på en M2M-klient har du tilgang til å bestemme scopes som skal brukes for hver API-ressurs: Huk av avkryssingsboksen for det eller de scopes som skal være tilgjengelige og aktive, og fjern avkryssingen i avkryssingsboksen for å gjøre det utilgjengelig. 

Når du er ferdig med å endre og har bestemt scopes for hver API-ressurs, klikk Lagre under listen. 

Endringer som er utført for M2M-klienten blir loggført i aktivitetsloggen. Du kan se disse å velge fanen Aktivitetslogg. 

![Aktivitetslogg for en M2M-klient.](img\Falk2.5\m2mklient-Aktivitetslogg.png)
Når du velger fanen Aktivitetslogg i M2M-klienten får du en oversikt over aktiviteter som er utført, ordnet etter dato. Oversikten har en nedtrekksmeny der du kan velge å se bestemte aktiviteter, for eksempel når klienten er endret på (Klient modifisert), rettigheter som har blitt slettet og opprettet ny klient. 

Du kan se mer informasjon om hvert innslag i Aktivitetslogg ved å klikke på det. 

![Aktivitetslogg for en M2M-klient som viser innslag .](img\Falk2.5\m2m-klient-AktivitetsloggKlientModifisert_Utvidet.png)


## <a name='API-ressurser'></a>API-ressurser
Falk Admininistrator har tilgang til et menyvalg i fanen Administrere som heter API-ressurser. Når du velger API-ressurser kommer du til en oversikt som viser de API-ressursene som finnes i Falk, sammen med funksjonen for å legge til en ny API-ressurs. 

Hver API-ressurs blir vist i en oversikt og er ordnet etter navnet på API-ressursen. Ett eller flere scopes som er registrert for API-ressursen blir vist, sammen med en knapp for å slette den. Hvis en API-ressurs har scopes som er inaktive, er dette vist i listen. 

![Oversikt som viser API-ressurser med aktive og inaktive scopes i Falk.](img\Falk2.5\m2m-API-ressurser.png)

### <a name='LeggtilnyAPI-ressurs'></a>Legg til ny API-ressurs
Som Falk Administrator kan du legge til ny API-ressurs ved å velge knappen Legg til ny API-ressurs og få opp et skjema for å opprette ny API-ressurs i Falk.

I skjemaet for å legge til ny API-ressurs kan du fylle ut navn, visningsnavn og bestemme om denne API-ressursen skal være aktiv. 

![Skjema for å legge til ny API-ressurs.](img\Falk2.5\m2m-API-ressursLeggTil.png)

For å legge til et scope for API-ressursen kan du klikke pluss-ikonet. Når du klikker på pluss-ikonet for Scopes blir flere felt tilgjengelige for å skrive inn navn og visningnavn for scopet og får å bestemme om scopet skal være aktivt. 

Du har mulighet til å registrere flere scopes med visningsnavn. Vil du ta bort et scope kan du klikke slette-ikonet på raden til scopet.

![Skjema for å legge til ny API-ressurs med scopes.](img\Falk2.5\m2m-API-ressursLeggTilScopes.png)

For å få korrekte scopes, ta kontakt med Hemit systemutvikling: [systemutvikling@hemit.no](mailto:systemutvikling@hemit.no).

Når du har lagt til API-ressursen og registrert scopes for den, lagrer du ved å klikke Lagre. API-ressursen du har lagt til blir vist i oversikten API-ressurser.

## <a name='Tilgang'></a>Tilgang
Falk Administrator har tilgang å administrere M2M-klienter for hver applikasjon. Dette gjøres via fanen Tilgang i applikasjonen. 

I applikasjonen du vil administrere, velg fanen Tilgang. Når fanen Tilgang blir åpnet og viser fanen Brukere i fokus, velger du fanen M2M-klienter som ligger i bakgrunnen. 


![Oversikten som viser en M2M-klient som har tilgang til applikasjonen.](img\Falk2.5\m2m-TilgangAdministrer.png)

Fanen M2M-klienter viser de M2M-klientene som har en eller flere tilganger til applikasjonen sammen med en knapp for å gi M2M-klienter tilgang. 
Dersom det ikke er gitt noen M2M-klienter tilgang til applikasjonen viser fanen informasjon om dette. 

![Tilgang](img\Falk2.5\m2m-tilgang.png)

For å gi en M2M-klient tilgang til applikasjonen, velg knappen Gi ny tilgang i fanen M2M-klienter. Vær oppmerksom på at dette krever at det eksisterer M2M-klienter som ikke har tilgang til applikasjonen fra før.

![Skjema for å velge M2M-klient og gi den tilgang til rolle og avdeling.](img\Falk2.5\m2m-Tilgang-GiNy.png)

![Skjema som viser en valgt M2M-klient med en rolle- og avdelingskombinasjon og felt for å legge til flere kombinasjoner.](img\Falk2.5\m2m-TilgangGiNy2.png)

Når det finnes M2M-klienter som har tilgang til applikasjonen, kan du klikke på denne M2M-klienten i oversikten. Mer informasjon om M2M-klienten blir vist sammen med en knapp for å administrere tilganger som denne M2M-klienten har. 

![Oversikten som viser en valgt M2M-klient og knappen Administrere Tilganger.](img\Falk2.5\m2m-TilgangAdministrer2.png)

Velg knappen Administrere tilganger for M2M-klienten for å komme til skjemaet for å se og endre hvilke tilganger den har. Når du har valgt knappen Administrer tilganger for en M2M-klient, kommer du til skjemaet der du ser navnet til M2M-klienten og informasjon om den. I skjemaet kan du tildele flere tilganger og fjerne tilganger M2M-klienten har til applikasjonen.

![Skjema for å administrere tilgang for M2M-klienten med felt for å legge til rolle- og avdelingskombinasjoner og for å fjerne eksisterende tilgang.](img\Falk2.5\m2m-TilgangAdministrer3.png)

---

Mer informasjon og veiledninger:

>[ Til forsiden i Falk brukerveiledning](README.md)

>[ Veiledning for innlogging](LoggInn.md)

>[ Brukerveledning for App Admin](Brukerdokumentasjon-applikasjonsadmin.md)

>[ Brukerveledning for Bruker](Brukerdokumentasjon-bruker.md)

>[ Brukerveledning for Falk Administrator](Brukerdokumentasjon-falkadmin.md)

>[ Brukerveledning for Tilgangstildeler](Brukerdokumentasjon-tilgangstildeler.md)

>[ Til toppen av denne siden](#brukerveiledning---m2m-klienter)