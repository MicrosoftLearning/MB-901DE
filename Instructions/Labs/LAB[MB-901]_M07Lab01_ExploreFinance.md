---
lab:
    title: 'Lab 01: Dynamics 365 Finance erkunden'
    module: 'Modul 07: Einführung in Dynamics 365 Finance'
---

# MB-901: Grundlagen von Dynamics 365 
## Modul 7, Lab 1 – Dynamics 365 Finance erkunden 


**Voraussetzungen**: Führen Sie vor dem Ausführen der Schritte dieses Lab die folgenden
 Aufgaben aus: 

**Hinweis:** Sie benötigen vor der Ausführung dieses Labs eine bereitgestellte Umgebung
mit Demodaten. Ihre Dynamics 365 Finance and Operations-Apps-Instanz kann
entweder von LCS gestartet werden, oder indem Sie direkt zur URL der Instanz wechseln.

Sie müssen das Unternehmen ändern auf **USMF.** Um sich bei der Instanz der Dynamics 365 Finance and Operations-Apps anzumelden, müssen Sie einen Benutzernamen und ein Kennwort mit der Sicherheitsrolle **Geschäftsführer** oder **Systemadministrator** besitzen.

Wenn Ihre Umgebung keine Demo-Daten enthält, befolgen Sie die Anweisungen.
Anweisungen:

Navigieren Sie zu **Module > Demo-Daten**, und klicken Sie auf **Daten generieren**. Klicken Sie dann auf
    **Sie auf „Ok“.**

### Importieren von Wechselkursen

1.  Ändern Sie das Unternehmen in **USMF.**

2.  Wechseln Sie zu **Hauptbuch > Währungen > Wechselkurstypen**.

3.  Klicken Sie auf **Neu**.

4.  Geben Sie im Feld **Wechselkurstyp** „GTL-EXCH“ ein.

5.  Geben Sie im Feld **Name** „Seahorse Exchange Rate“ ein.

6.  Klicken Sie auf **Wechselkurse**.

7.  Beachten Sie, dass keine Wechselkurse verfügbar sind.

8.  Schließen Sie das Formular „Wechselkurse“.

9.  Schließen Sie das Formular für Wechselkurstypen

10. Wechseln Sie zu **Hauptbuch > Währungen > Wechselkursanbieter konfigurieren**.

11. Klicken Sie auf **Neu**.

12. Wählen Sie **Zentralbank der Russischen Föderation** aus

13. Klicken Sie auf **OK**.

14. Schließen Sie die Seite.

15. Wechseln Sie zu **Hauptbuch > Währungen > Währungswechselkurse importieren**.

16. Geben Sie im Feld **Wechselkurstyp** „GTL-EXCH“ ein, oder wählen Sie dies aus.

17. Wählen Sie **Zentralbank der Russischen Föderation** aus

18. Geben Sie im Feld **Wechselkursanbieter** „Zentralbank der Russischen Föderation“, ein
    die Russische Föderation**

19. Klicken Sie auf **OK**.

20. Wechseln Sie zu **Hauptbuch > Währungen > Wechselkurstypen**.

21. Wählen Sie **GTL-EXCH** aus.

22. Klicken Sie auf **Wechselkurse**.

23. Beachten Sie die importierten Werte

24. Schließen Sie alle Formulare

### Eine Bestellung erstellen, einen Produktzugang buchen

1.  Wechseln Sie zu **Kreditorenkonten > Bestellungen > Alle Bestellungen**.

2.  Klicken Sie auf **Neu**.

3.  Wählen Sie im Feld **Anbieterkonto** den Eintrag **1001 Acme Office Supplies** aus.

4.  Wählen Sie im Feld **Lagerort** den Wert **11** aus.

5.  Klicken Sie auf **OK**.

6.  Wählen Sie im Feld **Artikelnummer** den Artikel **1000 Surface Pro 128 GB** aus.

7.  Klicken Sie im Aktionsbereich auf **Kaufen**.

8.  Klicken Sie auf **Bestätigen**.

9.  Klicken Sie im Aktionsbereich auf **Empfangen**.

10. Klicken Sie auf **Produktzugang**.

11. Geben Sie im Feld **Produktzugang** die Zeichenfolge **GTL02020** ein.

12. Klicken Sie auf **OK**.

13. Schließen Sie alle Formulare.

### Eine Freitextrechnung erstellen

1.  Wechseln Sie zu **Debitoren > Rechnungen > Alle Freitextrechnungen**.

2.  Wählen Sie **Neu** aus.

3.  Wählen Sie im Feld **Kundenkonto** den Eintrag **US-003** aus.

4.  Geben Sie im Feld **Beschreibung** **Anleitung zur Freitextrechnung** ein.
     Klicken Sie im Dialogfeld auf **Ja**.

5.  Wählen Sie im Feld **Hauptkonto** die Kontonummer **110180** aus.

6.  Geben Sie im Feld **Menge** den Wert **17** ein.

7.  Geben Sie in das Feld **Preis je Einheit** den Wert **817,00** ein. Der Betrag wird wie folgt berechnet:
    Menge multipliziert mit dem Preis pro Einheit. Sie können diese Berechnung jedoch außer Kraft setzen,
    indem Sie einen Betrag eingeben.

8.  Wählen Sie **Gebühren** aus, um der Rechnung eine Gebühr hinzuzufügen.

9.  Geben Sie im Feld **Gebührencode** als Name **Fracht** ein.

10. Geben Sie im Feld **Gebührenwert** **150** ein.

11. Schließen Sie die Seite.

12. Wählen Sie **Summen** aus, um eine Zusammenfassung der Rechnungsdetails und Summen anzuzeigen.

13. Wählen Sie **Schließen** aus.

14. Klicken Sie auf **Buchen**, um die Rechnung zu buchen. Sie haben immer noch die Möglichkeit zu
    stornieren, bevor Sie tatsächlich buchen.

    -  Sie können den Zeitpunkt, zu dem Rechnungen gedruckt werden sollen, ändern. Wählen Sie **Aktuell** aus, um
        jede Rechnung zu drucken, wenn diese aktualisiert wird. Wählen Sie **Nach**, um zu drucken, nachdem alle
        Rechnungen aktualisiert wurden.

    -  Um zu ändern, wie das Kreditlimit des Kunden überprüft wird, bevor die Rechnung
        gebucht wird, ändern Sie den Wert im Feld **Kreditlimittyp**.

    -  Um die Rechnung zu drucken, setzen Sie die Option auf **Ja**.

    -  Um die Rechnung zu buchen, setzen Sie die Option auf **Ja**. Sie können die Rechnung
        drucken, ohne sie zu buchen.

15. Klicken Sie auf **OK**.
