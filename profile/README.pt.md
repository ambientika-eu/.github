🌐 [DE](README.md) · [EN](README.en.md) · [IT](README.it.md) · [FR](README.fr.md) · [ES](README.es.md) · [NL](README.nl.md) · [PL](README.pl.md) · **PT** · [SV](README.sv.md) · [DA](README.da.md) · [CS](README.cs.md)

## Ambientika / Südwind GmbH

Integrações abertas para os equipamentos de ventilação Ambientika — Home Assistant, MQTT, KNX e funcionamento local.

| Repositório | Finalidade |
|---|---|
| [ambientika-mqtt-bridge](https://github.com/ambientika-eu/ambientika-mqtt-bridge) | Bridge MQTT através do servidor Ambientika — para Home Assistant, ioBroker, openHAB, Loxone, Node-RED. **Recomendada para a exploração corrente.** |
| [ambientika-ha-addon](https://github.com/ambientika-eu/ambientika-ha-addon) | A mesma bridge como add-on para Home Assistant OS |
| [ambientika-local-app](https://github.com/ambientika-eu/ambientika-local-app) | Interface própria (PWA) na rede doméstica. Modo local opcional: substitui **a bridge** por uma local que comunica diretamente com os equipamentos. |
| [ambientika-local-standalone](https://github.com/ambientika-eu/ambientika-local-standalone) | Substitui **o servidor**: a app Ambientika funciona sem alterações contra um serviço local na rede doméstica |
| [ambientika-rs485-boost-button](https://github.com/ambientika-eu/ambientika-rs485-boost-button) | Entrada de botão via RS485 para ADVANCED+ / ADVANCED B+ |

As duas variantes sem servidor diferem no âmbito: `local-app` substitui apenas a ligação de dados da sua própria interface, `local-standalone` o próprio servidor. Ambas foram concebidas como **nível de recurso** — para janelas de manutenção, falhas de rede ou edifícios sem ligação permanente à internet — e são disponibilizadas como entrega controlada. Para a exploração corrente, a via através do servidor Ambientika mantém-se a variante recomendada.

[ambientika.eu](https://www.ambientika.eu)
