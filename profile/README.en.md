🌐 [DE](README.md) · **EN** · [IT](README.it.md) · [FR](README.fr.md) · [ES](README.es.md) · [NL](README.nl.md) · [PL](README.pl.md) · [PT](README.pt.md) · [SV](README.sv.md) · [DA](README.da.md) · [CS](README.cs.md)

## Ambientika / Südwind GmbH

Open integrations for Ambientika ventilation units — Home Assistant, ioBroker, Matter, Homey, ESPHome, MQTT, KNX and local operation.

| Repository | Purpose |
|---|---|
| [ambientika-mqtt-bridge](https://github.com/ambientika-eu/ambientika-mqtt-bridge) | MQTT bridge via the Ambientika server — for Home Assistant, ioBroker, openHAB, Loxone, Node-RED. **Recommended for regular operation.** |
| [ambientika-ha-addon](https://github.com/ambientika-eu/ambientika-ha-addon) | The same bridge as an add-on for Home Assistant OS |
| [HomeAssistant-integration-for-Ambientika](https://github.com/ambientika-eu/HomeAssistant-integration-for-Ambientika) | Integration “Ambientika for Home Assistant” — find it by searching in HACS and in the Home Assistant Marketplace |
| [ioBroker.ambientika](https://github.com/ambientika-eu/ioBroker.ambientika) | Adapter for ioBroker (via the Ambientika server) |
| [matterbridge-ambientika](https://github.com/ambientika-eu/matterbridge-ambientika) | Plugin for Matterbridge — brings the units via Matter to Apple Home, Google Home, Amazon Alexa, SmartThings |
| [homey-ambientika](https://github.com/ambientika-eu/homey-ambientika) | App for Homey Pro (SMART, OFFICE) |
| [ESPHome-RS485-gateway-for-Ambientika](https://github.com/ambientika-eu/ESPHome-RS485-gateway-for-Ambientika) | Local control of ADVANCED+ / ADVANCED B+ via RS485 with ESPHome (M5Stack Atom Lite), no cloud |
| [ambientika-local-app](https://github.com/ambientika-eu/ambientika-local-app) | Own interface (PWA) on the home network. Optional local operating mode: replaces **the bridge** with a local one that addresses the units directly. |
| [ambientika-local-standalone](https://github.com/ambientika-eu/ambientika-local-standalone) | Replaces **the server**: the Ambientika app runs unchanged against a local service on the home network |
| [ambientika-rs485-boost-button](https://github.com/ambientika-eu/ambientika-rs485-boost-button) | Push-button input via RS485 for ADVANCED+ / ADVANCED B+ |

The two server-free variants differ in scope: `local-app` replaces only the data link of its own interface, `local-standalone` the server itself. Both are intended as a **fallback** — for maintenance windows, network outages or buildings without a permanent internet connection — and are shipped as a controlled release. For regular operation, the route via the Ambientika server remains the recommended variant.

[ambientika.eu](https://www.ambientika.eu)
