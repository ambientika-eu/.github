🌐 **DE** · [EN](README.en.md) · [IT](README.it.md) · [FR](README.fr.md) · [ES](README.es.md) · [NL](README.nl.md) · [PL](README.pl.md) · [PT](README.pt.md) · [SV](README.sv.md) · [DA](README.da.md) · [CS](README.cs.md)

## Ambientika / Südwind GmbH

Offene Integrationen für Ambientika Lüftungsgeräte — Home Assistant, ioBroker, Matter, Homey, ESPHome, MQTT, KNX und lokaler Betrieb.

| Repository | Zweck |
|---|---|
| [ambientika-mqtt-bridge](https://github.com/ambientika-eu/ambientika-mqtt-bridge) | MQTT-Bridge über den Ambientika-Server — für Home Assistant, ioBroker, openHAB, Loxone, Node-RED. **Empfohlen für den Regelbetrieb.** |
| [ambientika-ha-addon](https://github.com/ambientika-eu/ambientika-ha-addon) | Dieselbe Bridge als Add-on für Home Assistant OS |
| [HomeAssistant-integration-for-Ambientika](https://github.com/ambientika-eu/HomeAssistant-integration-for-Ambientika) | Integration „Ambientika for Home Assistant“ — in HACS und im Marketplace von Home Assistant über die Suche zu finden |
| [ioBroker.ambientika](https://github.com/ambientika-eu/ioBroker.ambientika) | Adapter für ioBroker (über den Ambientika-Server) |
| [matterbridge-ambientika](https://github.com/ambientika-eu/matterbridge-ambientika) | Plugin für Matterbridge — bringt die Geräte über Matter zu Apple Home, Google Home, Amazon Alexa, SmartThings |
| [homey-ambientika](https://github.com/ambientika-eu/homey-ambientika) | App für Homey Pro (SMART, OFFICE) |
| [ESPHome-RS485-gateway-for-Ambientika](https://github.com/ambientika-eu/ESPHome-RS485-gateway-for-Ambientika) | Lokale Steuerung von ADVANCED+ / ADVANCED B+ über RS485 mit ESPHome (M5Stack Atom Lite), ohne Cloud |
| [ambientika-local-app](https://github.com/ambientika-eu/ambientika-local-app) | Eigene Oberfläche (PWA) im Heimnetz. Optionaler lokaler Betriebsmodus: ersetzt **die Bridge** durch eine lokale, die die Geräte direkt anspricht. |
| [ambientika-local-standalone](https://github.com/ambientika-eu/ambientika-local-standalone) | Ersetzt **den Server**: die Ambientika-App läuft unverändert gegen einen lokalen Dienst im Heimnetz |
| [ambientika-rs485-boost-button](https://github.com/ambientika-eu/ambientika-rs485-boost-button) | Tastereingang über RS485 für ADVANCED+ / ADVANCED B+ |

Die beiden serverlosen Fassungen unterscheiden sich im Umfang: `local-app` ersetzt nur die Datenanbindung der eigenen Oberfläche, `local-standalone` den Server selbst. Beide sind als **Rückfallebene** gedacht — für Wartungsfenster, Netzstörungen oder Objekte ohne dauerhafte Internetanbindung — und werden im Beobachtungsmodus ausgeliefert. Für den Regelbetrieb bleibt der Weg über den Ambientika-Server die empfohlene Variante.

[ambientika.eu](https://www.ambientika.eu)
