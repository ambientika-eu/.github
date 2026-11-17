🌐 [DE](README.md) · [EN](README.en.md) · [IT](README.it.md) · **FR** · [ES](README.es.md) · [NL](README.nl.md) · [PL](README.pl.md) · [PT](README.pt.md) · [SV](README.sv.md) · [DA](README.da.md) · [CS](README.cs.md)

## Ambientika / Südwind GmbH

Intégrations ouvertes pour les appareils de ventilation Ambientika — Home Assistant, MQTT, KNX et fonctionnement local.

| Dépôt | Objet |
|---|---|
| [ambientika-mqtt-bridge](https://github.com/ambientika-eu/ambientika-mqtt-bridge) | Bridge MQTT via le serveur Ambientika — pour Home Assistant, ioBroker, openHAB, Loxone, Node-RED. **Recommandé pour l'exploitation courante.** |
| [ambientika-ha-addon](https://github.com/ambientika-eu/ambientika-ha-addon) | Le même bridge en add-on pour Home Assistant OS |
| [HomeAssistant-integration-for-Ambientika](https://github.com/ambientika-eu/HomeAssistant-integration-for-Ambientika) | Intégration « Ambientika for Home Assistant », installation via HACS |
| [ambientika-local-app](https://github.com/ambientika-eu/ambientika-local-app) | Interface propre (PWA) sur le réseau domestique. Mode local optionnel : remplace **le bridge** par un bridge local qui s'adresse directement aux appareils. |
| [ambientika-local-standalone](https://github.com/ambientika-eu/ambientika-local-standalone) | Remplace **le serveur** : l'application Ambientika fonctionne sans modification avec un service local sur le réseau domestique |
| [ambientika-rs485-boost-button](https://github.com/ambientika-eu/ambientika-rs485-boost-button) | Entrée bouton-poussoir via RS485 pour ADVANCED+ / ADVANCED B+ |

Les deux variantes sans serveur diffèrent par leur portée : `local-app` ne remplace que la liaison de données de sa propre interface, `local-standalone` le serveur lui-même. Toutes deux sont conçues comme **niveau de repli** — pour les fenêtres de maintenance, les pannes réseau ou les bâtiments sans connexion internet permanente — et sont livrées en version contrôlée. Pour l'exploitation courante, la voie passant par le serveur Ambientika reste la variante recommandée.

[ambientika.eu](https://www.ambientika.eu)
