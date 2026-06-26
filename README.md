# my-homeassistant

Eine Sammlung meiner Home Assistant Blueprints, Automationen und was noch so anfällt.

## 📦 Blueprints

### 🔔 Update-Benachrichtigungen
Benachrichtigung für alle verfügbaren HA-Updates per Push-Notification.

- Bis zu 3 Geräte (1 Pflicht, 2 optional)
- iOS & Android Support
- Backup vor Installation
- Erinnerungs-Intervall konfigurierbar
- Manueller Start möglich
- Benachrichtigung verschwindet nach Installation
- Integrations-Icon in Benachrichtigung ein-/ausblendbar

[![Import Blueprint](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https://raw.githubusercontent.com/ArnaudFeld/my-homeassistant/main/blueprints/notify_all_updates_de.yaml)

---

### 🔋 Batteriestand-Erkennung & Benachrichtigung
Regelmäßige Prüfung aller Batteriesensoren mit zweistufiger Warnung und automatischem Aufräumen der Notifications.

- Bis zu 3 Geräte (1 Pflicht, 2 optional)
- iOS & Android Support
- Zweistufige Warnung: normal & kritisch (mit konfigurierbarem `interruption-level`)
- Sensor-Zähler im Benachrichtigungstitel
- Persistente HA-Notification (wird automatisch gelöscht wenn alles OK ist)
- Push-Notifications werden nach Batteriewechsel automatisch entfernt
- Erinnerungs-Intervall konfigurierbar
- Zeitfenster & Wochentag konfigurierbar
- Sensoren ausschließbar (z.B. Smartphones)

[![Import Blueprint](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https://raw.githubusercontent.com/ArnaudFeld/my-homeassistant/main/blueprints/batterie_warnung_de.yaml)

---

### ⚽ TeamTracker Spiel-Benachrichtigungen
Push-Benachrichtigungen für ein per TeamTracker-Integration getracktes Fußball-Team.

- Bis zu 3 Geräte (1 Pflicht, 2 optional)
- Anstoß-Erinnerung mit konfigurierbarer Vorlaufzeit
- Benachrichtigung bei Spielbeginn
- Halbzeitstand
- Tore (eigene & Gegentore), jeweils mit Einordnung (Führung übernommen / Ausgleich / Vorsprung ausgebaut / verkürzt)
- Endstand inkl. Sieg / Niederlage / Unentschieden
- Alle Benachrichtigungstypen einzeln ein-/ausschaltbar

[![Import Blueprint](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https://raw.githubusercontent.com/ArnaudFeld/my-homeassistant/main/blueprints/teamtracker_push_de.yaml)

---

---

A collection of my Home Assistant blueprints, automations, and whatever else comes up.

## 📦 Blueprints

### 🔔 Update Notifications
Push notification for all available HA updates.

- Up to 3 devices (1 required, 2 optional)
- iOS & Android support
- Backup before installation
- Configurable reminder interval
- Manual trigger possible
- Notification clears after installation
- Integration icon in notification can be toggled

[![Import Blueprint](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https://raw.githubusercontent.com/ArnaudFeld/my-homeassistant/main/blueprints/notify_all_updates_en.yaml)

---

### 🔋 Battery Level Detection & Notification
Regular check of all battery sensors with two-level warnings and automatic notification cleanup.

- Up to 3 devices (1 required, 2 optional)
- iOS & Android support
- Two-level warnings: normal & critical (with configurable `interruption-level`)
- Sensor count in notification title
- Persistent HA notification (automatically dismissed when all batteries are OK)
- Push notifications automatically cleared after battery replacement
- Configurable reminder interval
- Configurable time window & day of week
- Sensors can be excluded (e.g. smartphones)

[![Import Blueprint](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https://raw.githubusercontent.com/ArnaudFeld/my-homeassistant/main/blueprints/batterie_warnung_en.yaml)

---

### ⚽ TeamTracker Game Notifications
Push notifications for a soccer team tracked via the TeamTracker integration.

- Up to 3 devices (1 required, 2 optional)
- Kickoff reminder with configurable lead time
- Notification when the game starts
- Halftime score
- Goals (yours & opponent's), each labeled (took the lead / equalized / extended the lead / reduced the gap)
- Final score including win / loss / draw
- All notification types can be toggled individually

[![Import Blueprint](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https://raw.githubusercontent.com/ArnaudFeld/my-homeassistant/main/blueprints/teamtracker_push_en.yaml)