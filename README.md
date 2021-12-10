# Falk

### Målet med Falk
Falk skal fungere som en felles autoriseringsløsning for de nasjonale kvalitetsregistrene på plattformene:
-	eReg
-	MRS 
-	OpenQReg

Den skal også kunne brukes av fellesløsninger som Rapporteket. Falk skal ivareta sikker autentisering og autorisering, samt administrasjon av dette, på en brukervennlig måte, og samtidig ivareta Normen sine krav. Den eksisterende autorisasjonsløsningen for nasjonale kvalitetsregistre, helseregister.no, har flere kjente svakheter som Falk ønsker å utbedre. De viktigste svakhetene er at vi ikke vet sikkert hvem det er som søker om tilganger og at brukerne lett kan søke om og få tildelt for høye rettigheter. Det er også en utfordring at helsepersonell må logge på svært mange systemer i løpet av en dag. Falk sikter på å løse disse problemene ved å etablere gode rutiner og grensesnitt for søknad og tildeling av tilganger. Vi skal ta i bruk HelseID som kilde til identiteter og vi skal sikre at tilgangssøkers identitet er godt verifisert før vi lagrer en søknad. Målet med Falk er at alle nasjonale kvalitetsregistre skal kunne ta i bruk HelseID uten å måtte håndtere brukerinformasjon eller tilgangsinformasjon selv. Falk vil også være gjenbrukbar for andre konsumenter med lignende behov. På sikt vil HelseID tilby fødererte identiteter fra alle identitetsleverandører med kobling til Helsenettet. Når dette er etablert vil vi kunne tilby «single sign-on» til alle kvalitetsregistrene. På kort sikt må vi håndtere identiteter i Falk. Pålogging her gjelder også internasjonale brukere.



### Brukerdokumentasjon

[Veiledning for innlogging](LoggInn.md)

[Bruker](Brukerdokumentsjon-bruker.md)

Bruker er en falk rolle som de fleste kommer til å ha. De vil bruke falk til å søke om tilgang og logge inn på applikasjoner.

[Tilgangstildeler](Brukerdokumentsjon-tilgangstildeler.md)

Tilgangstildeler er en falk rolle som er tildelt de som skal behanmdle søknader fra brukere og gi de rett tilgang.

[Applikasjons Administrator](Brukerdokumentasjon-appliokasjonsadmin.md)

Applikasjons Administrator er en falk rolle som administrerer en applikasjon og bestemmer hvem som skal være Tilgangstildeler for den applikasjonen.

[Falk Administrator](Brukersokumantasjon-falkadmin.md)

Falk Administrator er en falk rolle som administrerer Falk. Denne rollen kan legge til nye applikasjoner og administere alt inne i falk.
Det er bare NHN som har denne rollen.

[M2M](Brukerdokumentasjon-m2m.md)

M2M er Maskin til Maskin. Dette styrer tilganger som maskiner har for å komunisere med applikasjoner.

### Prosedyrer/rutiner 

[Prosedyrer](Prosedyrer.md)



