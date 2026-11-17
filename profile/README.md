🌐 **DE** · [EN](README.en.md) · [IT](README.it.md) · [FR](README.fr.md) · [ES](README.es.md) · [NL](README.nl.md) · [PL](README.pl.md) · [PT](README.pt.md) · [SV](README.sv.md) · [DA](README.da.md) · [CS](README.cs.md)

## Ambientika / Südwind GmbH

Offene Integrationen für Ambientika Lüftungsgeräte — Home Assistant, MQTT, KNX und lokaler Betrieb.

| Repository | Zweck |
|---|---|
| [ambientika-mqtt-bridge](https://github.com/ambientika-eu/ambientika-mqtt-bridge) | MQTT-Bridge über den Ambientika-Server — für Home Assistant, ioBroker, openHAB, Loxone, Node-RED. **Empfohlen für den Regelbetrieb.** |
| [ambientika-ha-addon](https://github.com/ambientika-eu/ambientika-ha-addon) | Dieselbe Bridge als Add-on für Home Assistant OS |
| [HomeAssistant-integration-for-Ambientika](https://github.com/ambientika-eu/HomeAssistant-integration-for-Ambientika) | Integration „Ambientika for Home Assistant“, Installation über HACS |
| [ambientika-local-app](https://github.com/ambientika-eu/ambientika-local-app) | Eigene Oberfläche (PWA) im Heimnetz. Optionaler lokaler Betriebsmodus: ersetzt **die Bridge** durch eine lokale, die die Geräte direkt anspricht. |
| [ambientika-local-standalone](https://github.com/ambientika-eu/ambientika-local-standalone) | Ersetzt **den Server**: die Ambientika-App läuft unverändert gegen einen lokalen Dienst im Heimnetz |
| [ambientika-rs485-boost-button](https://github.com/ambientika-eu/ambientika-rs485-boost-button) | Tastereingang über RS485 für ADVANCED+ / ADVANCED B+ |

Die beiden serverlosen Fassungen unterscheiden sich im Umfang: `local-app` ersetzt nur die Datenanbindung der eigenen Oberfläche, `local-standalone` den Server selbst. Beide sind als **Rückfallebene** gedacht — für Wartungsfenster, Netzstörungen oder Objekte ohne dauerhafte Internetanbindung — und werden im Beobachtungsmodus ausgeliefert. Für den Regelbetrieb bleibt der Weg über den Ambientika-Server die empfohlene Variante.

[ambientika.eu](https://www.ambientika.eu)
