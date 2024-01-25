# sudo keys (webbshop)

## Beskrivning

Sudo keys är en applikation där användare kan ta del av vår enomra produktlistning och kategorier av spel. Med en dynamisk lagerhantering för att övervaka och uppdatera lagernivån av olika givna produkter. 
Med en användarvänlig varukorg kan användare lägga till produkter och slutföra sina köptransaktioner. Användvaren kan hantera registering och inloggning på webbshoppen för att spåra sina beställningar och hantera sina konton. 

## Användare och roller

Här skriver du ner vilka typer av användare (som i inloggade användare) det finns, och vad de har för rättigheter, det vill säga, vad de kan göra (tänk admin, standard användare, etc).

### Exempel (ta bort)

Gästanvändare - oinloggad
. Kan söka efter titlar och se genomsnittligt betyg. Kan inte se eller skriva kommentarer eller sätta egna betyg.

Standardanvändare - inloggad. Kan allt gästanvändare kan, men kan även lägga in nya böcker och skriva kommentarer etc. Kan ta bort sitt eget konto och information kopplat till det.

Adminanvändare - kan ta bort/editera böcker, kommentarer och användare.

## ER-Diagram

![Er-Diagram](./er_diagram.png?raw=true "ER-diagram")

## Gränssnittsskisser

**Login**

![Er-Diagram](./ui_login.png?raw=true "ER-diagram")

**Visa bok**

![Er-Diagram](./ui_show_book.png?raw=true "ER-diagram")