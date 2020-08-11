---
lab:
    title: 'Lab 01: Funktionen von Dynamics 365 Sales entdecken'
    module: 'Modul 03: Einführung in Dynamics 365 Sales'
---

# MB-901: Dynamics 365 Sales
## Modul 3, Lab 1 – Funktionen von Dynamics 365 Sales entdecken

**Voraussetzungen:** Führen Sie die folgenden Aufgaben aus, bevor Sie die Schritte dieses Labs ausführen:

1. Erstellen und speichern Sie ein Word-Dokument mit einem Beispieltext (z. B. „Leitfaden für Dynamics 365 Sales“) auf Ihrem Desktop.
1. Aktivieren Sie die Erfahrung **E-Mail verbessern** in den Sales Hub App-Einstellungen. Mit dieser Funktion kann das E-Mail-Verfassenfenster in einem Popup-Fenster geöffnet werden, wenn Sie eine neue E-Mail in der Sektion **Zeitleiste** erstellen.
1. Aktualisieren Sie Ihren Browser.

**Optional:**
 
1. Wechseln Sie in der Dynamics 365-Instanz zu „Einstellungen“, und klicken Sie auf „Datenverwaltung“.
1. Wählen Sie „Beispieldaten“ aus.
1. Wenn die Beispieldaten nicht installiert sind, wählen Sie **Beispieldaten installieren** aus. Es kann einige Minuten dauern, bis die Beispieldaten angezeigt werden. Sie können die Anwendung jedoch während der Installation weiter verwenden.
1. Wählen Sie **Schließen** aus.

### Neuen Kontakt erstellen

1. Navigieren Sie im **Dynamics 365 Sales Hub** zu **Kunden** > , und klicken Sie auf **Kontakte**.
1. Klicken Sie auf **Neu**.
1. Geben Sie im Feld **Vorname** den Namen **Cameron** ein.
1. Geben Sie im Feld **Nachname** den Text **Azadi** ein.
1. Geben Sie dann im Feld **Position** die Bezeichnung **Xbox X-Series-Entwicklungsmanager** ein.
1. Tragen Sie in das Feld **Telefon (geschäftlich)** die Nummer **949-555-1212** ein.
1. Geben Sie in das Feld **Adresse 1: **Feld **Straße 1**, **1 Microsoft Way** eintragen.
1. Geben Sie in das Feld **Adresse 1: Stadt** den Text **Redmond** ein.
    - **Hinweis:** Wenn Demo-Daten hochgeladen wurden, wird das Formular **Adressvorschläge** angezeigt. Klicken Sie auf **OK**. Die Felder **Adresse 1** werden automatisch ausgefüllt. 
1. Geben Sie in das Feld **Adresse 1: Bundesland/Kanton** den Text **WA** ein.
1. Geben Sie in das Feld **Adresse 1: **im Feld **Postleitzahl** die Postleitzahl **98007** ein.
1. Geben Sie in das Feld **Adresse 1: Land/Region** das Land **USA** ein.
1. Geben Sie in das Feld **E-Mail** Ihren E-Mail-Alias ein.
1. Klicken Sie auf **Speichern**.

### Einen neuen Lead erstellen

1. Navigieren Sie im **Dynamics 365 Sales Hub** zu **Vertrieb** > **Leads**.
1. Klicken Sie auf **Neu**.
1. Klicken Sie auf das Symbol **Qualifizierungsphase**.
1. Wählen/Geben Sie im Feld **Vorhandener Kontakt?**  den Namen **Cameron Azadi** aus/ein.
- **Hinweis:** Wenn Sie beim Erstellen eines Lead-Datensatzes einen vorhandenen Kontakt auswählen, werden Vorname, Nachname, Jobtitel, Telefon (geschäftlich), Mobiltelefon und E-Mail automatisch im Lead-Formular ausgefüllt. Wenn Sie ein vorhandenes Konto auswählen, wird der Unternehmensname automatisch in das Lead-Formular eingetragen. Dies macht es sehr schnell und einfach, einen Lead-Datensatz einzugeben.
1. Geben Sie in das Feld **Thema** den Text **Mag unsere Xbox-Produkte** ein.
1. Klicken Sie auf **Speichern**.

### Systemeinstellungen ändern

1. Navigieren Sie im Menü oben rechts zum Zahnradsymbol **Einstellungen**. Verwenden Sie die Dropdownliste, um **Erweiterte Einstellungen** auszuwählen.
1. Klicken Sie auf die Dropdownliste neben **Einstellungen** und navigieren Sie unter **Systemeinstellungen** zu **Verwaltung.**
1. Wählen Sie die Registerkarte **Vertrieb** aus.
1. Klicken Sie im Feld **Lead-Erfahrung qualifizieren** auf **Nein**.
1. Klicken Sie auf **OK**.

### Den neuen Lead qualifizieren

1. Navigieren Sie im **Dynamics 365 Sales Hub**zu **Verkäufe** > **Leads**.
1. Wählen Sie **Cameron Azadi** aus.
1. Klicken Sie auf die Schaltfläche **Qualifizieren**.
1. Klicken Sie im Formular **Lead qualifizieren** auf **OK**. Dies ändert den Wert von **Ja** in **Nein**.
1. Klicken Sie im Formular **Lead qualifizieren** auf **Chance**. Dies ändert den Wert von **Nein** zu **Ja**.
1. Klicken Sie im Formular **Lead qualifizieren** auf **OK**. 
**Hinweis:** Der Lead geht in die Ausbauphase über.

### Einem neuen Lead Notizen hinzufügen

1. Klicken Sie im Abschnitt **Zeitplanung** auf **+**, um eine neue **Notiz** hinzufügen.
1. Geben Sie im Feld **Titel** **Besprechung mit Cameron bezüglich der Xbox X-Serie** ein.
1. Klicken Sie auf **Notiz hinzufügen**.
1. Klicken Sie im Abschnitt **Zeitachse** auf **+**, um eine weitere **Notiz** mit Anlage hinzuzufügen.
1. Geben Sie im Feld **Titel** **Produktinformationen zur Xbox X-Serie** ein.
1. Klicken Sie auf das Anlagesymbol, und wählen Sie das Word-Dokument aus, das Sie zu Beginn dieses Labs erstellt haben.
1. Klicken Sie auf **Notiz hinzufügen**.

### Überprüfen Sie die Notizen, die im Lead unter „Verkaufschancen“ erstellt wurden.

1. Navigieren Sie in **Dynamics 365 Sales Hub** zu **Verkäufe** > **Chancen**.
1. Wechseln Sie die Ansicht, indem Sie auf das Dropdownmenü klicken und **Alle Chancen** auswählen.
1. Klicken Sie hier, um die Chance **Mag unsere Xbox-Produkte für Cameron Azadi** auszuwählen.
1. Beachten Sie, dass die im Lead-Formular erstellte Anlage und die Notizen auch im Chancen-Formular verfügbar sind. 
1. Klicken Sie im Abschnitt**Zeitleiste** auf **+**, um eine **E-Mail** zu entwerfen und zu senden. Das E-Mail-Popup wird angezeigt.
1. Geben Sie im Feld **Betreff** **Xbox X-Series** ein.
1. Geben Sie eine Nachricht ein, z. B. „Hallo Cameron, vielen Dank für dein Interesse an der Xbox X-Series. Wir freuen uns auf unser Treffen.“ 
1. Optional können Sie aus dem Chancen-Datensatz oder den zugehörigen Datensätzen, z. B. durch Navigieren zum Kontaktdatensatz, im Hintergrund alle Informationen kopieren und in die E-Mail-Nachricht einfügen, ohne den Fokus zu verlieren und trotzdem Zeit zu sparen.
1. Klicken Sie auf **Speichern**.




