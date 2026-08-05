# 🎙️ ESP32 Voice-Assistant für Home Assistant

<div align="center">
  <img width="600" alt="VA-Moon" src="https://github.com/user-attachments/assets/c9c8cb89-40a4-4bee-bc80-fd2fa3c6d50e" />
</div>

---

## Über dieses Projekt

**(ESP32-S3 WROOM-1-N16-R8) Home Assistant Voice Assistant Pro Version**

Meinen Ersatz für den M5AtomEcho gibt es jetzt auch in der Pro Version als Voice Assistant für Home Assistant.

Die Pro Version meines “Voice Assistant“ unterscheidet sich von der Standardausführung durch ein zusätzlich integriertes Radarmodul, einen kleinen physikalischen Button auf der Rückseite und einen vorgeschalteten “CH224K USB-C Schnellladeregler“. Die nötige Pinbelegung für den Anschluss am “ESP32“ findet sich wie immer als Tabelle in meiner “YAML-Firmware-Datei“.

**Update: ab sofort funktioniert Music Assistant mit meiner letzten Firmware einwandfrei!!!**

Die Liste der Komponenten ist wie gewohnt sehr einfach und preiswert gehalten.

Ich verwende die üblichen Verdächtigen: einen Max98357A als Verstärker und ein INMP441 als Mikrofon. Die LED ist eine adressierbare WS2812 mit 5 Volt. Für die gestiegenen Anforderungen habe ich jetzt einen CH224K USB-C Schnellladeregler als Spannungsverteiler vorgeschaltet. Durch dessen Verwendung könnte man jetzt sogar mehrere LEDs anbinden (Einfach die LED-Anzahl in der YAML erhöhen) oder andere Sensor-Module einbinden.

Und was Preis und Leistung angeht, ist dieser Voice Assistant für Home Assistant, gemessen an vergleichbaren Assistenten, immer noch deutlich preiswerter und durch den integrierten Präsenzmelder ist er sogar überlegen, da Anbindung & Steuerung nicht über eine zusätzliche Bluetooth- oder ZigBee-Verbindung erfolgt.

* **Baukosten ohne den 3D Druck:** ca. 35€
* **Geschätzter Marktwert:** 80-120 Euro

---

**(ESP32-S3 WROOM-1-N16-R8) Home Assistant Voice Assistant Pro Version**

My replacement for the M5AtomEcho is now also available in a Pro Version as a Voice Assistant for Home Assistant.

The Pro Version of my "Voice Assistant" differs from the standard model by including an additional radar module, a small physical button on the back, and a preceding "CH224K USB-C Fast Charge Controller". As always, the necessary pinout for connecting to the "ESP32" can be found as a table in my "YAML firmware file."

**Update: Music Assistant is now working perfectly with my latest firmware!!!**

The component list is, as usual, kept very simple and inexpensive. I am using the usual suspects: a Max98357A as an amplifier and an INMP441 as a microphone. The LED is an addressable WS2812 operating at 5 volts. To meet the increased demands, I have now installed a CH224K USB-C Fast Charge Controller as a preceding voltage distributor. By using it, you could now even connect multiple LEDs (simply increase the LED count in the YAML) or integrate other sensor modules.

Regarding price and performance, this Voice Assistant for Home Assistant is still significantly less expensive compared to similar assistants, and due to the integrated presence detector, it is even superior, as connection and control do not require an additional Bluetooth or ZigBee link.

* **Construction costs without 3D print:** approx. €35
* **Estimated market value:** €80–120

---

> [!NOTE]
> **Anschlussbelegung:** Die notwendige Anschlussbelegung ist natürlich in die YAML-Datei integriert. / The necessary pin assignment is integrated into the YAML file.

<div align="center">
  <img width="800" alt="Pinbelegung" src="https://github.com/user-attachments/assets/3639ec3c-d429-47fd-81cf-6061cc5eb183" />
</div></div>

---
<div align="center">
<img width="1780" height="1001" alt="OldPinOut" src="https://github.com/user-attachments/assets/c61b4f29-c43c-4f6b-93c3-e1e6ee75760e" />
</div></div>

---

<div align="center">
  <img width="800" alt="InsideView" src="https://github.com/user-attachments/assets/c6c4eb46-9b17-49e7-bda7-7e0bb6c6b25a" />
</div></div>

---
* **Achtung !!!** - Da ich für meine letzten S3 Module die preiswerten Versionen von Ali gekauft habe und es mir nicht gelungen ist darauf die gleiche Standardkonfiguration zum laufen zu bringen, wie bei meinen Marken Modulen,
verstehe ich jetzt auch die Probleme, die einige von Euch beim Nachbau hatten.
* Um diese Probleme direkt zu beseitigen, habe ich nun doch die GPIO's für den MAX98357 und das INMP441 getrennt und eine eigene Firmware, basierend auf der neuen Verkabelung erstellt.
* Mit dieser Änderung funktionieren dann auch die Klon-Module als Voice Assistant und Music Assistant Satelliten. 
* Und das lästige Störgeräusch beim Booten ist damit ebenfalls Geschichte.
* **Das Video zur Neuerung ist noch in Arbeit**
---
<div align="center">
<img width="1758" height="989" alt="NewPinOut" src="https://github.com/user-attachments/assets/70ba4db3-5a9c-44b0-86f1-cea102ede2b1" />
</div></div>

---

# YouTube: ESP32 S3 Voice Assistant Pro

<div align="center">
  <a href="https://youtu.be/G6M7URdppqs">
    <img src="https://img.youtube.com/vi/G6M7URdppqs/maxresdefault.jpg" alt="Video Anleitung" width="800">
  </a>
  <p>📺 <i>Klicke auf das Bild, um das Video auf YouTube zu starten</i></p>
</div>


---

## 🛠️ Downloads & Firmware

Wähle die passende Version für deine Hardware:

### 1. Firmware old PinOut Version (YAML Dateien)
* 📥 [**Standard Version**](firmware/standard/) – Ohne Radar-Modul.
* 📥 [**Radar Version**](firmware/radar/) – Optimiert für Anwesenheitserkennung.
* *******************************************************************************
### 2. Firmware new PinOut Version (YAML Dateien)
**(Achtung - Bitte nur noch die Neue Version verwenden !!!)**
* 📥 [**New PinOut Version - Radar Version**](firmware/new/) – Optimiert für alle S3 Module.
* 📥 **New PinOut Version - Version - Ohne Radar-Modul** --- **Demnächst hier als Download**
* *******************************************************************************
* 📁 [Alle Firmware-Versionen durchsuchen](firmware/)
* *******************************************************************************
### 2. Tools & Personalisierung
* 🖥️ [**GGFW Personalizer Tool (EXE)**](gui-tool/)
  
**Nutze dieses Tool, um WLAN-Daten und Namen direkt in der Firmware anzupassen.**

### 3. Gehäuse & 3D-Druck
* 📐 [3D-Druck Dateien (STL)](3D-Print/)

**Es gibt jetzt auch eine neue universal 2,5"-Speaker-Halterung die mit M4 Schrauben funktioniert.**

### 4. Home Assistant - Integration
* 🏠 [**Home Assistant Beispiel-Konfigurationen**](home-assistant-examples/)

**Hier findest du YAML-Ausschnitte für Dashboards und Automatisierungen.**

</div></div>

---

<div align="center">
<i>Zuletzt aktualisiert: August 2026</i>
</div>

</div></div>   
<div align="center">
   <a href="https://gigagremlin.de">
    <img src="https://img.shields.io/badge/Made%20by-GigaGremlin-blue?style=for-the-badge" alt="GigaGremlin Website" />
  </a>
</div>
