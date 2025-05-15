
# FALK Brukerdokumentasjon

# <a name= 'Brukerveiledning-for-tilgangstildeler'></a>Brukerveiledning for tilgangstildeler


INNHOLDSLISTE
<!-- vscode-markdown-toc -->
* [Innlogging](#Innlogging)
* [Tilgangstildeler](#Tilgangstildeler)
* [Søknader](#Søknader)
* [Tilgang](#Tilgang)
	* [Utsett automatisk deaktivering](#Utsettautomatiskdeaktivering)
	* [Reaktiver deaktivert tilgang](#Reaktiverdeaktiverttilgang)
* [Aktivitetslogg](#Aktivitetslogg)

<!-- vscode-markdown-toc-config
	numbering=false
	autoSave=true
	/vscode-markdown-toc-config -->
<!-- /vscode-markdown-toc -->

---


SØK PÅ DENNE SIDEN

Du kan søke etter informasjon på denne siden med Ctrl+ F: 
- Trykk Ctrl+F for å få opp søkefeltet.
- I søkefeltet skriver du det vil søke etter.
- Søketreff blir uthevet med en annen bagrunnsfarge.  


---

## <a name='Innlogging'></a>Innlogging
[Klikk her for veiledning for innlogging.](LoggInn.md)

## <a name='Tilgangstildeler'></a>Tilgangstildeler

Som Tilgangstildeler som har logget inn i Falk, har du tilgang til en fane som heter Applikasjoner.  
Når du velger fanen Applikasjoner finner du en liste som viser alle applikasjonene du har rollen Tilgangstildeler for. Hver applikasjon blir vist som en rad i oversikten, med kolonner som viser hver applikasjon sitt applikasjonsnavn, scopenavn og en kolonne som viser en hake hvis applikasjonen krever autorisasjon. 

![Tilgangstildeler Applikasjoner-oversikt.](img\Falk2.5\Tilgangstildeler-ApplikasjonerOversikt.png)

## <a name='Sknader'></a>Søknader
Når du velger å åpne en applikasjon, har du tilgang til fanen som heter Søknader. Tallet ved siden av navnet på fanen viser det antallet søknader som venter på å bli behandlet. 

Velger du fanen Søknader kommer du til en liste som  viser søknader om tilgang som til applikasjonen. Dette er søknader som er sendt inn av personer som ber om å få tilgang til applikasjonen med en rolle ved en avdeling eller enhet. 
Listen med søknader inneholder navnet til personen som har søkt om tilgang, hvilken avdeling personen har søkt om tilgang til, og datoen søknaden ble sendt inn, sammen med knapper for å åpne søknaden og for å slette søknaden. 

![Liste med søknader om tilgang til en applikasjon.](img\Falk2.5\Tilgangstildeler-ApplikasjonSøknaderListe.png)

Når du åpner en søknad med å klikke knappen Åpne søknad, får du opp selve søknaden. Øverst i søknaden er navnet til applikasjonen det er søkt om tilgang til. Nederst i søknaden er det knapper for å behandle denne, det vil si knapper for å avbryte, for å avvise søknaden, slette søknaden og for å godkjenne søknaden.  

Søknaden viser all informasjonen som ble lagt i den, både informasjon om søker og om når søknaden ble sendt inn og hvilken enhet eller avdeling det er søkt om tilgang til.

![Søknad om tilgang som er åpnet.](img\Falk2.5\Tilgangstildeler-SøknadUbehandlet.png)

Ut ifra informasjonen du ser i søknaden kan du gi en eller flere tilganger til roller og avdelinger som personen trenger: 
- Velg en rolle fra nedtrekklisten og skriv inn tall eller tegn for å finne riktig avdeling som du vil gi personen tilgang til. 
- Når du har valgt både en rolle og søkt opp rette avdelingen, kan du velge knappen Legg til. 
- Når du velger knappen Legg til blir den rollen og avdelingen lagt til i listen i søknaden, sammen med knapp for å fjerne tilgangen. 
- Når en rolle- og avdelingskombinasjon er lagt til kan du godkjenne søknaden. 

Etter at du har lagt til en rolle med avdeling, har mulighet til å legge til flere rolle- og avdeling-kombinasjoner, før du godkjenner søknaden.
Du må legge til minst en rolle på en avdeling før du kan godkjenne søknaden. 

![Søknad som viser en kombinasjon av rolle og avdeling som er lagt til, med knapp for å fjerne tilgangen.](img\Falk2.5\Tilgangstildeler-SøknadBehandlingFjernTilgang.png)

Knappene for å behandle søknaden er:
- Avbryt: Gir deg mulighet til å gå ut av søknaden uten å gjøre noe med den eller avbryte uten å lagre det du har lagt inn hittil. 
- Avvis søknad: Denne knappen kan du bruke for å melde fra at søknaden om tilgang ikke er godkjent. Når du velger knappen Avvis søknad får du opp et kommentarfelt som gir deg mulighet til å skrive inn en kommentar på hvorfor søknaden blir avvist. 
- Slett søknad vil slette søknaden når du velger denne knappen. Denne funksjonen er brukt for å fjerne duplikat-søknader uten å måtte avvise en slik søknad.
- Godkjenn søknad: Denne knappen blir aktiv når du har lagt til minst en kombinasjon av rolle og avdeling. Denne bruker du når du vil gi tilgangen og godkjenne søknaden. 

![Søknad som har blitt godkjent.](img\Falk2.5\Tilgangstildeler-SøknadGodkjent.png)

Når du har godkjent en søknad blir søknaden vist sammen med informasjon om at søknaden er godkjent. Hvis du åpner fanen som viser søknader igjen, vil du se at søknaden du nettopp har behandlet ikke lenger blir vist i listen. 


## <a name='Tilgang'></a>Tilgang
Når du velger fanen som heter Tilgang får du en oversikt som viser alle brukere som har tilgang til applikasjonen. Hver bruker vises som en rad i oversikten sammen med kontaktinformasjon, hvilken avdeling og rolle personen har tilgang til, og med en knapp for å administrere tilgangen brukeren har. 

Oversikten har søkefelt for å søke etter en person og mulighet for å begrense søket ved å velge hvilken enhet (avdeling) og rolle du vil søke opp. 

Med knappen Last ned brukerliste kan du velge å laste ned en liste som viser brukerne til en fil i csv-format. 

![Tilgang-oversikt med søkefelt og funksjonen for å laste ned brukerliste.](img\Falk2.5\Tilgangstildeler-ApplikasjonTilgang.png)

For en bruker som har flere roller enn det er plass til å vise i oversikten kan du velge knappen Vis tilganger. Når du velger Vis tilganger får du se de kombinasjonene av roller og enheter som denne brukeren har tilgang til. 

Når du velger knappen Administrer for en bruker i oversikten, kommer du til siden som viser informasjon om brukeren og de tilgangene brukeren har. 

![Oversikt over tilgangene en bruker har og som du kan administrere.](img\Falk2.5\Tilgangstildeler-ApplikasjonTilgangAdministrer.png)

Ut ifra de tilgangene du ser at brukeren har, kan du gi brukeren tilgang til roller og avdelinger som personen trenger, fjerne en eller flere tilganger, og reaktivere en eller flere tilganger som har vært deaktivert. 

- For å gi tilgang, velg en rolle fra nedtrekklisten, og skriv inn og søk opp den avdelingen tilgangen gjelder. 
- Når du har valgt både en rolle og søkt opp riktig avdelingen, kan du velge knappen Legg til. 
- Når du velger Legg til blir den rollen og avdelingen du har valgt lagt til i listen som viser brukerens tilganger, sammen med en knapp for å fjerne tilgangen. 
- Når du vil fjerne en rolle- og avdelingskombinasjon som brukeren har, kan du klikke Fjern tilgang for å ta vekk brukeren sin tilgang til den rollen og enheten. 
- For å reaktivere en tilgang kan du klikke knappen Reaktiver som vises sammen med tilgangen.  

For å gå tilbake og se oversikten over brukerne igjen, kan du velge Administrer brukertilganger øverst på siden. 

### <a name='Utsettautomatiskdeaktivering'></a>Utsett automatisk deaktivering
Tilgangene en bruker har kan bli automatisk deaktivert når brukeren ikke har logget inn i løpet av en gitt periode. Hvor lang tid det går før den eller de rettighetene brukeren har blir deaktivert, er satt til seks -6- måneder. Du kan utsette automatisk deaktivering for en bruker. [Klikk her å gå til veiledningen for å utsette deaktivering i Brukerdokumentasjon for Applikasjonsadmin.](Brukerdokumentasjon-applikasjonsadmin.md#Utsettautomatiskdeaktivering)


### <a name='Reaktiverdeaktiverttilgang'></a>Reaktiver deaktivert tilgang
For en bruker som har en eller flere tilganger som har blitt deaktivert, blir det sendt et varsel på epost til brukeren og til Tilgangstildeler om dette. Varselet til Tilgangstildeler har lenke til brukeren sine tilganger i Falk. Tilgangstildeler kan gjøre en deaktivert tilgang aktiv igjen ved å reaktivere denne tilgangen for brukeren. Brukeren trenger ikke søke om tilgangen på nytt. 
[Klikk her å gå til veiledningen for bruker som ønsker at tilgang blir reaktivert, i Brukerdokumentasjon for bruker.](Brukerdokumentasjon-bruker.md#Reaktivereendeaktiverttilgang)

For å reaktivere en deaktivert tilgang: 
- Velg applikasjonen i applikasjonsoversikten og gå til fanen Tilgang. 
- Finn brukeren i oversikten som viser brukere og velg Administrer bruker.
- På siden Administrer brukertilganger er det informasjon om deaktiverte tilganger, og for hver tilgang som har blitt deaktivert er knappen Reaktiver tilgjengelig. 
- Trykk Reaktiver-knappen for den tilgangen som skal gjøres aktiv igjen. 

Etter at tilgangen har blitt reaktivert for brukeren, blir tilgangen oppdatert og aktiv igjen. 

[Oversikten Brukerens tilganger som viser informasjon om deaktivert tilgang som kan reaktiveres](img\Falk2.5\AppAdmin-TilgangAdministrerBrukerReaktiver1.png)

Tips: Hvis en bruker har sendt ny søknad om den tilgangen som er deaktivert, i tillegg til å be om reaktivering av denne tilgangen, kan Tilgangstildeler velge å slette søknaden eller avvise søknaden med kommentar. Å reaktivere en tilgang påvirker ikke søknadsbehandlingen. Søknader blir liggende til de er behandlet, uavhengig av reaktivering. 


## <a name='Aktivitetslogg'></a>Aktivitetslogg 
Når du velger fanen som heter Aktivitetslogg for en applikasjon, får du en oversikt som viser aktiviteter som er gjort for applikasjonen. 

![Aktivitetslogg-oversikten som viser aktiviteter som rader i en liste.](img\Falk2.5\Tilgangstildeler-Aktivitetslogg.png)

I nedtrekklisten over aktivitetene kan du velge å se bestemte typer logginnslag, for eksempel logginnslag som viser når en bruker har logget på, når det er gitt rettighet til applikasjonen og når det er fjernet en rettighet til applikasjonen. 

![Aktivitetslogg-menyen med valgene for å se en bestemt type logginnslag.](img\Falk2.5\Tilgangstildeler-AktivitetsloggLoggtyper.png)

Logginnslagene i aktivtitetsloggen er ordnet etter tidspunkt, og hvert logginnslag kan utvides til å vise mer informasjon om aktiviteten som er gjort. Klikk på raden i oversikten for å utvide og se informasjon om aktiviteten. 

![Aktivitetslogg der et logginnslag er utvidet og viser mer informasjon om aktiviteten.](img\Falk2.5\Tilgangstildeler-AktivitetsloggUtvidetLogginnslag.png)

---
Mer informasjon og veiledninger:

>[ Til forsiden på Falk brukerveiledning](README.md)

>[ Veiledning for innlogging](LoggInn.md)

>[ Brukerveiledning for App Admin](Brukerdokumentasjon-applikasjonsadmin.md)

>[ Brukerveiledning for Bruker](Brukerdokumentasjon-bruker.md)

>[ Brukerveiledning for Falk Administrator](Brukerdokumentasjon-falkadmin.md)

>[ Brukerveiledning for M2M-klienter](Brukerdokumentasjon-m2m.md)

>[ Til toppen av denne siden](#Brukerveiledning-for-tilgangstildeler)