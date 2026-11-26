🌐 [DE](README.md) · [EN](README.en.md) · [IT](README.it.md) · [FR](README.fr.md) · [ES](README.es.md) · [NL](README.nl.md) · **PL** · [PT](README.pt.md) · [SV](README.sv.md) · [DA](README.da.md) · [CS](README.cs.md)

## Ambientika / Südwind GmbH

Otwarte integracje dla central wentylacyjnych Ambientika — Home Assistant, ioBroker, Matter, Homey, ESPHome, MQTT, KNX i praca lokalna.

| Repozytorium | Przeznaczenie |
|---|---|
| [ambientika-mqtt-bridge](https://github.com/ambientika-eu/ambientika-mqtt-bridge) | Mostek MQTT przez serwer Ambientika — dla Home Assistant, ioBroker, openHAB, Loxone, Node-RED. **Zalecany do eksploatacji bieżącej.** |
| [ambientika-ha-addon](https://github.com/ambientika-eu/ambientika-ha-addon) | Ten sam mostek jako dodatek do Home Assistant OS |
| [HomeAssistant-integration-for-Ambientika](https://github.com/ambientika-eu/HomeAssistant-integration-for-Ambientika) | Integracja „Ambientika for Home Assistant” — do znalezienia przez wyszukiwanie w HACS i w Marketplace Home Assistant |
| [ioBroker.ambientika](https://github.com/ambientika-eu/ioBroker.ambientika) | Adapter dla ioBroker (przez serwer Ambientika) |
| [matterbridge-ambientika](https://github.com/ambientika-eu/matterbridge-ambientika) | Wtyczka do Matterbridge — udostępnia centrale przez Matter w Apple Home, Google Home, Amazon Alexa, SmartThings |
| [homey-ambientika](https://github.com/ambientika-eu/homey-ambientika) | Aplikacja dla Homey Pro (SMART, OFFICE) |
| [ESPHome-RS485-gateway-for-Ambientika](https://github.com/ambientika-eu/ESPHome-RS485-gateway-for-Ambientika) | Lokalne sterowanie ADVANCED+ / ADVANCED B+ przez RS485 z ESPHome (M5Stack Atom Lite), bez chmury |
| [ambientika-local-app](https://github.com/ambientika-eu/ambientika-local-app) | Własny interfejs (PWA) w sieci domowej. Opcjonalny tryb lokalny: zastępuje **mostek** lokalnym, który komunikuje się z urządzeniami bezpośrednio. |
| [ambientika-local-standalone](https://github.com/ambientika-eu/ambientika-local-standalone) | Zastępuje **serwer**: aplikacja Ambientika działa bez zmian wobec lokalnej usługi w sieci domowej |
| [ambientika-rs485-boost-button](https://github.com/ambientika-eu/ambientika-rs485-boost-button) | Wejście przyciskowe przez RS485 dla ADVANCED+ / ADVANCED B+ |

Obie warianty bez serwera różnią się zakresem: `local-app` zastępuje tylko połączenie danych własnego interfejsu, `local-standalone` sam serwer. Oba pomyślane są jako **poziom awaryjny** — na okna serwisowe, awarie sieci lub obiekty bez stałego łącza internetowego — i są udostępniane jako wydanie kontrolowane. Do eksploatacji bieżącej zalecaną drogą pozostaje serwer Ambientika.

[ambientika.eu](https://www.ambientika.eu)
