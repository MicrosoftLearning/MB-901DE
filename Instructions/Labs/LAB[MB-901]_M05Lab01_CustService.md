---
lab:
    title: 'Lab 01: Entdecken Sie Dynamics 365 Customer Service'
    module: 'Modul 05: Einführung in Dynamics 365 Customer Service'
---

# MB-901: Grundlagen von Dynamics 365 
## Modul 5, Lab 1 – Entdecken von Dynamics 365 Customer Service 

**Voraussetzungen:** Führen Sie die folgenden Aufgaben aus, bevor Sie die Schritte dieses Labs ausführen: 

**Optional:**
1. Wechseln Sie in der Dynamics 365-Instanz zu **Einstellungen**, und wählen Sie > **Datenverwaltung** aus. 
1. Wählen Sie **Beispieldaten** aus. 
1. Wenn die Beispieldaten nicht installiert sind, wählen Sie **Beispieldaten installieren** aus. Es kann einige Minuten dauern, bis die Beispieldaten angezeigt werden. Sie können die Anwendung jedoch während der Installation weiter verwenden. 
1. Wählen Sie **Schließen** aus. 

**Szenario:**
Als Kundendienstmitarbeiter müssen Sie Ihre Kundenanforderungen und -probleme verfolgen, indem Sie Supportanfragen in Dynamics 365 Customer Service erstellen. Wenn ein Debitor den Support mit einer Frage oder einem Problem kontaktiert, können Sie schnell überprüfen, ob eine Anfrage vorliegt, oder eine neue Anfrage öffnen und das Problem verfolgen. Sie können eine Anfrage auch eskalieren, neu zuweisen oder wieder in die Servicewarteschlange stellen, wenn Sie nicht über genügend Informationen oder Zeit verfügen, um an ihr zu arbeiten.

Bevor Sie Support leisten, können Sie auch die Berechtigungen des Kunden überprüfen. Berechtigungen sind wie Verträge, die Ihnen sagen, auf welche Art von Support ein Kunde Anspruch hat. Sie können sehen, ob die Supportbedingungen auf der Anzahl der Stunden oder Fälle, dem Supportkanal oder auf dem Produkt oder der Dienstleistung basieren, die der Kunde gekauft hat.

Um Ihnen bei der Auswahl des richtigen Status einer Anfrage zu helfen, hat Ihr Administrator möglicherweise die Einstellungen so vorgenommen, dass nur eine begrenzte Anzahl von Status basierend auf dem aktuellen Status einer Anfrage angezeigt wird.

## Anweisungen

### Erstellen einer Anfrage

1. Nagivieren Sie im **Kundenservicehub** zu **Service** > **Anfragen**.
1. Wählen Sie **Neue Anfrage** aus.
1. Geben Sie im Feld **Anfragetitel** den Text **Seahorse Smart Watch** ein.
1. Wählen Sie dann im Feld **Kunde** den Kunden **Fabrikam** aus. 
1. Geben Sie im Feld **Beschreibung** den Text **Problem mit der Smartwatch** ein.
1. Klicken Sie auf die Registerkarte **Details**.
1. Klicken Sie im Feld **Kontakt** auf die Schaltfläche **Kontaktsuche**, und wählen Sie einen vorhandenen Kontakt für die Anfrage aus oder klicken Sie auf **Neu** in den Inline-Suchergebnissen, um einen neuen Kontaktdatensatz zu erstellen.
1. Klicken Sie auf **Speichern**.
1. Um Ihr Gespräch mit dem Kunden nachzuverfolgen, klicken Sie im Abschnitt **Zeitachse** auf **+**, um Informationen und Aktivitäten hinzuzufügen.
1. Klicken Sie auf **Notiz**.
1. Geben Sie im Feld **Titel** den Text **Defekte Smartwatch** ein.
1. Geben Sie im Feld **Notiz** dann den Text **Zur Reparatur schicken** ein.
1. Klicken Sie auf **Notiz hinzufügen**. 
14.	Um zu sehen, welche Art von Unterstützung Sie dem Debitor bieten sollten, klicken Sie auf die Schaltfläche **Berechtigungssuche**, und wählen Sie eine aktive Berechtigung aus.
 **Hinweis:** Wenn für den Kunden keine Berechtigung existiert, ist dies leer.
1. Klicken Sie auf **Speichern**.

### Eine Lösung anhand ähnlicher Anfragen finden

**Hinweis:** Sie können sich bereits gelöste Fälle ansehen, um festzustellen, ob diese Ihnen bei der Lösung des offenen Falls, an dem Sie arbeiten, helfen können. Wenn das Thema der Anfrage, an der Sie arbeiten, beispielsweise „Defekte Smartwatch“ ist, können Sie nach gelösten Anfragen mit demselben Thema suchen, um Hilfe bei Ihrer aktuellen Anfrage zu erhalten.

### Anfrage abschließen

Stellen Sie vor dem Lösen einer Anfrage sicher, dass alle Anfrageaktivitäten geschlossen sind. Andernfalls erhalten Sie eine Meldung, dass Sie noch offene Aktivitäten im Zusammenhang mit der Anfrage haben. Diese werden abgebrochen, wenn die Anfrage gelöst ist.

1. Gehen Sie zu **Service** > **Anfragen**.
1. Öffnen Sie die Anfrage **Seahorse Smart Watch** in der Liste der aktiven Anfragen, um sie abzuschließen.
1. Wählen Sie auf der Befehlsleiste **Anfrage abschließen** aus.
1. Wählen Sie im Dialogfeld **Anfrage abschließen** in der Liste **Abschlusstyp** die Option **Problem behoben** aus.
1. Geben Sie in das Feld **Abschluss** den Text **Repariert** ein.
1. Die tatsächlich aufgewendete Zeit für alle Aktivitäten in dieser Anfrage, aufgezeichnet im Feld **Dauer** für jede Aktivität, wird automatisch im Feld **Gesamtzeit** ausgefüllt.
1. Wählen Sie in der Liste **Abzurechnende Zeit** die Option **30 Minuten** als die Zeit aus, die für die Anfrage aufgewendet wurde, um diese dem Kunden in Rechnung zu stellen.
 **Hinweis:** Wenn diese Anfrage mit einem Vertrag oder einer Berechtigung verbunden ist, wird die abzurechnende Zeit von den für diesen Vertrag zugewiesenen Minuten abgezogen.
1. Wählen Sie **Abschließen** aus. Eine Aktivität zum Abschluss von Anfragen wird erstellt und im Bereich **Aktivitäten** angezeigt. 

Die Aktivität zum Abschluss enthält Informationen zu einer gelösten Anfrage, einschließlich des Abschlusses und der Gesamtzeit, die für die Anfrage aufgewendet wurde. Sie können eine abgeschlossene Anfrage jederzeit reaktivieren.
