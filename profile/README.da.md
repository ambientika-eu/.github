🌐 [DE](README.md) · [EN](README.en.md) · [IT](README.it.md) · [FR](README.fr.md) · [ES](README.es.md) · [NL](README.nl.md) · [PL](README.pl.md) · [PT](README.pt.md) · [SV](README.sv.md) · **DA** · [CS](README.cs.md)

## Ambientika / Südwind GmbH

Åbne integrationer til Ambientika ventilationsaggregater — Home Assistant, MQTT, KNX og lokal drift.

| Repository | Formål |
|---|---|
| [ambientika-mqtt-bridge](https://github.com/ambientika-eu/ambientika-mqtt-bridge) | MQTT-bridge via Ambientika-serveren — til Home Assistant, ioBroker, openHAB, Loxone, Node-RED. **Anbefales til normal drift.** |
| [ambientika-ha-addon](https://github.com/ambientika-eu/ambientika-ha-addon) | Samme bridge som add-on til Home Assistant OS |
| [HomeAssistant-integration-for-Ambientika](https://github.com/ambientika-eu/HomeAssistant-integration-for-Ambientika) | Integrationen “Ambientika for Home Assistant”, installeres via HACS |
| [ambientika-local-app](https://github.com/ambientika-eu/ambientika-local-app) | Egen brugerflade (PWA) i hjemmenetværket. Valgfri lokal tilstand: erstatter **bridgen** med en lokal, der taler direkte med aggregaterne. |
| [ambientika-local-standalone](https://github.com/ambientika-eu/ambientika-local-standalone) | Erstatter **serveren**: Ambientika-appen kører uændret mod en lokal tjeneste i hjemmenetværket |
| [ambientika-rs485-boost-button](https://github.com/ambientika-eu/ambientika-rs485-boost-button) | Trykknapindgang via RS485 til ADVANCED+ / ADVANCED B+ |

De to serverfrie udgaver adskiller sig i omfang: `local-app` erstatter kun dataforbindelsen for sin egen brugerflade, `local-standalone` selve serveren. Begge er tænkt som **reserveniveau** — til vedligeholdelsesvinduer, netværksforstyrrelser eller bygninger uden permanent internetforbindelse — og leveres som kontrolleret levering. Til normal drift er vejen via Ambientika-serveren fortsat den anbefalede variant.

[ambientika.eu](https://www.ambientika.eu)
