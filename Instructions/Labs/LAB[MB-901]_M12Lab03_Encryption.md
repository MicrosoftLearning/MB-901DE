---
lab:
    title: 'Lab 03: Erhöhen Sie die Sicherheit, indem Sie Ihre Daten verschlüsseln'
    module: 'Modul 12: Anerkennen von Sicherheit in Dynamics 365'
---

# MB-901: Grundlagen von Dynamics 365
## Modul 12, Lab 3: Erhöhen Sie die Sicherheit, indem Sie Ihre Daten verschlüsseln

**Szenario:** Als Systemadministrator müssen Sie den Organisationsverschlüsselungsschlüssel ändern und kopieren.

## Anweisungen

1. Navigieren Sie zum Power Platform Admin Center.  
1. Diese Einstellungen finden Sie in **Umgebungen** > [Umgebung auswählen]> **Einstellungen** > **Verschlüsselung** > **Datenverschlüsselung**.
1. Geben Sie im Feld **Verschlüsselungsschlüssel ändern** den neuen Verschlüsselungsschlüssel ein, und wählen Sie dann **Ändern** aus.
1. Wählen Sie in der Bestätigungsnachricht **OK** und wählen Sie dann **Schließen**, um die Seite **Datenverschlüsselung** zu verlassen.

Wir empfehlen dringend, dass Sie eine Kopie Ihres Datenverschlüsselungsschlüssels erstellen.

1. Wählen Sie dieselbe Umgebung aus, die Sie in den Schritten 1 bis 4 verwendet haben, und wechseln Sie zu **Einstellungen** > **Verschlüsselung**.
1. Wählen Sie im Dialogfeld **Datenverschlüsselung** **Schlüssel anzeigen** aus, und wählen Sie im Feld **Aktueller Schlüssel** den Schlüssel aus, und kopieren Sie ihn in die Zwischenablage.
1. Fügen Sie den Verschlüsselungsschlüssel in einen Text-Editor ein (z. B. in Notepad).

**Hinweis:** Standardmäßig generieren modellgesteuerte Apps in Dynamics 365 eine Passphrase, die eine zufällige Anordnung von Unicode-Zeichen ist. Daher müssen Sie die vom System generierte Passphrase mithilfe einer Anwendung und einer Datei speichern, die Unicode-Zeichen unterstützt. Einige Text-Editoren, wie z. B. Editor, verwenden standardmäßig die ANSI-Codierung. Bevor Sie die Passphrase mit Notepad speichern, wählen Sie „Speichern unter“ und anschließend in der Liste „Codierung“ die Option „Unicode“.

Speichern Sie als bewährte Methode die Textdatei, die den Verschlüsselungsschlüssel enthält, auf einem Computer an einem sicheren Ort auf einer verschlüsselten Festplatte.
