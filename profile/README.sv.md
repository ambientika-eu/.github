🌐 [DE](README.md) · [EN](README.en.md) · [IT](README.it.md) · [FR](README.fr.md) · [ES](README.es.md) · [NL](README.nl.md) · [PL](README.pl.md) · [PT](README.pt.md) · **SV** · [DA](README.da.md) · [CS](README.cs.md)

## Ambientika / Südwind GmbH

Öppna integrationer för Ambientika ventilationsaggregat — Home Assistant, MQTT, KNX och lokal drift.

| Repository | Syfte |
|---|---|
| [ambientika-mqtt-bridge](https://github.com/ambientika-eu/ambientika-mqtt-bridge) | MQTT-brygga via Ambientika-servern — för Home Assistant, ioBroker, openHAB, Loxone, Node-RED. **Rekommenderas för normal drift.** |
| [ambientika-ha-addon](https://github.com/ambientika-eu/ambientika-ha-addon) | Samma brygga som tillägg för Home Assistant OS |
| [ambientika-local-app](https://github.com/ambientika-eu/ambientika-local-app) | Eget gränssnitt (PWA) i hemnätet. Valfritt lokalt läge: ersätter **bryggan** med en lokal som kommunicerar direkt med aggregaten. |
| [ambientika-local-standalone](https://github.com/ambientika-eu/ambientika-local-standalone) | Ersätter **servern**: Ambientika-appen körs oförändrad mot en lokal tjänst i hemnätet |
| [ambientika-rs485-boost-button](https://github.com/ambientika-eu/ambientika-rs485-boost-button) | Tryckknappsingång via RS485 för ADVANCED+ / ADVANCED B+ |

De två serverfria varianterna skiljer sig i omfattning: `local-app` ersätter endast dataanslutningen för sitt eget gränssnitt, `local-standalone` servern själv. Båda är avsedda som **reservnivå** — för underhållsfönster, nätstörningar eller byggnader utan permanent internetanslutning — och levereras som kontrollerad leverans. För normal drift är vägen via Ambientika-servern fortsatt den rekommenderade varianten.

[ambientika.eu](https://www.ambientika.eu)
