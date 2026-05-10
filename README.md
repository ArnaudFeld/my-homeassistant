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

[![Import Blueprint](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https://raw.githubusercontent.com/ArnaudFeld/my-homeassistant/main/blueprints/notify_all_updates.yaml)

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
