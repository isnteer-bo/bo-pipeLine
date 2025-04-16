| Parameter        | Erklärung                                                                 | Beispiel                                             |
|------------------|---------------------------------------------------------------------------|------------------------------------------------------|
| --callerNumber   | Die Nummer des Anrufers. Wird benötigt, um den Anrufer zu identifizieren. | --callerNumber="+4171123123123"                     |
| --callerName     | Der Name des Anrufers. Falls die Applikation diesen übergibt, kann er verwendet werden – ansonsten kann das Feld leer bleiben. | --callerName="Max Mustermann"                       |
| --eventType      | Wird benötigt, um zu identifizieren, welches Ereignis der Anruf darstellt (z. B. Angebot, angenommen, aufgelegt). | --eventType="call-offering" / --eventType="call-connected" / --eventType="call-disconnected" |
