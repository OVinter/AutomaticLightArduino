# SI - proiect

# Sistem de control al becurilor de pe strada

## Descriere

Scopul proiectului este reducerea consumului de energie (este estimat ca acest consum reprezintă 19% din totalul de energie consumata din lume). Sistemul va încerca sa activeze becurile doar în momentul în care trece o persoana sau o mașină.

Resurse propuse spre utilizare:

* Placa de dezvoltare UNO R3 compatibil Arduino

* Modul Senzor PIR HC-SR501 pentru miscare

* Senzor ultrasonic HC-SR04 -> pentru distanta

* Modul cu Fotorezistor -> pentru lumina

* Modul Bluetooth Master Slave HC-05 -> pentru aplicatia *Android*

* Modul releu 1 canal comandat 5V -> pentru controlarea curentului

* Breadboard 830 puncte MB-102

* LED 5mm -> pentru confirmari

* Rezistenta 220ohmi -> pentru a nu arde led-ul


### Detalii proiect

* Parametrii masurati, dar și controlul becurilor, se va realiza de pe o aplicație mobila pentru Android

* Datele vor fi transmise spre un server pentru procesare

* Datele preluate trebuie analizate și în momente bine stabilite se vor acționa actuatorii

* Modulul bluetooth va comunica datele preluate de catre ceilalti senzori catre aplicatia de android


### Detalii aplicatie

* Aprindem/stingem becul manual

* Afisare status bec(on/off)

* Afisare date prelauate de catre senzori

