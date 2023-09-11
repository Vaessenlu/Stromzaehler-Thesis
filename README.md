# Stromzaehler-Thesis 
Das folgende Projekt wurde als Abschlussarbeit an der Hochschule Pforzheim durchgeführt, um einen analogen Stromzähler auszulesen. Weitere Informationen können aus der [Thesis](https://github.com/Vaessenlu/Stromzaehler-Thesis/blob/main/Thesis_Lukas_Vaessen-Mat_321987.pdf) entnommen werden.

![Bildversuchsaufbau](https://github.com/Vaessenlu/Stromzaehler-Thesis/assets/119928392/eadeaf81-7301-438f-9c34-922f3c2bb129)

## Benötigte Materialien

1. Kreppband für Montage an Zähler
2. Timer Cam X von M5Stack
3. Lego Bauteile
4. Externe LED
5. Computer/Server zum ausführen des Codes

## Aufbau Anleitung und Inbetriebnahme
1. Timer Cam X via Arduino IDE flashen
2. Seriellen Monitor aktivieren um IP-Adresse des Webservers zu erhalten
3. LED an Timer Cam X anschließen via Groove-Port
4. Webserver über IP-Adresse aufrufen und testen mit ip/capture
5. Python Code in lokales Jupyter Notebook laden
6. [OCR.Space](https://ocr.space/) besuchen und kostenfreien API-Key beantragen
7. API-Key, Wifi und Dateipfad für CSV in die Platzhalter eintragen
8. Geflashte Timer Cam X an Zähler montieren mit LEGO Bausteinen und Kreppband
9. Jupyter Notebook manuell ausführen und Crop Einstellungen anpassen, nach Bedarf
10. Batch-Datei erstellen und via Windowsaufgabenplanner ausführen    

## Hinweis

Zum anpassen der LED-Codierung müssen die folgenden C++ Libraries angepasst werden.

 1. app_httpd.cpp
 2. led.c
 3. led.h
    
Für die Anpassungen wurde Visual Studio mit einer C++ IDE verwendet. 

## Anhang:
1. [Timer Cam X Shop & Dokumentation](https://shop.m5stack.com/products/esp32-psram-timer-camera-x-ov3660?variant=36362228301988)
2. [Jupyter Notebook download](https://jupyter.org/install) 
3. [Arduino download](https://www.arduino.cc/en/software)
4. [LED](https://docs.m5stack.com/en/unit/FlashLight)
5. [Visual Studio](https://code.visualstudio.com/?wt.mc_id=vscom_downloads)
