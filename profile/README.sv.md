🌐 [DE](README.md) · [EN](README.en.md) · [IT](README.it.md) · [FR](README.fr.md) · [ES](README.es.md) · [NL](README.nl.md) · [PL](README.pl.md) · [PT](README.pt.md) · **SV** · [DA](README.da.md) · [CS](README.cs.md)

## Ambientika / Südwind GmbH

Öppna integrationer för Ambientika ventilationsaggregat — Home Assistant, ioBroker, Matter, Homey, ESPHome, MQTT, KNX och lokal drift.

| Repository | Syfte |
|---|---|
| [ambientika-mqtt-bridge](https://github.com/ambientika-eu/ambientika-mqtt-bridge) | MQTT-brygga via Ambientika-servern — för Home Assistant, ioBroker, openHAB, Loxone, Node-RED. **Rekommenderas för normal drift.** |
| [ambientika-ha-addon](https://github.com/ambientika-eu/ambientika-ha-addon) | Samma brygga som tillägg för Home Assistant OS |
| [HomeAssistant-integration-for-Ambientika](https://github.com/ambientika-eu/HomeAssistant-integration-for-Ambientika) | Integrationen ”Ambientika for Home Assistant” — hittas via sökningen i HACS och i Home Assistants Marketplace |
| [ioBroker.ambientika](https://github.com/ambientika-eu/ioBroker.ambientika) | Adapter för ioBroker (via Ambientika-servern) |
| [matterbridge-ambientika](https://github.com/ambientika-eu/matterbridge-ambientika) | Plugin för Matterbridge — gör aggregaten tillgängliga via Matter i Apple Home, Google Home, Amazon Alexa, SmartThings |
| [homey-ambientika](https://github.com/ambientika-eu/homey-ambientika) | App för Homey Pro (SMART, OFFICE) |
| [ESPHome-RS485-gateway-for-Ambientika](https://github.com/ambientika-eu/ESPHome-RS485-gateway-for-Ambientika) | Lokal styrning av ADVANCED+ / ADVANCED B+ via RS485 med ESPHome (M5Stack Atom Lite), utan moln |
| [ambientika-local-app](https://github.com/ambientika-eu/ambientika-local-app) | Eget gränssnitt (PWA) i hemnätet. Valfritt lokalt läge: ersätter **bryggan** med en lokal som kommunicerar direkt med aggregaten. |
| [ambientika-local-standalone](https://github.com/ambientika-eu/ambientika-local-standalone) | Ersätter **servern**: Ambientika-appen körs oförändrad mot en lokal tjänst i hemnätet |
| [ambientika-rs485-boost-button](https://github.com/ambientika-eu/ambientika-rs485-boost-button) | Tryckknappsingång via RS485 för ADVANCED+ / ADVANCED B+ |

De två serverfria varianterna skiljer sig i omfattning: `local-app` ersätter endast dataanslutningen för sitt eget gränssnitt, `local-standalone` servern själv. Båda är avsedda som **reservnivå** — för underhållsfönster, nätstörningar eller byggnader utan permanent internetanslutning — och levereras som kontrollerad leverans. För normal drift är vägen via Ambientika-servern fortsatt den rekommenderade varianten.

[ambientika.eu](https://www.ambientika.eu)
