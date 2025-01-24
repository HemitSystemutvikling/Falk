
# <a name='Prosedyrer'></a>Prosedyrer

INNHOLDSLISTE
<!-- vscode-markdown-toc -->
* [Prosedyre for godkjennelse av søkere i portal for tilgangsforvaltning (Risiko 4.1)](#ProsedyreforgodkjennelseavskereiportalfortilgangsforvaltningRisiko4.1)
* [Funksjonalitet for godkjennelse av søkere i portal for tilgangsforvaltning (Risiko 4.2)](#FunksjonalitetforgodkjennelseavskereiportalfortilgangsforvaltningRisiko4.2)
* [Prosedyrer for oppsett og endring av roller og rettigheter (Risiko 15)](#ProsedyrerforoppsettogendringavrollerogrettigheterRisiko15)
* [Rutine for å rydde i brukerprofiler (Risiko 18)](#RutineforryddeibrukerprofilerRisiko18)
* [Prosedyre for agerering på automatiske varsler om endringer (Risiko 20)](#ProsedyreforagereringpautomatiskevarsleromendringerRisiko20)
* [Prosedyre for autorisasjon til Administrasjonsregisteret (Risiko 24 (og 25))](#ProsedyreforautorisasjontilAdministrasjonsregisteretRisiko24og25)
* [Prosedyrer for å følge med endringer i HelseID (Risiko 28)](#ProsedyrerforflgemedendringeriHelseIDRisiko28)

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

## <a name='ProsedyreforgodkjennelseavskereiportalfortilgangsforvaltningRisiko4.1'></a>Prosedyre for godkjennelse av søkere i portal for tilgangsforvaltning (Risiko 4.1)
-	Risiko 4: «Det må utarbeides prosedyre(r) og utvikles funksjonalitet for godkjennelse av søkere i portal for tilgangsforvaltning med basis i: 
    - Hvem som kan autorisere for å gi tilgang (registeransvarlig)
        - `Dette inngår i NHN driftsdok, etableres i forbindelse med bestilling av register.`
        - `Det er opprettet en ny rolle, Applikasjonsadministrator, som kan gi tilgang.`

**Formål:** Formålet med denne prosedyren er å sørge for at det altid skal være en Tilgangstildeler for en applikasjon.

**Omfang:**  Personen som setter opp applikasjonen hos Norsk Helsenett (NHN) og den ansvarlige hos applikasjonen.

**Definisjon:**  Ingen

**Ansvar og Myndighet:** Norsk Helsenett (NHN)

**Beskrivelse:**
NHN har ansvaret for å sørge for at de har fått informasjon om hvem som skal være Tilgangstildeler for applikasjonen.
- Dette må ligge som et punkt under informasjon NHN trenger får å sette opp en ny applikasjon, på lik linje med navn og url til applikasjonen.

**Referanser og vedlegg:**  Ingen

---
## <a name='FunksjonalitetforgodkjennelseavskereiportalfortilgangsforvaltningRisiko4.2'></a>Funksjonalitet for godkjennelse av søkere i portal for tilgangsforvaltning (Risiko 4.2)
-	Risiko 4: «Det må utarbeides prosedyre(r) og utvikles funksjonalitet for godkjennelse av søkere i portal for tilgangsforvaltning med basis i: 
    - Hyppighet i å bruke portalen og hvem som skal håndtere varsler som sendes fra varslingstjenesten»
        - `Tilgangstildeler`

**Formål:** Formålet med denne prosedyren er å beskrive bruke portalen og hvem som skal håndtere varsler som sendes fra varslingstjenesten.

**Omfang:**  Personen som setter opp applikasjonen hos NHN og den ansvarlige hos applikasjonen.

**Definisjon:**  Ingen

**Ansvar og Myndighet:** Tilgangstildeler

**Beskrivelse:**
Per nå gjøres dette løpende per bestilling.
<!-- Tilgangstildeler har ansvaret for å sørge for at de gir informasjon om hyppighet av varsler hvis det skal være noe annet en default.
- I likhet med 4.1, dette bør være et punkt under informasjon NHN trenger. (Synes det skal være med selv om det er default) -->

**Referanser og vedlegg:**  Ingen

---
## <a name='ProsedyrerforoppsettogendringavrollerogrettigheterRisiko15'></a>Prosedyrer for oppsett og endring av roller og rettigheter (Risiko 15)
-	Risiko 15: «Etabler prosedyrer for oppsett og endring av roller og rettigheter»
    - `Selve tildeling og oppfølging av endringer. Tilgangstildeles må sørge for å fjerne rettighet når noen slutter. Bruker søker eventuelle nye rettigheter.`

**Formål:** Fårmålet med denne prosedyren er å sørge for at retighetter som ikke er korrekt blir endret til å være korrekt.

**Omfang:**  Tilgangstildeler

**Definisjon:**  Ingen

**Ansvar og Myndighet:** Tilgangstildeler

**Beskrivelse:**
Tilgangstildeler har ansvaret for at brukere som søker får tildelt riktig tilgang.
Hvis det skjer at en bruker er tildelt feil tilgang skal Tilgangstildeler fjerne den tilgangen som er feil og gi brukeren den tilgangen som brukeren skulle hatt.
- Mest sannsynlig at bruker sier ifra at brukeren ikke har fått den tilgangen brukeren skulle hatt.
- Tilgangstildeler kan deretter fjerne gitt tilgang og gi brukeren tilgangen som de skulle ha.
- Tilgangstildeler bør gå gjennom alle brukere å se over at brukerne har de tilgangene de skal ha, og bare de tilgangene de skal ha.

**Referanser og vedlegg:** Ingen

---
<!-- ## Risiko 17
`Er ikke dette 4.1? Mulig jeg ikke skjønner denne`  
-	Risiko 17: «Det må utarbeides prosedyre(r) for godkjennelse av søkere i portal for tilgangsforvaltning med basis i hvem som kan autorisere for å gi tilgang (registeransvarlig)
    - `Dette inngår i NHN driftsdok, etableres i forbindelse med bestilling av register. NHN tildeler her roller etter bestilling fra regsitereier.`

**Formål:** 

**Omfang:**  

**Definisjon:**  

**Ansvar og Myndighet:** 

**Beskrivelse:**

**Referanser og vedlegg:** 

--- -->
## <a name='RutineforryddeibrukerprofilerRisiko18'></a>Rutine for å rydde i brukerprofiler (Risiko 18)
-	Risiko 18: «Virksomheten må gjøres oppmerksom på at de skal etablere rutiner for å rydde i brukerprofiler» - («…organisasjonen må utarbeide og dokumentere prosedyrer og rutiner for forvaltning av tilgang til administrasjonsgrensesnittet») hvilken rutine benytter Falk? 
    - `Exitkontroll. Tilgangstildeler må fjerne roller hvis bruker ikke lenger skal ha tilgang. Må gjennomgås en gang i året.`

**Formål:** Formålet med denne prosedyren er å sørge for at brukere som ikke skal ha tilgang ikke har dette.

**Omfang:**  Tilgangstildeler

**Definisjon:**  

**Ansvar og Myndighet:** Tilgangstildeler

**Beskrivelse:**
Tilgangstildeler har ansvar for å fjerne tlganger til brukere som slutter eller flytter.
Alle tilganger må gå gjennom en gang i året for å sørge for at ingen ble glemt.
- Tilgangstildeler må legge til et punkt i listen som gjennomgås når en bruker slutter, hvor det sjekkes at tilganger brukeren har blir fjernet.
- Tilgangstildeler bør gå gjennom alle brukere minimum en gang i året og se over at brukere har de tilgangene de skal ha, og bare de tilgangene de skal ha.

**Referanser og vedlegg:** 

---
## <a name='ProsedyreforagereringpautomatiskevarsleromendringerRisiko20'></a>Prosedyre for agerering på automatiske varsler om endringer (Risiko 20)
-	Risiko 20: «Det må utarbeides en prosedyre slik at registeransvarlig agerer på automatiske varsler om endringer»
    - `Prosedyre for å håndtere endringer iiht varsler – tilgangstildeler sitt ansvar.`

**Formål:** Formålet med denne prosedyren er å sørge for at Tilgangstildeler behandler søknader som kommer inn.

**Omfang:**  Tilgangstildeler

**Definisjon:**  Registeransvarlig i denne sammenhengen er Tilgangstildeler.

**Ansvar og Myndighet:** Tilgangstildeler

**Beskrivelse:**
Tilgangstildeler har ansvaret for at søknadene som kommer inn for applikasjonen sin blir besvart innen to-tre virkedager.

**Referanser og vedlegg:** Ingen

---
## <a name='ProsedyreforautorisasjontilAdministrasjonsregisteretRisiko24og25'></a>Prosedyre for autorisasjon til Administrasjonsregisteret (Risiko 24 (og 25))
-	Risiko 24 (og 25): «Det må etableres prosedyre for autorisasjon til Administrasjonsregisteret» 
    - `Dette inngår i NHN driftsdok, etableres i forbindelse med bestilling av register.`

**Formål:** Formålet med denne prosedyren er å sørge for at ikke hvem som helst kan opprette applikajsoner.

**Omfang:**  Norsk Helsenett (NHN)

**Definisjon:**  Ingen

**Ansvar og Myndighet:** Norsk Helsenett (NHN)

**Beskrivelse:** 
Norsk Helsenett (NHN) har ansvaret for at bare autoriserte personer har tilgang til Falk Admin-grensesnittet.
Hemit sender en bestilling for ny applikasjon til NHN og de følger sine rutiner for opprettelse.

**Referanser og vedlegg:** Ingen

---
## <a name='ProsedyrerforflgemedendringeriHelseIDRisiko28'></a>Prosedyrer for å følge med endringer i HelseID (Risiko 28)
-	Risiko 28: «Det må etableres prosedyrer for å følge med endringer i HelseID»
    - `I ferd med å etablere rutine for mottak av changelog. Endringer må fanges opp av Hemit.`

**Formål:** Formålet med denne prosedyren er å sørge for at Falk er oppdatert til å fungere med siste versjon av HelseID

**Omfang:**  Hemit

**Definisjon:**  Ingen

**Ansvar og Myndighet:** Hemit

**Beskrivelse:**
Hemit mottar changelog fra NHN. Endringer må fanges opp av Hemit.

**Referanser og vedlegg:** Ingen

---

Mer informasjon og veiledninger:

>[ Til forsiden i Falk brukerveiledning](README.md)

>[ Til veiledning for innlogging](LoggInn.md)

>[ Til toppen av denne siden](#prosedyrer)