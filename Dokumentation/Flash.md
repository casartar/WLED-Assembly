# Flashen des Controllers

Gehe mit Google Chrome/Chromium auf folgede Website  [install.wled.me](https://install.wled.me/) 

Wähle aus dem Drop-Down Menü das letzte Release aus. (Hier 0.13.3)

<img src="Bilder/Screenshot_20230205_175032.png" width=50% height=50%>

Wenn du Install klickst, wirst du nach dem Zugriff auf die serielle Schnittstelle gefragt. Welchen du mit "Verbinden" gewären musst.

Wenn nicht klar ist, welche Schnittstelle du brauchst, musst du unter Linux in /dev nachsehen und unter Windows im Gerätemanager unter "COM & LPT". Einfach den Controller vom USB trennen und wieder verbinden. Das was sich ändert ist der richtige Anschluss.

<img src="Bilder/Screenshot_20230205_175330.png" width=50% height=50%>

"Install WLED" anklicken. 

<img src="Bilder/Screenshot_20230205_175405.png" width=50% height=50%>

"Install" anklicken.

<img src="Bilder/Screenshot_20230205_175422.png" width=50% height=50%>

Warten.

<img src="Bilder/Screenshot_20230205_175432.png" width=50% height=50%>

Warten.

<img src="Bilder/Screenshot_20230205_175450.png" width=50% height=50%>

"NEXT" anklicken.

<img src="Bilder/Screenshot_20230205_175527.png" width=50% height=50%>




## ALTERNATIVE Methode

 1. Runterladen der Firmware:

[Binary für Wemos D1 mini](https://github.com/Aircoookie/WLED/releases/download/v0.14.0-b1/WLED_0.14.0-b1_ESP01.bin)

[Sonstige](https://github.com/Aircoookie/WLED/releases)



 2. Runterladen eines der Flash tools:

[Tasmotizer (Windows)](https://github.com/tasmota/tasmotizer/releases)

[ESPHome Flasher](https://github.com/esphome/esphome-flasher/releases)


3. So jetzt das Tool öffnen ( am Beispiel vom ESPHome Flasher):

![ESP Home FLasher](Bilder/Bildschirm%C2%ADfoto%202023-02-14%20um%2021.47.09.jpg)

4. Den richtigen Serial Port auswählen:
![ausgewählter Serial Port](Bilder/Bildschirm%C2%ADfoto%202023-02-14%20um%2021.57.58.jpg)

5. Dann das runtergeladene Firmware-File auswählen ( Browse klicken)

![Select Firmware File](Bilder/Bildschirm%C2%ADfoto%202023-02-14%20um%2021.48.16.jpg)

6. Dann auf "Flash ESP" klicken:

![Alles selektiert](Bilder/Bildschirm%C2%ADfoto%202023-02-14%20um%2021.54.48.jpg)

7. Dann sollte es  gleich so aussehen:

![Fertig](Bilder/Bildschirm%C2%ADfoto%202023-02-14%20um%2021.55.20.jpg)

FERTIG :)