# Adafruit-IO app

Gemaakt door Tim Meeuwsen

## Introductie
Ik heb een app gemaakt waarbij je de LEDstrip kleuren kan aanpassen via de wifi. Met de app kan je kiezen uit een stadaard patroon of een bepaalden kleur.

## Benodigheden
1x Arduino Board(met wifi)
1x ledstrip
1x usb naar arduino poort
3x verbindingsdraden (vast gelijmt aan ledstrip)

![IMG_20211007_161030206](https://user-images.githubusercontent.com/29665951/136402185-46be7434-224d-4d7e-a826-abde8273721e.jpg)

## Stap 1 (Instaleren Adafruit IO)
Open de arduino software en ga naar Sketch > Include library > Mannage libraries.

![image](https://user-images.githubusercontent.com/29665951/136405326-cf4ddd80-7a95-4a07-acf5-65730b938cf8.png)

Een nieuw venster moet dan openen van de library manager hier type je dan in het zoekveld Adafruit IO Arduino. Zoek in de lijst en klik vervolgens op instaleren > install all.

![image](https://user-images.githubusercontent.com/29665951/136405252-8be0067d-e780-48c9-88f0-a2a0fab64f59.png)

## Stap 2 Aanmelden en deshboard maken
Maak een account aan op https://io.adafruit.com/.  Wanneer je naar https://io.adafruit.com/timmit147/dashboards gaat kan je bij My key de Username en Active Key copieren.

![image](https://user-images.githubusercontent.com/29665951/136407565-6c9930a1-f342-4b2b-b435-9a73e958fa3f.png)

Klik daarna op new dashboard en kies een naam een beschijving.

![image](https://user-images.githubusercontent.com/29665951/136407780-0e244058-1e17-49a4-b7c6-671dbd282989.png)

Aan de rechter kant kan je een nieuw blok aanmaken kies hierbij color picker en vul velvolgens de gegevens in.

![image](https://user-images.githubusercontent.com/29665951/136408107-436826b9-3d1c-49f6-b578-14f2371caf37.png)

![image](https://user-images.githubusercontent.com/29665951/136408199-3ed8a4a5-84a8-4e2a-ac84-a2541d9e42d6.png)

## Stap 3 Code connecten

Ga naar de arduino File > Examples > Adafruit IO Arduino > Adafruitio_14_neopixel

Verander in de code : #define PIXEL_PIN 5  naar #define PIXEL_PIN D5

## Fouten 
Ik begreep eerst niet dat de Baud rate per programa anders kan zijn en dat ik deze dan elke keer moet aanpassen.
