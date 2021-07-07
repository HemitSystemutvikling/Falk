# Step-By-Step for Applikasjonsadministrator

[Klikk her for veiledning for innlogging.](LoggInn)

Applikasjonsadministrator har samme rettigheter som en [Tilgangstildeler](Brukerdokumentsjon-tilgangstildeler)

I tillegg har AppAdmin tre ekstra faner under en applikasjon; Tilgangsdelere, Aktivitetslogg og Importer Preautoriserte Søknader.

## Tilgangdelere
I Tilgangdelere fanen finner du en liste over Tilgangstildelere for applikasjonen.
Innslagene i denne listen kan utvides for å se hvilke enheter personen er tilganstildeler for og legge til flere enheter.
Nederst på siden har du også mulighet til å søke opp en ny person og gjøre de til tilgangstildeler for applikasjonen.
Du har også mulighet til å laste den den CSV fil med all tilgangstildeler.

![AppAdmin-Tilgangdelere](img/AppAdmin-Tilgangsdelere.PNG)

## Aktivitetslogg
I Aktivitetslogg fanen finner du en liste over innlogginger på applikasjonen.
Informasjonen inkluderer hvem som har logget inn, når de logget inn og med hvilke rolle og enhet.

![AppAdmin-Aktivitetslogg](img/AppAdmin-Aktivitetslogg.PNG)

## Importer Preautoriserte Søknader
I Importer Preautoriserte Søknader fanen finner du en tekst boks hvor du kan legge inn et json-objekt.
Dette json-objektet inneholder en liste over personer og hvilke rettigheter de skal ha.


    {
        "OrderDescription": "This is an order",
        "PreAuthorizedOrders": [{
            "PersonIdentifier": "17078614919",
            "FirstName": "Putte",
            "LastName": "Andresen",
            "PhoneNumber": "99887766",
            "Email": "putte.andresen@hemit.no",
            "Claims": [{
                    "Type": "http://schemas.microsoft.com/ws/2008/06/identity/claims/role",
                    "Value": "Pasientansvarlig"
                },
                {
                    "Type": "http://schemas.hemit.no/Hemit/Mqr/Claims/AuthorizedForOrganizationalUnit",
                    "Value": "100320"
                }
            ]
        }]
    }

![AppAdmin-ImporterPreautoriserteSøknader](img/AppAdmin-ImporterPreautoriserteSøknader.PNG)