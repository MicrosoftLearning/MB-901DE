---
lab:
    title: 'Lab 01: Erstellen Sie Ihre erste modellgesteuerte App von Grund auf neu'
    module: 'Module 13: Verbinden und analysieren Sie Ihre Dynamics 365-Daten'
---

# MB-901: Grundlagen von Dynamics 365
## Modul 13, Lab 1: Erstellen Sie Ihre erste modellgesteuerte App von Grund auf neu

**Szenario:** Sie müssen die Erstellung einer modellgesteuerten App mithilfe einer der Standardentitäten vereinfachen, die in Ihrer Power Apps-Umgebung verfügbar sind. Modellgesteuerte Apps werden nicht in der mobilen Power Apps-App ausgeführt. Stattdessen führen Sie eine modellgesteuerte App auf einem mobilen Gerät entweder über die Dynamics 365 Mobile-App oder im Webbrowser des Smartphones aus.

Melden Sie sich mit Ihrer Windows-Live-ID bei Power Apps an. Wenn Sie noch nicht über ein Power Apps-Konto verfügen, wählen Sie den kostenlosen Link „Erste Schritte“ aus unter https://signup.microsoft.com/Start?sku=powerapps_viral&ru=https%3a%2f%2fweb.powerapps.com%2flogin%2fportal

## Anweisungen
1. Greifen Sie auf das Power Platform Admin Center zu.
12.	Klicken Sie auf **Umgebungen**.
13.	Klicken Sie auf Ihre Test-CRM-Umgebung. 
14.	Klicken Sie auf den Hyperlink ![Dynamics 365 Admin Center](https://port.crm.dynamics.com/G/Instances/InstancePicker.aspx?redirect=False0).
15.	Wählen Sie **GTLPowerApps** aus.
16.	Klicken Sie auf **Öffnen**.
17.	Klicken Sie auf **Neue App erstellen**.
19.	Auf der Seite **Eine neue App erstellen** geben Sie die folgenden Details ein und klicken Sie dann **Fertig**:
    - **Name:** Geben Sie **GuideToPowerApp** ein.
    - **Eindeutiger Name:** Standardmäßig verwendet der eindeutige Name den Namen, den Sie im Feld „Name“ ohne Leerzeichen angegeben haben und dem das Herausgeberpräfix und ein Unterstrich (_) vorangestellt sind.
    - **Beschreibung:** Geben Sie **GuideToPowerApp** ein.
20.	Klicken Sie auf **Fertig**.
21.	Über den App-Designer fügen Sie Ihrer App Komponenten hinzu. Wählen Sie das Bleistift-Symbol auf der Schaltfläche **Siteübersicht** aus, um den Siteübersichts-Designer zu öffnen.
22.	In dieser Power-App verwenden Sie die Entität „Konten“, um Debitorenkonten zu verwalten.
22. Geben Sie auf der Registerkarte **Eigenschaften** als Bereichsname **Konten** ein.
23.	Wählen Sie im Siteübersichts-Designer **Neuer Unterbereich** aus, wählen Sie dann im rechten Bereich die Registerkarte **Eigenschaften** aus und wählen Sie anschließend den Wert der folgenden Eigenschaften:
    - **Typ: Entität**
    - **Entität: Firma**  
    - Klicken Sie auf **Speichern.** 
24.	Klicken Sie auf **App-Designer**.
25.	Wählen Sie auf der App-Designer-Canvas **Formulare** aus und dann im rechten Bereich unter der Gruppe **Hauptformulare** wählen Sie das Formular **Konto** aus.
26.	Klicken Sie auf die Schaltfläche **Zurück**.
27.	Wählen Sie auf der App-Designers-Canvas **Ansichten** aus und wählen Sie dann die Ansichten **Aktive Konten**, **Alle Konten** und **Meine aktiven Konten** aus.
28.	Klicken Sie auf die Schaltfläche **Zurück**.
29.	Wählen Sie auf der App-Designer-Canvas **Diagramme** aus und wählen Sie dann das **Diagramm „Konten nach Branchen“** aus.
30.	Klicken Sie auf die Schaltfläche **Zurück**.
31.	Klicken Sie in der Symbolleiste des App-Designers auf **Speichern** und dann auf **Veröffentlichen**.
32.	Klicken Sie auf **Wiedergeben**.
34.	Überprüfen Sie die Ergebnisse und interagieren Sie mit Ihrer ersten modellgesteuerten Anwendung.
35.	Probieren Sie es auf Ihrem mobilen Gerät aus, indem Sie die App „Dynamics 365 für Smartphones“ oder „Dynamics 365 für Tablets“ über den App Store Ihres Geräts installieren. Weitere Informationen: https://docs.microsoft.com/dynamics365/customer-engagement/mobile-app/install-dynamics-365-for-phones-and-tablets
36.	Geben Sie die URL der Anwendung direkt in den Webbrowser Ihres Smartphones ein und folgen Sie den Anweisungen auf dem Bildschirm, um die App zu laden. 
  **Hinweis:** Ein Beispiel Ihrer Anwendungs-URL sieht folgendermaßen aus: https://orgxxxxx.crm.dynamics.com/main.aspx?appid=e4547538-e20f-ea01-a811-000d3a33438d&pagetype=entitylist&etn=account
