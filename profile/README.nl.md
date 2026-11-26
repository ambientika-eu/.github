🌐 [DE](README.md) · [EN](README.en.md) · [IT](README.it.md) · [FR](README.fr.md) · [ES](README.es.md) · **NL** · [PL](README.pl.md) · [PT](README.pt.md) · [SV](README.sv.md) · [DA](README.da.md) · [CS](README.cs.md)

## Ambientika / Südwind GmbH

Open integraties voor Ambientika ventilatie-units — Home Assistant, ioBroker, Matter, Homey, ESPHome, MQTT, KNX en lokaal bedrijf.

| Repository | Doel |
|---|---|
| [ambientika-mqtt-bridge](https://github.com/ambientika-eu/ambientika-mqtt-bridge) | MQTT-bridge via de Ambientika-server — voor Home Assistant, ioBroker, openHAB, Loxone, Node-RED. **Aanbevolen voor de reguliere werking.** |
| [ambientika-ha-addon](https://github.com/ambientika-eu/ambientika-ha-addon) | Dezelfde bridge als add-on voor Home Assistant OS |
| [HomeAssistant-integration-for-Ambientika](https://github.com/ambientika-eu/HomeAssistant-integration-for-Ambientika) | Integratie “Ambientika for Home Assistant” — te vinden via de zoekfunctie in HACS en in de Marketplace van Home Assistant |
| [ioBroker.ambientika](https://github.com/ambientika-eu/ioBroker.ambientika) | Adapter voor ioBroker (via de Ambientika-server) |
| [matterbridge-ambientika](https://github.com/ambientika-eu/matterbridge-ambientika) | Plugin voor Matterbridge — brengt de units via Matter naar Apple Home, Google Home, Amazon Alexa, SmartThings |
| [homey-ambientika](https://github.com/ambientika-eu/homey-ambientika) | App voor Homey Pro (SMART, OFFICE) |
| [ESPHome-RS485-gateway-for-Ambientika](https://github.com/ambientika-eu/ESPHome-RS485-gateway-for-Ambientika) | Lokale bediening van ADVANCED+ / ADVANCED B+ via RS485 met ESPHome (M5Stack Atom Lite), zonder cloud |
| [ambientika-local-app](https://github.com/ambientika-eu/ambientika-local-app) | Eigen interface (PWA) in het thuisnetwerk. Optionele lokale modus: vervangt **de bridge** door een lokale die de units rechtstreeks aanspreekt. |
| [ambientika-local-standalone](https://github.com/ambientika-eu/ambientika-local-standalone) | Vervangt **de server**: de Ambientika-app draait ongewijzigd tegen een lokale dienst in het thuisnetwerk |
| [ambientika-rs485-boost-button](https://github.com/ambientika-eu/ambientika-rs485-boost-button) | Drukknopingang via RS485 voor ADVANCED+ / ADVANCED B+ |

De twee serverloze varianten verschillen in omvang: `local-app` vervangt alleen de datakoppeling van de eigen interface, `local-standalone` de server zelf. Beide zijn bedoeld als **terugvalniveau** — voor onderhoudsvensters, netwerkstoringen of gebouwen zonder permanente internetverbinding — en worden als gecontroleerde uitlevering geleverd. Voor de reguliere werking blijft de weg via de Ambientika-server de aanbevolen variant.

[ambientika.eu](https://www.ambientika.eu)
