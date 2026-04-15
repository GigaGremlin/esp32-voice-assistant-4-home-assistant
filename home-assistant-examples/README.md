# 🏠 Home Assistant Integration
So sieht meine Einbindung in HomeAssistant aus 
Ich habe in meinem “Home Assistant“ eine Extraseite für meine Pro VA's erstellt und bequem zwei Geräte nebeneinander 
darstellen / überwachen, ohne das es zu eng auf dem Bildschirm wird. Bei dieser Darstellung kann man die Raumbelegung 
überwachen, ohne dabei auf eine Kamera zurückgreifen zu müssen, was sich besonders für Umkleidekabinen oder ein 
Schlafzimmer eignet und sich auch über eine Mobile Verbindung gut nutzen lässt. 

## 📊 Dashboard Vorschau

**Normalmodus / Standard**

<img width="800" alt="Radar-S3ProCombi-1-HA" src="https://github.com/user-attachments/assets/566f49be-c530-4735-addb-702505874301" />


**Engineering Modus eingeschaltet**
<img width="800" alt="Radar-S3ProCombi-2-HA" src="https://github.com/user-attachments/assets/96e8863f-ca00-4b4a-b913-1f10248f5ef4" />


### Installation
1. Kopiere den Code aus der Datei `ESPHome-S3-Box_Ver4-Radar-HA-Vorlage.yaml`.
2. Erstelle eine neue Karte in HA und füge den Code ein.
3. Passe die Entitäten-Namen an dein Gerät an.
#
 **Wichtig - Vor der Nutzung müssen alle Vorkommen von**
 *esp32s3_va00*
 **durch den eigenen Modul-Namen ersetzt werden !!!**
