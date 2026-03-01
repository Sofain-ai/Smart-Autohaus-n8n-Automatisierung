# Smart-Autohaus-n8n-Automatisierung
Automatisierte Verarbeitung von Fahrzeuganfragen für ein Smart-Autohaus mit E-Mail-Benachrichtigung und strukturierter Datenspeicherung in Google Sheets.




# Überblick

Dieser Workflow simuliert den digitalen Verkaufsprozess eines Autohauses.
Sobald ein Fahrzeug verkauft wird, werden die Verkaufsdaten über einen Webhook an n8n übermittelt.
Der Workflow versendet automatisch eine E-Mail und speichert die Verkaufsdaten im Google Sheet „Smart-Autohaus“.

Ziel ist die Reduzierung manueller Dokumentation und die automatische Erfassung von Verkaufsdaten.

**Workflow**

- Webhook → Gmail → Google Sheets

**Prozessablauf**

- Verkaufsdaten werden über einen Webhook gesendet
- Automatische E-Mail-Benachrichtigung über den Verkauf
- Speicherung der Daten im Google Sheet

**Beispiel-Daten**

{
  "name": "Max Schmidt",
  "preis": 24000,
  "modell": "Toyota Camry"
}




**Technische Umsetzung**

- Webhook als Trigger
- Gmail-Integration für E-Mail-Versand
- Google Sheets API für Datenspeicherung




**Setup**

- Workflow-JSON importieren
- Gmail-Credentials konfigurieren
- Google-Sheets-Credentials verbinden

**Webhook aktivieren**

- Hinweis:
API-Keys und Credentials sind nicht im Repository enthalten und müssen lokal in n8n eingerichtet werden.


![Workflow](docs/workflow.png)
