# Brukerveiledning for Falk Administrator

[Klikk her for veiledning for innlogging.](LoggInn.md)

## Innholdsliste: 
Varsler
Brukere
- Deaktivere og reaktivere brukere
M2M-klienter
API-ressurser
Registerkategorier
Applikasjoner
- Legg til ny applikasjon
- Egenskaper
- Klienter 


Falk Admininistrator har samme rettigheter som en [Applikasjonsadministrator](Brukerdokumentasjon-applikasjonsadmin.md)
I tillegg har Falk Administrator en fane i Falk som heter Administrere. Velg fanen Administrere for å se og velge hva du vil administrere: 
- Varsler
- Brukere
- M2M-klienter
- API-ressurser
- Registerkategorier
- Applikasjonstyper


    ![Menyen i fanen Administrere.](img\Falk2.5\FalkAdmin-Administrere.png)

## Varsler
Når du velger Varsler i Administrer-menyen, kommer du til en oversikt over varsler som er satt opp i Falk.
Disse varslene kan blir vist til alle brukere i Falk, hvis varslene er aktive.
Du har muligheten til å Legge til varsler, og til å endre og slette varsler herfra.

![Varsler-oversikten og tre forskjellige varsler som er vist fordi de er aktive.](img\Falk2.5\FalkAdmin-Varselnavn.png)

Klikk knappen Legg til nytt varsel for å opprette et nytt varsel. Skriv teksten varselet skal vise og velg den typen varsel det er: Enten Informasjon, Feil eller Advarsel. Hver type varsel blir vist med en egen farge og vises i det tidsrommet du setter opp. Klikk Lagre for å lukke skjemaet og legge til varselet. Varselet du har lagt til blir vist i oversikten som viser Varlser og du kan endre og slette det herfra. 

![Skjemaet for å legge til et varsel.](img\Falk2.5\FalkAdmin-VarselLeggTil.png)


## Brukere
Når du velger menypunktet Brukere kommer du til en side med et søke-felt hvor du kan skrive inn navn og søke opp brukere i Falk. 

Over søkefeltet er det knapper for å laste ned en liste som kan vise alle administratorer og alle tilgangstildelere i Falk. Denne listen er en fil i CSV-format.  

![Siden som viser brukere med søkefelt for å søke oppbrukere i Falk.](img\Falk2.5\FalkAdmin-Brukere_Søk.PNG)


### Søk etter brukere 
For å søke etter en eller flere brukere på siden som viser brukere, må du skrive inn minst 3 tegn i feltet for å få et søkeresultat. Du kan søke på navn, epostadresse eller telefonnummer. 

Hvis du får treff på søket ditt, blir det vist i en liste. Klikk den brukeren i listen som du vil gå inn på. 

Når du har valgt en bruker får du vist kontaktinformasjon og knapper for å deaktivere brukeren, og for å endre informasjon om brukeren. 
Hvilke tilganger brukeren har og hvilke søknader brukeren har sendt blir vist i egne faner, dvs. fanene Tilganger og Søknader.

![Skjema for å se og endre bruker i Falk.](img\Falk2.5\FalkAdmin-Bruker-admin.png)

### Deaktivere og reaktivere brukere
Falk Administrator har tilgang til å utsette deaktivering av tilganger og reaktivere tilganger som har blitt deaktivert for en bruker. Disse aktivitetene blir loggført som aktiviteter i Aktivitetsloggen for applikasjonen.  

[Klikk her å gå til veiledningen for å deaktivere og reaktivere brukere i Brukerdokumentasjon for Applikasjonsadmin.](Brukerdokumentasjon-applikasjonsadmin.md#L45-L46)


## M2M-Klienter
For å se og administrere M2M-klienter, maskin-til-maskin-klienter, kan du velge M2M-klienter under Administrere. Du kan lese mer om funksjonaliteten ved å klikke på lenken [M2M](Brukerdokumentasjon-m2m.md)


## API-ressurser
For å se og administrere API-ressurser i Falk, kan du velge API-ressurser under Aministrere. Dette kan du lese mer om ved å klikke på lenken [M2M](Brukerdokumentasjon-m2m.md)


## Registerkategorier
Når du velger Registerkategorier finner du en liste som viser kategorier hver applikasjon i Falk kan bli ordnet inn i.

![Registerkategorier-listen.](img\Falk2.5\FalkAdmin-Registerkategorier.png)

Som Falk Administrator har du mulighet til å legge til nye registerkategorier og endre på eller slette eksisterende registerkategorier.

![Skjema for å legge til registerkategori.](img\Falk2.5\FalkAdmin-RegisterkategorierLeggTil.png)


## Applikasjoner 
Som Falk Administrator har du oversikt over alle applikasjoner (registre) og kan admininstrere dem. Oversikten får du tilgang til når du velger fanen Applikasjoner på menyen. 

Over listen som viser applikasjoner vil du få et søke-felt. I søke-feltet kan du skrive inn navn og søke opp en bestemt applikasjon. Du kan velge å vise applikasjonene i listen i stigende eller fallende rekkefølge ved å klikke på pilene ved siden av Applikasjonsnavn og Scopenavn.

![Applikasjoner-listen med søkefelt.](img\Falk2.5\FalkAdmin-Applikasjoner.png)

For å se og administrere en bestemt applikasjon kan du klikke på raden for applikasjonen i oversikten. 

### Legg til ny applikasjon
Som Falk Administrator kan du legge til nye applikasjoner i Falk. Dette kan du gjøre ved å velge knappen Legg til ny applikasjon i Applikasjoner-oversikten.

![Legg til ny applikasjon-knapp.](img\FalkAdmin-LeggTilNyApplikasjonKnapp.PNG)

Når du har valgt Legg til ny applikasjon får du opp et skjema med felter og valg for den nye applikasjonen. Noen felt og valg er obligatoriske, og når skjemaet er fullført kan du lagre skjemaet og få opprettet den nye applikasjonen. 

![Skjemaet for å legge til ny applikasjon med fanen Egenskaper i fokus.](img\Falk2.5\FalkAdmin-Applikasjon_EgenskaperEndre.png)

Applikasjonen du har lagt til kan du finne i Applikasjoner-oversikten med navnet du har gitt applikasjonen og med scopenavnet du har fylt ut i skjemaet. 

Ønsker du å åpne en applikasjon for å få mer informasjon om den og gjøre endringer på den, kan du klikke raden til applikasjonen i Applikasjoner-oversikten. 

![Oversikten som viser applikasjoner i Falk.](img\Falk2.5\FalkAdmin-Applikasjoner.png)

### Egenskaper

Når du velger en applikasjon i Applikasjoner-oversikten og klikker på den slik at du åpner den, vil du komme til en fane som heter Egenskaper i fokus, og ha fane som heter Klienter i bakgrunnen. Fanen Egenskaper viser informasjon og innstillinger for  applikasjonen. Disse kan du redigere ved å klikke Endre-knappen. 

![Applikasjon med fanen Egenskaper i fokus.](img\Falk2.5\FalkAdmin-Applikasjon_EgenskaperEndre.png)

Når du har gjort endringene du ville gjøre på applikasjonen, kan du lagre dem ved å klikke Lagre. Etter at du har lagret får du en bekreftelse på skjermen om at applikasjonen er oppdatert. 

### Klienter
Det er også en fane bak fanen Egenskaper, og det er fanen Klienter. I denne fanen kan du se klienter som er lagt til for applikasjonen og du kan du legge nye klienter. 

For hver klient er det knapper for å åpne klienten og gjøre endringer på den, for å sette at en klient er registrert uri, og for å slette klienten.

![Applikasjon med fanen Klienter i fokus.](img\Falk2.5\FalkAdmin-Applikasjon_Klienter.png)

Når du velger knappen Legg til klient får du opp et skjema med felt du må fylle ut for å legge til den nye klienten. Når feltene er fylt ut klikker du Legg til i skjemaet for å lukke skjemaet og legge til klienten. Den nye klienten du har lagt til blir vist i listen i fanen Klienter. 
Pass på å klikke Lagre-knappen for å lagre klienter du har lagt til  applikasjonen. 

![Skjema for å legge til ny klient for en applikasjon.](img\Falk2.5\FalkAdmin-Applikasjon_KlienterLeggTilNy.png)

### __________________


>[> Til forsiden i Falk brukerveiledning](README.md)

>[> Til veiledning for innlogging](LoggInn.md)