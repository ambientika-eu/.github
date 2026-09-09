🌐 [DE](README.md) · [EN](README.en.md) · [IT](README.it.md) · [FR](README.fr.md) · **ES** · [NL](README.nl.md) · [PL](README.pl.md) · [PT](README.pt.md) · [SV](README.sv.md) · [DA](README.da.md) · [CS](README.cs.md)

## Ambientika / Südwind GmbH

Integraciones abiertas para los equipos de ventilación Ambientika — Home Assistant, MQTT, KNX y funcionamiento local.

| Repositorio | Finalidad |
|---|---|
| [ambientika-mqtt-bridge](https://github.com/ambientika-eu/ambientika-mqtt-bridge) | Bridge MQTT a través del servidor Ambientika — para Home Assistant, ioBroker, openHAB, Loxone, Node-RED. **Recomendado para el funcionamiento habitual.** |
| [ambientika-ha-addon](https://github.com/ambientika-eu/ambientika-ha-addon) | El mismo bridge como add-on para Home Assistant OS |
| [ambientika-local-app](https://github.com/ambientika-eu/ambientika-local-app) | Interfaz propia (PWA) en la red doméstica. Modo local opcional: sustituye **el bridge** por uno local que se dirige directamente a los equipos. |
| [ambientika-local-standalone](https://github.com/ambientika-eu/ambientika-local-standalone) | Sustituye **el servidor**: la app Ambientika funciona sin modificaciones contra un servicio local en la red doméstica |
| [ambientika-rs485-boost-button](https://github.com/ambientika-eu/ambientika-rs485-boost-button) | Entrada de pulsador por RS485 para ADVANCED+ / ADVANCED B+ |

Las dos variantes sin servidor difieren en alcance: `local-app` sustituye solo la conexión de datos de su propia interfaz, `local-standalone` el servidor mismo. Ambas están concebidas como **nivel de respaldo** — para ventanas de mantenimiento, incidencias de red o edificios sin conexión permanente a internet — y se suministran como entrega controlada. Para el funcionamiento habitual, la vía a través del servidor Ambientika sigue siendo la variante recomendada.

[ambientika.eu](https://www.ambientika.eu)
