🌐 [DE](README.md) · [EN](README.en.md) · [IT](README.it.md) · [FR](README.fr.md) · [ES](README.es.md) · **NL** · [PL](README.pl.md) · [PT](README.pt.md) · [SV](README.sv.md) · [DA](README.da.md) · [CS](README.cs.md)

## Ambientika / Südwind GmbH

Open integraties voor Ambientika ventilatie-units — Home Assistant, MQTT, KNX en lokaal bedrijf.

| Repository | Doel |
|---|---|
| [ambientika-mqtt-bridge](https://github.com/ambientika-eu/ambientika-mqtt-bridge) | MQTT-bridge via de Ambientika-server — voor Home Assistant, ioBroker, openHAB, Loxone, Node-RED. **Aanbevolen voor de reguliere werking.** |
| [ambientika-ha-addon](https://github.com/ambientika-eu/ambientika-ha-addon) | Dezelfde bridge als add-on voor Home Assistant OS |
| [HomeAssistant-integration-for-Ambientika](https://github.com/ambientika-eu/HomeAssistant-integration-for-Ambientika) | Integratie “Ambientika for Home Assistant”, installatie via HACS |
| [ambientika-local-app](https://github.com/ambientika-eu/ambientika-local-app) | Eigen interface (PWA) in het thuisnetwerk. Optionele lokale modus: vervangt **de bridge** door een lokale die de units rechtstreeks aanspreekt. |
| [ambientika-local-standalone](https://github.com/ambientika-eu/ambientika-local-standalone) | Vervangt **de server**: de Ambientika-app draait ongewijzigd tegen een lokale dienst in het thuisnetwerk |
| [ambientika-rs485-boost-button](https://github.com/ambientika-eu/ambientika-rs485-boost-button) | Drukknopingang via RS485 voor ADVANCED+ / ADVANCED B+ |

De twee serverloze varianten verschillen in omvang: `local-app` vervangt alleen de datakoppeling van de eigen interface, `local-standalone` de server zelf. Beide zijn bedoeld als **terugvalniveau** — voor onderhoudsvensters, netwerkstoringen of gebouwen zonder permanente internetverbinding — en worden als gecontroleerde uitlevering geleverd. Voor de reguliere werking blijft de weg via de Ambientika-server de aanbevolen variant.

[ambientika.eu](https://www.ambientika.eu)
