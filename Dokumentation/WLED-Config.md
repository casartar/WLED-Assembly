# WLED-Config

## Vorbereitung

Lade dir die WLED-APP von Aircookie herunter.

* [Playstore](https://play.google.com/store/apps/details?id=com.aircoookie.WLED&hl=de&gl=US) mit widerlichem Google
* [GitHub](https://github.com/Aircoookie/WLED-App/releases) ohne widerliches Google

## Konfiguration

### Smartphone mit WLED-AP verbinden

Der frisch geflashte und unkonfigurierte Controller (ESP8266) strahlt nach dem Einschalten ein WLAN aus Namens "WLED-AP". Verbinde dich damit und klicke auf "Im Netzwerk anmelden"!

<img src="Bilder/Screenshot_20210623-214006.jpg" width=50% height=50%>

Normalerweise wirst du nach dem Verbinden mit dem WLAN direkt auf die WLED Konfigurationsseite umgeleitet (Captive Portal). Wenn das nicht funktioniert, musst du im Browser die IP-Adresse "4.3.2.1" ansurfen.

Hier kannst du WLED ins heimische WLAN integrieren, oder direkt steuern:

<img src="Bilder/Screenshot_20210623-214020.jpg" width=50% height=50%>

Drücke "WIFI SETTINGS".

### WLED mit heimischem WLAN verbinden

Gib hier die Zugangsdaten für dein heimisches IoT WLAN an ;) (SSID und Passwort reicht).

Drücke danach "Save & Connect"

<img src="Bilder/Screenshot_20210623-214031.jpg" width=50% height=50%>

Der WLED Controller bootet nun und verbindet sich danach mit deinem heimischen WLAN.
