🌐 [DE](README.md) · [EN](README.en.md) · [IT](README.it.md) · [FR](README.fr.md) · [ES](README.es.md) · [NL](README.nl.md) · [PL](README.pl.md) · [PT](README.pt.md) · [SV](README.sv.md) · [DA](README.da.md) · **CS**

## Ambientika / Südwind GmbH

Otevřené integrace pro větrací jednotky Ambientika — Home Assistant, MQTT, KNX a lokální provoz.

| Repozitář | Účel |
|---|---|
| [ambientika-mqtt-bridge](https://github.com/ambientika-eu/ambientika-mqtt-bridge) | Most MQTT přes server Ambientika — pro Home Assistant, ioBroker, openHAB, Loxone, Node-RED. **Doporučeno pro běžný provoz.** |
| [ambientika-ha-addon](https://github.com/ambientika-eu/ambientika-ha-addon) | Tentýž most jako doplněk pro Home Assistant OS |
| [ambientika-local-app](https://github.com/ambientika-eu/ambientika-local-app) | Vlastní rozhraní (PWA) v domácí síti. Volitelný lokální režim: nahrazuje **most** lokálním, který komunikuje s jednotkami přímo. |
| [ambientika-local-standalone](https://github.com/ambientika-eu/ambientika-local-standalone) | Nahrazuje **server**: aplikace Ambientika běží beze změny proti lokální službě v domácí síti |
| [ambientika-rs485-boost-button](https://github.com/ambientika-eu/ambientika-rs485-boost-button) | Tlačítkový vstup přes RS485 pro ADVANCED+ / ADVANCED B+ |

Obě varianty bez serveru se liší rozsahem: `local-app` nahrazuje pouze datové napojení vlastního rozhraní, `local-standalone` samotný server. Obě jsou zamýšleny jako **záložní úroveň** — pro servisní okna, výpadky sítě nebo objekty bez trvalého připojení k internetu — a jsou poskytovány jako řízené vydání. Pro běžný provoz zůstává doporučenou variantou cesta přes server Ambientika.

[ambientika.eu](https://www.ambientika.eu)
