🌐 [DE](README.md) · [EN](README.en.md) · **IT** · [FR](README.fr.md) · [ES](README.es.md) · [NL](README.nl.md) · [PL](README.pl.md) · [PT](README.pt.md) · [SV](README.sv.md) · [DA](README.da.md) · [CS](README.cs.md)

## Ambientika / Südwind GmbH

Integrazioni aperte per le unità di ventilazione Ambientika — Home Assistant, MQTT, KNX e funzionamento locale.

| Repository | Scopo |
|---|---|
| [ambientika-mqtt-bridge](https://github.com/ambientika-eu/ambientika-mqtt-bridge) | Bridge MQTT tramite il server Ambientika — per Home Assistant, ioBroker, openHAB, Loxone, Node-RED. **Consigliato per l'esercizio ordinario.** |
| [ambientika-ha-addon](https://github.com/ambientika-eu/ambientika-ha-addon) | Lo stesso bridge come add-on per Home Assistant OS |
| [HomeAssistant-integration-for-Ambientika](https://github.com/ambientika-eu/HomeAssistant-integration-for-Ambientika) | Integrazione “Ambientika for Home Assistant”, installazione tramite HACS |
| [ambientika-local-app](https://github.com/ambientika-eu/ambientika-local-app) | Interfaccia propria (PWA) nella rete domestica. Modalità locale opzionale: sostituisce **il bridge** con uno locale che comunica direttamente con le unità. |
| [ambientika-local-standalone](https://github.com/ambientika-eu/ambientika-local-standalone) | Sostituisce **il server**: l'app Ambientika funziona senza modifiche con un servizio locale nella rete domestica |
| [ambientika-rs485-boost-button](https://github.com/ambientika-eu/ambientika-rs485-boost-button) | Ingresso a pulsante via RS485 per ADVANCED+ / ADVANCED B+ |

Le due varianti senza server differiscono per portata: `local-app` sostituisce solo il collegamento dati della propria interfaccia, `local-standalone` il server stesso. Entrambe sono concepite come **livello di riserva** — per finestre di manutenzione, disservizi di rete o edifici senza connessione internet permanente — e vengono fornite come rilascio controllato. Per l'esercizio ordinario resta consigliata la via tramite il server Ambientika.

[ambientika.eu](https://www.ambientika.eu)
