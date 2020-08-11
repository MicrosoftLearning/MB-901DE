---
lab:
    title: 'Lab 02: Sicherheitsrollen in Dynamics 365 Finance and Operations-Apps untersuchen'
    module: 'Modul 03: Informationen zur Sicherheit in Dynamics 365'
---

# MB-901: Grundlagen von Dynamics 365
## Modul 3, Lab 2 – Sicherheitsrollen in Dynamics 365 Finance and Operations-Apps untersuchen

### Rolle ausschließen

**Szenario:** Die Personalabteilung von USMF hat beantragt, einem Mitarbeiter, der die Rolle gewechselt hat, die Zugriffsrechte der Rolle des Debitorenbuchhalters in den Finance and Operations-Apps von Dynamics 365 zu entziehen. Als Systemadministrator müssen Sie die Rolle des Debitorenbuchhalters für den Mitarbeiter ausschließen.

1. Navigieren Sie zu **Systemverwaltung** > **Sicherheit** > **Benutzer zu Rollen zuweisen**.
1. Wählen Sie in der Struktur den Knoten **Debitorenbuchhalter** aus.
1. Klicken Sie auf **Benutzer manuell zuweisen**/**ausschließen**.
1. Wählen Sie einen Benutzer aus der Liste aus.
1. Wählen Sie die Option **Von Rolle ausschließen** aus, um die ausgewählten Benutzer von der Rolle auszuschließen.
1. Markieren Sie zum Entfernen von Ausnahmen die Benutzer, für die Sie die Ausnahmen entfernen möchten. Wählen Sie anschließend **Status zurücksetzen** aus. 

### Regel zur Aufgabentrennung erstellen

**Szenario:** Die Personalabteilung der USMF hat eine Regelung zur Aufgabentrennung für **Zugriff auf Arbeitsbereich Vergütung** (erste Aufgabe) und **Produktionserfassung genehmigen** (zweite Aufgabe) beantragt. Als Systemadministrator müssen Sie die Regel erstellen.

1. Wechseln Sie zu **Systemverwaltung** > **Sicherheit** > **Aufgabentrennung** > **Aufgabentrennungsregeln**.
1. Klicken Sie auf **Neu**.
1. Geben Sie im Feld **Name** einen Namen für die Regel ein.
1. Klicken Sie im Feld **Erste Aufgabe** auf die Dropdown-Schaltfläche, um die Suche zu öffnen.
1. Suchen Sie in der Liste die erste Aufgabe, die von der Regel gesteuert wird, und wählen Sie diese aus.
1. Klicken Sie in der Liste auf den Link in der ausgewählten Zeile.
1. Wählen Sie im Feld **Zweite Aufgabe** die Dropdown-Schaltfläche aus, um die Suche zu öffnen.
1. Suchen Sie in der Liste die zweite Aufgabe, die von der Regel gesteuert wird, und wählen Sie diese aus.
1. Klicken Sie in der Liste auf den Link in der ausgewählten Zeile.
1. Wählen Sie im Feld **Schweregrad** den Schweregrad des Risikos aus, das auftritt, wenn derselbe Benutzer oder dieselbe Rolle beide Aufgaben ausführt.
1. Geben Sie im Feld **Sicherheitsrisiko** eine Beschreibung des Sicherheitsrisikos ein.
1. Geben Sie im Feld **Sicherheitsausgleich** einen Wert ein.
1. Geben Sie eine Beschreibung der Maßnahmen ein, die Sie ergreifen, um das Sicherheitsrisiko zu begrenzen. 
Sie können das Risiko beispielsweise durch detailliertere Überprüfungen des Prozesses, durch eine monatliche Überprüfung durch das Management oder durch die gemeinsame Nutzung von Ressourcen mit anderen Abteilungen verringern.
1. Klicken Sie auf **Speichern**.
