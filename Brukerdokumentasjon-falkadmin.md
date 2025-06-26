
# FALK Brukerdokumentasjon

# <a name='Brukerveiledning-for-Falk-Administrator'></a>Brukerveiledning for Falk Administrator


INNHOLDSLISTE
<!-- vscode-markdown-toc -->
* [Innlogging](#Innlogging)
* [Falk Administrator](#FalkAdministrator)
* [Varsler](#Varsler)
* [Brukere](#Brukere)
	* [Søk etter brukere](#Sketterbrukere)
	* [Utsett automatisk deaktivering](#Utsettautomatiskdeaktivering)
	* [Reaktiver tilgang](#Reaktivertilgang)
* [M2M-Klienter](#M2M-Klienter)
* [API-ressurser](#API-ressurser)
* [Registerkategorier](#Registerkategorier)
* [Applikasjonstyper](#Applikasjonstyper)
* [Applikasjoner](#Applikasjoner)
	* [Legg til ny applikasjon](#Leggtilnyapplikasjon)
	* [Egenskaper](#Egenskaper)
	* [Klienter](#Klienter)

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

## <a name='FalkAdministrator'></a>Falk Administrator

Som Falk Admininistrator har du samme rettigheter som en [Applikasjonsadministrator](Brukerdokumentasjon-applikasjonsadmin.md). I tillegg har Falk Administrator en fane i Falk som heter Administrere. Velg fanen Administrere for å se og velge hva du vil administrere: 
- Varsler
- Brukere
- M2M-klienter
- API-ressurser
- Registerkategorier
- Applikasjonstyper


    ![Menyen i fanen Administrere.](img\Falk2.5\FalkAdmin-Administrere.png)

## <a name='Varsler'></a>Varsler
Når du velger Varsler i Administrer-menyen, kommer du til en oversikt over varsler som er satt opp i Falk.
Disse varslene kan blir vist til alle brukere i Falk, hvis varslene er aktive.
Du har muligheten til å Legge til varsler, og til å endre og slette varsler herfra.

![Varsler-oversikten og tre forskjellige varsler som er vist fordi de er aktive.](img\Falk2.5\FalkAdmin-Varselnavn.png)

Klikk knappen Legg til nytt varsel for å opprette et nytt varsel. Skriv teksten varselet skal vise og velg den typen varsel det er: Enten Informasjon, Feil eller Advarsel. Hver type varsel blir vist med en egen farge og vises i det tidsrommet du setter opp. Klikk Lagre for å lukke skjemaet og legge til varselet. Varselet du har lagt til blir vist i oversikten som viser Varlser og du kan endre og slette det herfra. 

![Skjemaet for å legge til et varsel.](img\Falk2.5\FalkAdmin-VarselLeggTil.png)


## <a name='Brukere'></a>Brukere
Når du velger menypunktet Brukere kommer du til en side med et søke-felt hvor du kan skrive inn navn og søke opp brukere i Falk. 

Over søkefeltet er det knapper for å laste ned en liste som kan vise alle administratorer og alle tilgangstildelere i Falk. Denne listen er en fil i CSV-format.  

![Siden som viser brukere med søkefelt for å søke oppbrukere i Falk.](img\Falk2.5\FalkAdmin-Brukere_Søk.PNG)


### <a name='Sketterbrukere'></a>Søk etter brukere 
For å søke etter en eller flere brukere på siden som viser brukere, må du skrive inn minst 3 tegn i feltet for å få et søkeresultat. 
Du kan søke på navn, epostadresse eller telefonnummer. 

Hvis du får treff på søket ditt, blir det vist i en liste. Klikk den brukeren i listen som du vil gå inn på. 

Når du har valgt en bruker får du vist kontaktinformasjon og knapper for å deaktivere brukeren, og for å endre informasjon om brukeren. 
Hvilke tilganger brukeren har og hvilke søknader brukeren har sendt blir vist i egne faner, dvs. fanene Tilganger og Søknader.

![Skjema for å se og endre bruker i Falk.](img\Falk2.5\FalkAdmin-Bruker-admin.png)

### <a name='Utsettautomatiskdeaktivering'></a>Utsett automatisk deaktivering 
Det er mulig å utsette automatisk deaktivering av tilganger en bruker har, og å reaktivere tilganger som har blitt deaktivert for en bruker. Disse aktivitetene blir loggført som aktiviteter i Aktivitetsloggen for applikasjonen.  

[Klikk her å gå til veiledningen for å utsette deaktivering i Brukerdokumentasjon for Applikasjonsadmin.](Brukerdokumentasjon-applikasjonsadmin.md#Utsettautomatiskdeaktivering)

### <a name='Reaktivertilgang'></a>Reaktiver tilgang
For en bruker som har en eller flere tilganger som har blitt deaktivert, kan du gjøre tilgangen aktiv igjen:
[Klikk her å gå til veiledningen for å reaktivere en tilgang som har blitt deaktivert i Brukerdokumentasjon for Applikasjonsadmin.](Brukerdokumentasjon-applikasjonsadmin.md#Reaktivertilgang)
En bruker som har fått deaktivert en tilgang trenger ikke søke om tilgangen på nytt. Brukeren kan be om reaktivering via brukerprofilsiden. 

## <a name='M2M-Klienter'></a>M2M-Klienter
For å se og administrere M2M-klienter, maskin-til-maskin-klienter, kan du velge M2M-klienter under Administrere. 
Du kan lese mer om funksjonaliteten ved å klikke på lenken [Brukerveiledning - M2M](Brukerdokumentasjon-m2m.md##M2Mklienter)


## <a name='API-ressurser'></a>API-ressurser
For å se og administrere API-ressurser i Falk, kan du velge API-ressurser under Aministrere. 
Dette kan du lese mer om ved å klikke på lenken [Brukerveiledning - M2M](Brukerdokumentasjon-m2m.md##API-ressurser)


## <a name='Registerkategorier'></a>Registerkategorier
Når du velger Registerkategorier finner du en liste som viser kategorier hver applikasjon i Falk kan bli ordnet inn i.

![Registerkategorier-listen.](img\Falk2.5\FalkAdmin-Registerkategorier.png)

Som Falk Administrator har du mulighet til å legge til nye registerkategorier og endre på eller slette eksisterende registerkategorier.

![Skjema for å legge til registerkategori.](img\Falk2.5\FalkAdmin-RegisterkategorierLeggTil.png)


## <a name='Applikasjonstyper'></a>Applikasjonstyper
Når du velger Applikasjonstyper i Administrere-menyen, finner du en liste som viser de applikasjonstypene en applikasjon i Falk kan settes opp med.
Listen viser hver applikasjonstype med ett eller flere claims som er lagt til hver applikasjonstype. 

![Applikasjonstyper-listen.](img\Falk2.5\FalkAdmin-Applikasjonstyper.png)

Som Falk Administrator har du mulighet til å legge til nye applikasjonstyper og endre på hver applikasjonstype som vises i listen.

Når du velger Legg til ny applikasjonstype blir skjemaet for å registrere den nye applikasjonstypen åpnet. Skjemaet har felt for å gi applikasjonstypen et navn og en nedtrekkliste for å velge blant tilgjengelige claim-typer som skal legges til denne applikasjonstypen. 

![Skjema for å legge til ny applikasjonstype.](img\Falk2.5\FalkAdmin-Applikasjonstyper_LeggTilNy.png)

Når du har valgt riktig claim-type bruker du avkryssingsboksene for å definere hva claim-typen skal angi: 
- EnhetsId, OrgUnitId, ReshId, 
- roller, og 
- bestemme om det skal være lov å sette spesifikke claim-verdier. 

Etter at claim-type er valgt og du har definert hva den skal angi, kan du legge til claim-typen ved å velge knappen Legg til i tilgjengelige claim-typer. 
Claim-typen du har lagt til blir vist i oversikten over claim-typer nederst i skjemaet. 

![Applikasjonstype med en claim-type lagt til.](img\Falk2.5\FalkAdmin-Applikasjonstyper_LeggTilNy_Claim-type.png)


Når en eller flere claim-typer er lagt til for applikasjonstypen er de vist i oversikten med informasjon claim-typen tillater å angi roller, enhetsId og spesifikke verdier. 
Merk at det er mulig å slette en claim-type med Slett-knappen helt frem til du lagrer applikasjonstypen. 

![Claim-typer med tilgjengelig slette-knapp før applikasjonstypen er lagret.](img\Falk2.5\FalkAdmin-Applikasjonstyper_LeggTilNy_Claim-type2.png)



## <a name='Applikasjoner'></a>Applikasjoner 
Som Falk Administrator har du oversikt over alle applikasjoner (registre) og kan admininstrere dem. Oversikten får du tilgang til når du velger fanen Applikasjoner på menyen. 

Over listen som viser applikasjoner vil du få et søke-felt. I søke-feltet kan du skrive inn navn og søke opp en bestemt applikasjon. 
Du kan velge å vise applikasjonene i listen i stigende eller fallende rekkefølge ved å klikke på pilene ved siden av Applikasjonsnavn og Scopenavn.

![Applikasjoner-listen med søkefelt.](img\Falk2.5\FalkAdmin-Applikasjoner.png)

For å se og administrere en bestemt applikasjon kan du klikke på raden for applikasjonen i oversikten. 

### <a name='Leggtilnyapplikasjon'></a>Legg til ny applikasjon
Som Falk Administrator kan du legge til nye applikasjoner i Falk. Dette kan du gjøre ved å velge knappen Legg til ny applikasjon i Applikasjoner-oversikten.

![Legg til ny applikasjon-knapp.](img\FalkAdmin-LeggTilNyApplikasjonKnapp.PNG)

Når du har valgt Legg til ny applikasjon får du opp et skjema med felter og valg for den nye applikasjonen. Noen felt og valg er obligatoriske, og når skjemaet er fullført kan du lagre skjemaet og få opprettet den nye applikasjonen. 

![Skjemaet for å legge til ny applikasjon med fanen Egenskaper i fokus.](img\Falk2.5\FalkAdmin-Applikasjon_EgenskaperEndre.png)

Applikasjonen du har lagt til kan du finne i Applikasjoner-oversikten med navnet du har gitt applikasjonen og med scopenavnet du har fylt ut i skjemaet. 

Ønsker du å åpne en applikasjon for å få mer informasjon om den og gjøre endringer på den, kan du klikke raden til applikasjonen i Applikasjoner-oversikten. 

![Oversikten som viser applikasjoner i Falk.](img\Falk2.5\FalkAdmin-Applikasjoner.png)

### <a name='Egenskaper'></a>Egenskaper

Når du velger en applikasjon i Applikasjoner-oversikten og klikker på den slik at du åpner den, vil du komme til en fane som heter Egenskaper i fokus, og ha fane som heter Klienter i bakgrunnen. 
Fanen Egenskaper viser informasjon og innstillinger for  applikasjonen. Disse kan du redigere ved å klikke Endre-knappen. 

![Applikasjon med fanen Egenskaper i fokus.](img\Falk2.5\FalkAdmin-Applikasjon_EgenskaperEndre.png)

Når du har gjort endringene du ville gjøre på applikasjonen, kan du lagre dem ved å klikke Lagre. Etter at du har lagret får du en bekreftelse på skjermen om at applikasjonen er oppdatert. 

### <a name='Klienter'></a>Klienter
Det er også en fane bak fanen Egenskaper, og det er fanen Klienter. I denne fanen kan du se klienter som er lagt til for applikasjonen og du kan du legge nye klienter. 

For hver klient er det knapper for å åpne klienten og gjøre endringer på den, for å sette at en klient er registrert uri, og for å slette klienten.

![Applikasjon med fanen Klienter i fokus.](img\Falk2.5\FalkAdmin-Applikasjon_Klienter.png)

Når du velger knappen Legg til klient får du opp et skjema med felt du må fylle ut for å legge til den nye klienten. 
I skjemaet for å legge til ny klient kan du velge klienttype. Hvis du velger klienttype Code blir feltene for å registrere URI, Redirect-URI, Front CHannel Logout-URI og Post Logout Redirect-URI vist sammen med felt for å legge til en eller flere klienthemmeligheter:

![Skjema for å legge til ny klient for en applikasjon.](img\Falk2.5\FalkAdmin-Applikasjon_KlienterLeggTilNy.png)


Hvis du velger klienttype Hubro viser skjemaet felt du må fylle ut for denne typen klient: 

![Skjema for å legge til ny Hybro-klient for en applikasjon.](img\Falk2.5\FalkAdmin-Applikasjon_KlienterLeggTilNy_HubroClient.png)

Når feltene i skjemaet er fylt ut med klienttype, navn og innstillinger og du har lagt til en eller flere klienthemmeligheter, klikker du Legg til i skjemaet for å lagre og lukke skjemaet. 

Når du har klikket Legg til i skjemaet for den nye klienten blir skjemaet lukket, og du kommer tilbake til fanen Klienter. Den nye klienten du har lagt til blir vist i listen i fanen Klienter. 
Pass på å klikke Lagre-knappen for å lagre en eller flere klienter som du har lagt til applikasjonen, før du går ut av applikasjonen.


---
Mer informasjon og veiledninger:

>[ Til forsiden i Falk brukerveiledning](README.md)

>[ Veiledning for innlogging](LoggInn.md)

>[ Brukerveiledning for App Admin](Brukerdokumentasjon-applikasjonsadmin.md)

>[ Brukerveiledning for Bruker](Brukerdokumentasjon-bruker.md)

>[ Brukerveiledning for M2M-klienter](Brukerdokumentasjon-m2m.md)

>[ Brukerveiledning for Tilgangstildeler](Brukerdokumentasjon-tilgangstildeler.md)

>[ Til toppen av denne siden](#Brukerveiledning-for-Falk-Administrator)