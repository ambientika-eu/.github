🌐 [DE](README.md) · [EN](README.en.md) · [IT](README.it.md) · **FR** · [ES](README.es.md) · [NL](README.nl.md) · [PL](README.pl.md) · [PT](README.pt.md) · [SV](README.sv.md) · [DA](README.da.md) · [CS](README.cs.md)

## Ambientika / Südwind GmbH

Intégrations ouvertes pour les appareils de ventilation Ambientika — Home Assistant, ioBroker, Matter, Homey, ESPHome, MQTT, KNX et fonctionnement local.

| Dépôt | Objet |
|---|---|
| [ambientika-mqtt-bridge](https://github.com/ambientika-eu/ambientika-mqtt-bridge) | Bridge MQTT via le serveur Ambientika — pour Home Assistant, ioBroker, openHAB, Loxone, Node-RED. **Recommandé pour l'exploitation courante.** |
| [ambientika-ha-addon](https://github.com/ambientika-eu/ambientika-ha-addon) | Le même bridge en add-on pour Home Assistant OS |
| [HomeAssistant-integration-for-Ambientika](https://github.com/ambientika-eu/HomeAssistant-integration-for-Ambientika) | Intégration « Ambientika for Home Assistant » — à trouver par la recherche dans HACS et dans le Marketplace de Home Assistant |
| [ioBroker.ambientika](https://github.com/ambientika-eu/ioBroker.ambientika) | Adaptateur pour ioBroker (via le serveur Ambientika) |
| [matterbridge-ambientika](https://github.com/ambientika-eu/matterbridge-ambientika) | Plugin pour Matterbridge — intègre les appareils via Matter dans Apple Home, Google Home, Amazon Alexa, SmartThings |
| [homey-ambientika](https://github.com/ambientika-eu/homey-ambientika) | Application pour Homey Pro (SMART, OFFICE) |
| [ESPHome-RS485-gateway-for-Ambientika](https://github.com/ambientika-eu/ESPHome-RS485-gateway-for-Ambientika) | Commande locale des ADVANCED+ / ADVANCED B+ via RS485 avec ESPHome (M5Stack Atom Lite), sans cloud |
| [ambientika-local-app](https://github.com/ambientika-eu/ambientika-local-app) | Interface propre (PWA) sur le réseau domestique. Mode local optionnel : remplace **le bridge** par un bridge local qui s'adresse directement aux appareils. |
| [ambientika-local-standalone](https://github.com/ambientika-eu/ambientika-local-standalone) | Remplace **le serveur** : l'application Ambientika fonctionne sans modification avec un service local sur le réseau domestique |
| [ambientika-rs485-boost-button](https://github.com/ambientika-eu/ambientika-rs485-boost-button) | Entrée bouton-poussoir via RS485 pour ADVANCED+ / ADVANCED B+ |

Les deux variantes sans serveur diffèrent par leur portée : `local-app` ne remplace que la liaison de données de sa propre interface, `local-standalone` le serveur lui-même. Toutes deux sont conçues comme **niveau de repli** — pour les fenêtres de maintenance, les pannes réseau ou les bâtiments sans connexion internet permanente — et sont livrées en version contrôlée. Pour l'exploitation courante, la voie passant par le serveur Ambientika reste la variante recommandée.

[ambientika.eu](https://www.ambientika.eu)
