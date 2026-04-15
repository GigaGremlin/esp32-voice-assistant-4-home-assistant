# 🎙️ ESP32 Voice-Assistant für Home Assistant

  <img width="600" alt="VA-Moon" src="https://github.com/user-attachments/assets/c9c8cb89-40a4-4bee-bc80-fd2fa3c6d50e" />

## Über dieses Projekt
(ESP32-S3 WROOM-1-N16-R8) Home Assistant Voice Assistant Pro Version

Meinen Ersatz für den M5AtomEcho gibt es jetzt auch in der Pro Version als Voice Assistant für Home Assistant.

Die Pro Version meines “Voice Assistant“ unterscheidet sich von der Standardausführung durch ein zusätzlich integriertes Radarmodul, einen kleinen physikalischen Button auf der Rückseite und einen vorgeschalteten “CH224K USB-C Schnellladeregler“. Die nötige Pinbelegung für den Anschluss am “ESP 32“ findet sich wie immer als Tabelle in meiner “YAML-Firmware-Datei“

Die Liste der Komponenten ist wie gewohnt sehr einfach und preiswert gehalten.

Ich verwende die üblichen Verdächtigen einen Max98357A als Verstärker und ein INMP441 als Mikrofon. Die LED ist eine Adressierbare WS2812 mit 5 Volt. Für die gestiegenen Anforderung habe ich jetzt einen CH224K USB-C Schnellladeregler als Spannungsverteiler vorgeschaltet. Durch dessen Verwendung könnte man jetzt sogar mehrere LED's anbinden (Einfach die LED-Anzahl in der YAML erhöhen) oder andere Sensor-Module einbinden.

Und was Preis und Leistung angeht ist dieser Voice Assistant für Home Assistant, gemessen an vergleichbaren Assistenten immer noch deutlich preiswerter und durch den integrierten Präsenzmelder ist er sogar überlegen, da Anbindung & Steuerung nicht über eine zusätzliche Bluetooth oder ZigBee Verbindung erfolgt.

Baukosten ohne den 3D Druck: ca. 35€
Geschätzter Marktwert für den fertigen Voice Assistant: 80-120 Euro

---

(ESP32-S3 WROOM-1-N16-R8) Home Assistant Voice Assistant Pro Version

My replacement for the M5AtomEcho is now also available in a Pro Version as a Voice Assistant for Home Assistant.

The Pro Version of my "Voice Assistant" differs from the standard model by including an additional radar module, a small physical button on the back, and a preceding "CH224K USB-C Fast Charge Controller". As always, the necessary pinout for connecting to the "ESP32" can be found as a table in my "YAML firmware file."

The component list is, as usual, kept very simple and inexpensive. I am using the usual suspects: a Max98357A as an amplifier and an INMP441 as a microphone. The LED is an addressable WS2812 operating at 5 volts. To meet the increased demands, I have now installed a CH224K USB-C Fast Charge Controller as a preceding voltage distributor. By using it, you could now even connect multiple LEDs (simply increase the LED count in the YAML) or integrate other sensor modules.

Regarding price and performance, this Voice Assistant for Home Assistant is still significantly less expensive compared to similar assistants, and due to the integrated presence detector, it is even superior, as connection and control do not require an additional Bluetooth or ZigBee link.

Construction costs without the 3D print: approx. €35

Estimated market value for the finished Voice Assistant: €80–120

---
Die notwendige Anschlussbelegung ist natürlich in die YAML-Datei integriert
The necessary pin assignment is of course integrated into the YAML file.


  <img width="600" alt="Pinbelegung" src="https://github.com/user-attachments/assets/3639ec3c-d429-47fd-81cf-6061cc5eb183" />

---

## 🛠️ Downloads & Firmware

Wähle die passende Version für deine Hardware:

### 1. Firmware (YAML Dateien)
* 📥 [**Standard Version**](firmware/standard/) – Ohne Radar-Modul.
* 📥 [**Radar Version**](firmware/radar/) – Optimiert für Anwesenheitserkennung.
* 📁 [Alle Firmware-Versionen durchsuchen](firmware/)

### 2. Tools & Personalisierung
* 🖥️ [**GGFW Personalizer Tool (EXE)**](gui-tool/)
  *Nutze dieses Tool, um WLAN-Daten und Namen direkt in der Firmware anzupassen.*

### 3. Gehäuse & 3D-Druck
* 📐 [3D-Druck Dateien (STL)](3D-Print/)

### 4. Home Assistan - Integration
* 🏠 [**Home Assistant Beispiel-Konfigurationen**](home-assistant-examples/)
  *Hier findest du YAML-Ausschnitte für Dashboards und Automatisierungen.*

---
*Erstellt von [GigaGremlin / gigagremlin.de]*
